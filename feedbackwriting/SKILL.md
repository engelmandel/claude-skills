---
name: "feedbackwriting"
description: "Corrects a photographed or scanned student text: marks errors with green underlines and margin symbols, explains each error category, writes an improved version and short feedback, and creates targeted practice exercises with answers. Student name removed throughout."
---

# feedbackwriting – correct student texts, give feedback, practise

Goal: from a photographed or scanned student text (usually handwritten; subjects such as English, German or Ethics), produce a feedback package with:
1. the corrected sheet (errors underlined in green, correction symbols in the margin),
2. correction notes by error category, each with the rule and a learning tip,
3. an improved version of the text and short, appreciative feedback,
4. practice exercises aimed precisely at the errors in this text,
5. answers to the exercises (kept separate, so they can be handed out later).

Talk to the teacher in their language; write the exercise content in the subject language (e.g. English for an English text).

**Output format is open.** Deliver the package in whatever form the environment and the teacher prefer: a document, a page, a set of files, or directly in the chat. If the teacher hasn't said, ask once or choose the format that is easiest to print and hand out. The steps below describe the content, not a particular file type.

## 0. Data protection (always)
- **Never carry over the student's name**: not in titles, footers, file names, document metadata, or your reply.
- Cover a handwritten name on the photo **with the paper colour** (sample the colour right next to the name; align the covering shape with the slant of the paper).
- Never store student names or student-specific details in memory.
- Delete intermediate files that still show the name, and check the finished output for the name (e.g. extract its text and search for the name).
- The date of the work may stay.

## 1. Read the text and identify the errors
- Look at the image. Transcribe the text completely, including crossings-out and insertions.
- Record and categorise every error. Default correction symbols (German school convention; replace them with the symbols used at your school if they differ):
  - **R** spelling (Rechtschreibung) · **Gr** grammar · **Z** punctuation (Zeichensetzung) · **A** expression/style (Ausdruck) · **W** word choice (Wortwahl) · **St** word order (Satzstellung) · where needed **T** tense, **Bz** reference (Bezug), **I** content (Inhalt)
- For each error note: original word, correction, rule, line.
- Look for patterns: which error type occurs most often? That becomes the focus of the feedback and the exercises. Name first-language interference where you see it (e.g. j/y, v/f, literal translations of idioms, false friends).
- Mark only genuine errors; don't over-correct minor matters of style.

## 2. Create the corrected image
If the environment can run code (e.g. Python with PIL and OpenCV), annotate the image directly. Otherwise, describe the corrections line by line instead.

1. Apply the EXIF orientation to the original and check its size.
2. Estimate the coordinates of each error word **at the scale you are viewing** the image, and convert to the original size. Keep a list: `(x1, x2, baseline_y, symbol)`.
3. **Draw roughly, look, then correct** – at least one review pass until every underline sits exactly under the right word.
4. Marking style:
   - Colour green `(20, 140, 60)`, slightly transparent.
   - Underlines **slightly wavy** (sine plus a little noise, slight tilt of ±3 px), drawn as a double line of about 3.6 px / 2.2 px to look like a pen stroke.
   - Margin symbols in a handwriting font such as **Caveat Bold** (open licence, available e.g. via `@fontsource/caveat`), about 40 px at a 1500 px image width, each symbol slightly rotated (−6° to +4°) with small variations in x-position. A handwriting font looks more natural than a hand-drawn stroke simulation.
   - Several errors in one line → symbols side by side (e.g. "Z  Gr"), level with the line in the right margin.
5. Cover the name (see 0).
6. **Crop to the sheet so that no table or background is visible:** determine the four paper corners (visually; automatic threshold detection is unreliable), then apply a perspective transform onto a rectangle in the **sheet's natural aspect ratio** (don't stretch it to A4, or the handwriting will be distorted). Set the corners slightly inwards. Fill rounded corners or dog-ears with the paper colour. Then check the edges (no leftover background, no cut-off date, no smudge lines).

## 3. Assemble the feedback package
Keep the design plain and print-friendly: clear headings, a few light-tinted boxes to separate sections, readable body text. Follow the teacher's or school's own design guidelines if they provide any.

Sections, in this order:
- **Correction:** title "Correction: <text type> '<topic>'", date of the work, a legend of the correction symbols, then the cropped, annotated sheet as large as possible.
- **Correction notes:** one line with error counts per category. For each category (sorted by frequency) a table *Your text | Correct | Rule/tip*, followed by a highlighted "Learning tip" box (a rule of thumb, mnemonic, or method).
- **Improved version:** the complete text without errors, in the student's own voice (correct it, don't polish it into something else).
- **Feedback:** 2–3 sentences, addressed directly to the student. First a strength (content), then **one** clear focus for next time.
- **Practice exercises** (with an empty name/date line to fill in):
  - One exercise per frequent error type; build the sentences from the content of the student's text where possible (e.g. characters from the book they wrote about).
  - Formats that work well: gap fill with verb forms · find the error and rewrite the sentence · choose the right option (this/these, then/than) · a personal error dictionary as a table (error word | correct | own example sentence) with the method "read – cover – write – compare" · contractions/punctuation · translation versus literal transfer / false friends · building sentences from word blocks · a correction task in the exercise book with a ☐ checklist · an extension task (transfer, e.g. summarise the next chapter and highlight its features in colour).
  - Sprinkle in mnemonic boxes.
  - Don't split an exercise across pages; avoid nearly empty pages. If space runs short, replace writing lines with "in your exercise book".
- **Answers** (separate, last section): table Exercise | Answer.
- Footer (if the format has one): subject · text type · date · page number. **No name.**

## 4. Check and deliver
- Look over the finished package: layout, page breaks if it will be printed, image crop.
- Check the answers against the exercises (number, order, correctness).
- Check that the student's name appears nowhere (see 0).
- Deliver it in the agreed format. Suggested name: `<topic>_correction_and_exercises`.
- Keep the reply short: what's included (section overview), which error type is the focus, and any uncertain readings of the handwriting.

## 5. Common change requests
- "The symbols should look more handwritten" → vary the rotation and size of the handwriting font more, make the underlines wavier; don't switch to a stroke simulation.
- "Go back" → restore the previous version (keep each version's script or file).
- "Adjust the crop / remove the table" → perspective correction as in step 2.6.
- Only text feedback wanted → give an overview in the reply instead of a full package.
