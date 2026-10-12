# CosmoSG

Cosmopolitan Singapore. A mobile-first, static phrase comparison website with ten everyday expressions across English, Mandarin, Malay, Tamil, Hokkien, Cantonese, Teochew, Hakka/Khek, Tagalog and Vietnamese.

## Use

Open `index.html` in a browser. No dependencies or build step. Search phrases, select a language, and follow the per-entry sources. Phone layouts recompose tables into labelled rows. Desktop keeps a comparison table.

## Accuracy

This is a source-backed starter draft, not a native-speaker-reviewed phrasebook. Confidence labels mean source coverage, not certified translation accuracy. Regional dialect forms and romanisation systems differ. All Hakka entries need Singapore variety review; most Hokkien readings use a Taiwanese reference. Tamil register needs local review. Teochew birthday pronunciation is intentionally withheld.

`data.json` contains the phrase data, sources and confidence notes. The same data is embedded in `index.html` so the page works without a network request. Keep both aligned when editing.

## Inspiration

- https://www.channelnewsasia.com/cna-insider/voices/language-learning-dialects-culture-social-cohesion-6426431
- https://www.channelnewsasia.com/cna-insider/ground-up/dialect-heritage-language-preservation-hokkien-teochew-baba-malay-malayalam-6316366
- https://www.channelnewsasia.com/cna-insider/voices/singapore-chinese-dialect-teochew-skills-language-grandmother-family-5007876
- https://www.channelnewsasia.com/cna-insider/voices/todayvoiceslearnt-7-languages-help-customers-job-4667711

Translation sources: LearnDialect.sg (Singapore teaching resources) and Omniglot (independent comparative phrase reference). Each entry links directly to its source. CNA provides project motivation, not translation validation.

## Privacy

No analytics, account, microphone or external translation service. The page uses no cookies or local storage. Source links and GitHub correction links leave the site.

Prepared 12 October 2026.

## Audio

Each phrase has a Listen button that uses the browser's built-in speech voices (Web Speech API, no server or API key). English, Mandarin, Malay, Tamil, Tagalog, Vietnamese and Cantonese play only if the device has a matching voice; otherwise the button says "No voice on this device". Hokkien, Teochew and Hakka have no device voices and are not faked. Device voices read standard forms, not Singapore-accented speech.
