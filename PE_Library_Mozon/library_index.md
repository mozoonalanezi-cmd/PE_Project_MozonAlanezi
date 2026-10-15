# PE_Library_Mozon — Library Index

Owner: Mozon Alanezi
Scenario: Learner Support Desk at a Training Center
Prefix: TC
Date: 2026_10_15

## Templates

| Template | Task | Variables | Version | Status |
|---|---|---|---|---|
| TC-Answer-MemberQuestion-v1_2026_10_15.md | Answer a learner’s question | INPUT_TEXT, LANGUAGE, TONE, MAX_WORDS, FACTS | v1 | Approved |
| TC-Summarize-Message-v1_2026_10_15.md | Summarize a learner’s message | MESSAGE, LANGUAGE, MAX_WORDS, FOCUS | v1 | Approved |
| TC-Classify-Request-v1_2026_10_15.md | Sort incoming requests | REQUEST, LANGUAGE, FOCUS | v1 | Approved |
| TC-Translate-CourseNotice-v1_2026_10_15.md | Bilingual course notice | NOTICE, LANGUAGE, DIRECTION, MAX_WORDS | v1 | Approved |
| TC-CourseStartReminder-v1_2026_10_15.md | Course start reminder | COURSE_NAME, START_DATE, START_TIME, ITEMS_TO_BRING, LANGUAGE, TONE, MAX_WORDS | v1 | Approved |

## Shared Blocks

| File | Purpose |
|---|---|
| blocks/TC-Facts-v1_2026_10_15.md | Approved facts for the Learner Support Desk. |
| rules/TC-Rules-v1_2026_10_15.md | Five responsible-use rules for data, verification, fairness, policy, and human decision. |

## [LANGUAGE] Values

| Value | Meaning |
|---|---|
| Arabic | Answer in Arabic only |
| English | Answer in English only |
| Automated | Reply in the main language of the input |
| Bilingual | Two separate versions: Arabic, then English |
| Mixed | One reply that merges Arabic and English |

## Change Log

- v1 · 2026_10_15 · Initial library index created for the Learner Support Desk scenario.
- v1 · 2026_10_15 · Five approved templates added.
- v1 · 2026_10_15 · Facts block and rules file added.