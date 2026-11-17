# NutrimedDx🩺

A browser game that helps nutrition and dietetics students learn clinical nutrition. It is a single `index.html` file with no build step and no dependencies.

> Educational use only. Cases are fictional. Doses and targets reflect common adult or WHO reference values; always check your local formulary and protocols. Live Demo: https://naire-arch.github.io/NutriMedDx/

## Game modes
- **Jargon Blitz:** 44 medical terms, asked as term-to-meaning and meaning-to-term
- **Ward Conditions:** 20 questions on the nutrition management of conditions seen on the wards (renal, liver, GI, diabetes, paediatrics, pressure ulcers and more)
- **Case Files:** 10 cases with history, symptoms and labs. Choose the diagnosis, then the nutrition management
- **Meds & Supplements:** 20 questions on indications, doses and counselling (thiamine, folic acid, iron, B12, vitamin D, zinc, vitamin A, lactulose, pancreatic enzymes and more)
- **Ward Round Challenge:** a mixed round with 3 lives
- **Glossary:** searchable study list of all jargon terms

XP, streak bonuses, levels (Student Dietitian to Consultant) and badges are saved in the browser's `localStorage`. Keyboard: press 1–4 to answer and Enter for the next question.

## Add your own questions
All content is at the top of the `<script>` in `index.html`:
- `JARGON`: `[term, definition]`
- `COND` and `MEDS`: `[question, correct answer, [3 wrong answers], explanation]`
- `CASES`: title, patient, history, signs, labs, then the diagnosis and management questions

Keep exactly three wrong answers per question. Have a clinician review any new content.
