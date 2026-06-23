# Style And Lexical Choice

Use this file for stylistic correctness, semantic precision, concise Georgian wording, naturalness, and near-synonym choice. Keep it as a reasoning checklist, not a synonym list or answer database.

## Decision Steps

1. Identify the relation being expressed: person, place, ownership, naming, origin, collective, action, state, or evaluation.
2. Prefer the standard Georgian lexical construction that expresses that relation directly.
3. Reject a grammatically possible form if it is semantically narrower, heavier, calqued, or mismatched to the noun it modifies.
4. If the choice depends on a specific word's accepted meaning or strict school-test norm, route to `lexical-norm-boundary.md` before finalizing.

## Compact Lexical Choice

When two options are both grammatical, prefer the more idiomatic Georgian form if it carries the same meaning without a heavy analytic phrase.

- Prefer a direct lexical equivalent over a literal construction when the task asks for stylistic correctness.
- Do not treat a familiar analytic phrase as best merely because it is grammatical.
- If the direct equivalent changes the meaning, keep the analytic phrase or rewrite clearly.

## Semantic Precision

Check the exact noun class and referent before choosing a near synonym.

- For people living in a place, distinguish ordinary residents from native or ancestral locals.
- For a collective that denotes people, choose words that modify people as a group. For language, culture, product, or institution, choose the corresponding adjectival form.
- For place names, ethnic labels, institutions, and cultural labels, decide whether the phrase means people, language, territory, product, or organization before selecting the modifier.

## Pronoun Economy

Pronouns are often grammatically valid but stylistically weak or ambiguous.

- If a pronoun phrase leaves the referent unclear, replace the pronoun with the noun or name.
- If a possessive pronoun creates a heavy analytic expression, check whether Georgian has a concise lexical equivalent.
- Keep `თავისი`/`თავიანთი` for the current subject's own possession, and `მისი`/`მათი` for a different third-person owner; if ambiguity remains, rewrite.

## Fast Checks

- If the task says "სტილისტურად სწორი", do not stop after grammar; compare economy, meaning, register, and naturalness.
- If an option sounds elevated, archaic, bureaucratic, or calqued, verify that this register is intended.
- If two near synonyms survive grammar checks, prefer the one whose semantic scope exactly matches the sentence.

## Common Translation Calques and Idiomatic Alternatives

Avoid direct word-for-word translations from English or Russian when they make Georgian sound heavy, bureaucratic, or unnatural. These forms are not all ungrammatical; choose by register and sentence purpose.

| English | Often heavy or over-literal | Prefer when natural |
|---|---|---|
| "It is important to note that..." | "მნიშვნელოვანია აღინიშნოს, რომ..." | `გაითვალისწინეთ:` or state the point directly |
| "In terms of..." | overusing `...თვალსაზრისით` / `...კუთხით` | Restructure, omit, or use a precise relation |
| "At the end of the day" | literal `დღის ბოლოს` when not about time | `საბოლოო ჯამში` / `საბოლოოდ` |
| "When it comes to..." | heavy `როდესაც საქმე ეხება...` | `რაც შეეხება...` or state directly |
| "The fact that..." | overusing `ის ფაქტი, რომ...` | Omit or use a direct noun phrase |

## Digital, Technical, and AI Terminology

When translating modern tech and AI concepts, avoid pretending that one Georgian term is always mandatory. Use the clearest term for the audience, and mark uncertain or emerging terminology as context-dependent rather than "wrong".

| English Term | Prefer / Accept | Avoid as default | Notes |
|---|---|---|---|
| **Reasoning / Thinking Model** | `მოაზროვნე მოდელი`, `მსჯელობის მოდელი` | forcing `აზროვნების მოდელი` everywhere | Models with stronger multi-step reasoning. |
| **AI / Autonomous Agent** | `AI აგენტი`, `ავტონომიური აგენტი` | `AI წარმომადგენელი` unless it is a human role | Software that can plan or execute tasks. |
| **Agentic AI** | `აგენტური ხელოვნური ინტელექტი`; `აგენტური AI` is acceptable in technical/casual prose | treating only one form as mandatory | AI systems that run task-oriented workflows. |
| **Computer Use** | `კომპიუტერის მართვა` for UI-control capabilities | `კომპიუტერის გამოყენება` when the meaning is direct control | Use literal "use" only for ordinary computer use. |
| **Vibe Coding** | `ინტუიციური კოდირება` or explain the English term | `ვიბრაციული კოდირება` | Emerging term; avoid overstandardizing it. |
| **Chain-of-thought (CoT)** | `აზროვნების ჯაჭვი`, `მსჯელობის ჯაჭვი` | `ფიქრის ჯაჭვი` in formal technical prose | Step-by-step reasoning term. |
| **Context Window** | `კონტექსტის ფანჯარა` | overusing `კონტექსტური ფანჯარა` | Maximum context/token volume processed at once. |
| **Open-weight model** | `ღია წონების მოდელი`, `ღია წონებით გამოქვეყნებული მოდელი` | `ღია კოდის მოდელი` unless source code is actually open | Models whose weights are publicly released. |
| **Frontier model** | `მოწინავე მოდელი`, `წამყვანი მოდელი` | `საზღვრისპირა მოდელი` | State-of-the-art capable models. |
| **Tokens / Tokenization** | `ტოკენები`, `ტოკენიზაცია` | `ნიშნები` / `სიმბოლოები` when discussing model tokens | Basic text-processing units. |
| **Deep Reasoning** | `ღრმა მსჯელობა`, `ღრმა აზროვნება` | `ღრმა ფიქრი` in formal technical prose | Multi-step reasoning capability. |
| **Deployment / Deploy** | `განთავსება`, `პროდუქციაში გატანა`, `დანერგვა`, or `დეპლოი` by context | forcing `დანერგვა` for every software deploy | `დანერგვა` fits adoption/implementation; `განთავსება` or `პროდუქციაში გატანა` often fits release operations. |
| **Launch / Release** | `გამოშვება`, `რელიზი`, `გაშვება` by context | treating `გაშვება` as always wrong | Products are often `გამოუშვა`; services, campaigns, and processes may naturally be `გაუშვა`. |

## Borrowed Technical Terms And Product Feature Names

For English technical words that also have an ordinary Georgian meaning, first decide whether the word is being used as a normal concept or as a named software/platform feature.

- If the meaning is ordinary and the Georgian equivalent is clear, prefer Georgian: `უნარი`, `ინსტრუმენტი`, `ფუნქცია`, `შესაძლებლობა`, `დამატება`.
- If the word identifies a specific software feature, plugin type, tool surface, API object, command, file format, package name, or community-recognized product term, keep the Latin-script term so the technical reference remains recognizable.
- Attach Georgian case suffixes to Latin-script technical names with a hyphen: `skill-ი`, `skill-მა`, `skill-ს`, `skill-ის`, `skill-ით`; `plugin-ი`, `plugin-მა`, `plugin-ს`; `tool-ი`, `tool-მა`, `tool-ს`; `API-ს`, `CLI-ით`.
- Use the same pattern for product-feature names that are not meant as ordinary vocabulary: `Codex Skill-ი`, `Browser plugin-ი`, `GitHub connector-ი`, `Supabase tool-ი`.
- On first mention for a mixed audience, add a short Georgian explanation after the technical term: `Codex Skill-ი, ანუ Codex-ისთვის შექმნილი სპეციალური ინსტრუქცია`.
- Keep one naming style inside a short passage. Do not switch between `skill-ი`, `სკილი`, and `უნარი` unless the text explicitly contrasts the product term with the ordinary meaning.
- Avoid quotation marks after the first mention unless the text is explicitly defining or discussing the word itself.

For example, in a message to a technical or Codex-aware reader, prefer `ქართული გრამატიკის ეს skill-ი შევქმენი` or `Georgian Grammar Skill-ი შევქმენი`. For a broader audience, prefer `Codex-ისთვის ქართული გრამატიკის skill-ი შევქმენი` and explain briefly if needed.

## Name Transliteration Cautions

Transliterate names based on common English pronunciation rather than strict spelling, but avoid turning these examples into a closed answer list:

- **Sam Altman** -> prefer `სემ ალტმანი`; avoid `სემ ოლტმენი`.
- **Nick Bostrom** -> prefer `ნიკ ბოსტრომი`; avoid `ნიკ ბოსტრემი`.
- **Demis Hassabis** -> prefer `დემის ჰასაბისი`; avoid `დემის ხასაბისი`.
- **Eliezer Yudkowsky** -> prefer `ელიეზერ იუდკოვსკი`; avoid spelling-driven forms such as `ელაიზერ იუდკაუსკი`.
