# Translation Guide

This document defines the translation principles, terminology conventions, editorial standards, and review process for the Persian translation of **Beyond Coding** by David Tuffley.

The goal is to maintain a consistent, accurate, readable, and professional Persian translation throughout the project.

---

## 1. Translation Philosophy

The translation follows a balanced approach between fidelity to the original work and natural Persian writing.

The primary objective is to preserve:

- the meaning of the original text;
- the author's intent;
- the tone and level of formality;
- the logical relationship between ideas.

At the same time, the Persian text should read naturally and should not mechanically reproduce English sentence structures.

Literal translation should be avoided when it produces unnatural, ambiguous, or misleading Persian.

The guiding principle is:

> Preserve the meaning and voice of the original while expressing them naturally in Persian.

---

## 2. Accuracy and Fidelity

The translation should not intentionally:

- omit information from the original text;
- introduce concepts that are not present in the original;
- simplify ideas in a way that changes their meaning;
- add personal interpretation to the translated body text.

When additional explanation is useful, it should be clearly separated from the translation and placed in the **Translator Notes** section.

---

## 3. Technical and Professional Terminology

Technical and professional terminology should be translated consistently throughout the book.

When an important term appears for the first time, the preferred format is:

> مهارت‌های نرم (Soft Skills)

Subsequent occurrences may normally use only the established Persian equivalent:

> مهارت‌های نرم

The English term may be retained when:

- no clear or widely accepted Persian equivalent exists;
- the English term is commonly used by Persian-speaking IT professionals;
- retaining the original term improves technical clarity;
- the context requires distinguishing between closely related concepts.

Terminology decisions should be recorded in `GLOSSARY.md`.

---

## 4. Project Glossary

`GLOSSARY.md` is the authoritative terminology reference for this translation project.

The glossary should be updated whenever:

- a significant technical or professional term is introduced;
- multiple Persian equivalents are possible;
- a terminology decision could affect later chapters;
- consistency across the book needs to be preserved.

Existing glossary decisions should normally be followed throughout the translation.

If a better translation is identified later, the glossary and affected translations should be reviewed together to maintain consistency.

---

## 5. Persian Writing Style

The Persian translation should be:

- natural and readable;
- professional without being unnecessarily formal;
- clear for Persian-speaking IT professionals;
- consistent in terminology and tone.

English syntax should not be reproduced mechanically when Persian sentence structure provides a clearer result.

Long English sentences may be divided into shorter Persian sentences when necessary for readability, provided that the meaning and logical relationships are preserved.

Similarly, short sentences may occasionally be combined when doing so produces more natural Persian without changing the author's meaning or emphasis.

---

## 6. Names, Products, and Established Terms

Names of people, organizations, technologies, products, standards, and established technical identifiers should normally retain their original form where appropriate.

A Persian rendering or explanation may be provided when it improves readability.

Code, commands, URLs, file names, identifiers, and similar technical elements should not be translated unless the context specifically requires explanation.

---

## 7. Punctuation and Typography

Persian punctuation and typographic conventions should be used in the translated text.

This includes appropriate use of:

- Persian comma (`،`);
- Persian question mark (`؟`);
- Persian quotation and parenthetical conventions where appropriate;
- Persian spacing and half-space conventions.

English punctuation may remain inside code, URLs, identifiers, quotations, or other contexts where changing it would alter or distort the original content.

---

## 8. Paragraph and Document Structure

The structure of the original book should be preserved wherever practical.

This includes:

- chapters;
- sections;
- headings;
- lists;
- tables;
- quotations;
- examples.

Paragraph boundaries should generally follow the original work so that the translation can be compared and reviewed against the source.

Structural changes may be made when required for Persian readability or Markdown presentation, but they should not alter the organization or meaning of the original content.

---

## 9. Translator Notes

Translator notes may be added when they provide meaningful value to Persian readers.

They may be used for:

- explaining terminology;
- clarifying cultural or professional context;
- providing context that may not be obvious to Persian-speaking readers;
- discussing a translation decision;
- connecting a concept to contemporary software or IT practice where useful.

Translator notes must be clearly distinguished from the author's original text.

They should not interrupt the translation unnecessarily or turn the translated book into a separate commentary.

When used, they should appear in a clearly identified section such as:

**Translator Notes**

The reader must always be able to distinguish between the author's content and the translator's commentary.

---

## 10. AI-Assisted Translation Workflow

This project follows a **human-led translation process supported by AI-assisted tools**.

AI tools may be used for:

- exploring alternative translations;
- terminology research;
- identifying ambiguous passages;
- checking consistency;
- reviewing readability;
- comparing terminology across chapters;
- assisting with editorial review.

AI-generated output is not considered final translation content.

Every translated passage must be reviewed and approved by a human before publication.

The translator remains responsible for:

- interpretation of the source text;
- terminology decisions;
- linguistic quality;
- fidelity to the original;
- final editorial decisions.

Raw AI-generated translation should not be published without human review.

---

## 11. Translation Workflow

The recommended workflow for each section is:

1. Read the complete source passage before translating it.
2. Identify its meaning, context, tone, and important terminology.
3. Check existing terminology decisions in `GLOSSARY.md`.
4. Prepare the Persian translation.
5. Use AI-assisted tools where useful for research, comparison, or review.
6. Review the translation against the original text.
7. Review the Persian text independently for readability and natural expression.
8. Update `GLOSSARY.md` when new terminology decisions are made.
9. Add translator notes only when they provide meaningful additional value.
10. Commit the reviewed translation to the repository.

---

## 12. Review Principles

Before a translation is considered complete, it should be reviewed for:

- accuracy;
- completeness;
- readability;
- terminology consistency;
- Persian grammar and typography;
- consistency with the author's tone;
- correct separation of translation and translator commentary.

A technically correct translation should still be revised if it reads unnaturally in Persian.

Likewise, a fluent Persian translation should be revised if it changes or weakens the meaning of the original.

---

## 13. Contributions and Suggestions

Feedback, corrections, and translation suggestions are welcome.

To maintain consistency across the book, translation decisions remain subject to editorial review by the project maintainer.

Contributors are encouraged to:

- review the existing glossary before proposing terminology changes;
- explain significant translation changes when submitting suggestions;
- preserve the distinction between the original author's content and translator notes;
- follow the principles defined in this guide.

---

## 14. Guiding Principle

When there is a conflict between literal wording and accurate communication of the author's meaning, the translation should favor accurate and natural communication while remaining faithful to the original work.

The final Persian text should feel as though the ideas were clearly expressed in Persian while remaining recognizably faithful to **Beyond Coding**.