<p align="center">
  <img src="georgian-grammar/assets/georgia-flag.png" alt="Georgian Grammar Skill icon" width="84">
</p>

<h1 align="center">Georgian Grammar Skill for Codex</h1>

<p align="center">
  Rule-first Georgian writing, editing, translation, punctuation reasoning, and QA for standard literary Georgian.
</p>

<p align="center">
  Open-source Codex skill | Apache License 2.0 | Contribution-friendly
</p>

An open-source Codex skill designed to help agents write cleaner, more natural, and more grammatically correct Georgian. The skill follows a rule-first workflow, keeps the hot path lean, and routes deeper morphology, syntax, punctuation, and lexical-boundary questions into focused reference files.

This project is open to ongoing improvement. If you spot a mistake, refine a rule, or want to add clearer examples, open an issue or submit a pull request.

Repository name: `georgian-grammar-codex-skill`

## ქართულად

**Georgian Grammar Skill for Codex** არის Codex-ისთვის შექმნილი ქართული გრამატიკის სკილი, რომელიც ეხმარება აგენტს გამართული, ბუნებრივი და ნორმების შესაბამისი ქართული ტექსტის წერაში, რედაქტირებაში, თარგმნაში, პუნქტუაციის შემოწმებასა და გრამატიკულ ანალიზში.

ეს სკილი განსაკუთრებით გამოსადეგია, როცა საჭიროა:

- ქართული ტექსტის გამართვა
- ქართული გრამატიკის შემოწმება
- პუნქტუაციის სწორად დასმა
- ბუნებრივი და თანამედროვე ქართული ფორმულირებების შერჩევა
- ინგლისურიდან ქართულად აზრობრივად სწორი თარგმნა

## Highlights

- Rule-first Georgian QA for writing, editing, and translation
- Progressive-disclosure structure: `SKILL.md` stays lean, deeper material lives in `references/`
- Coverage for morphology, syntax, agreement, punctuation, compounds, particles, adverbs, and lexical boundaries
- Explicit contribution flow with pull request guidance
- Public package prepared for GitHub publication

## Preview

<p align="center">
  <img src="assets/georgian-grammar-skill-preview.png" alt="Georgian Grammar Skill preview" width="720">
</p>

## Repository Layout

```text
georgian-grammar-codex-skill/
|- assets/
|  `- georgian-grammar-skill-preview.png
|- georgian-grammar/
|  |- SKILL.md
|  |- agents/
|  |  `- openai.yaml
|  |- assets/
|  |  |- georgia-flag.svg
|  |  `- georgia-flag.png
|  `- references/
|     |- normative-decision-protocol.md
|     |- grammar-guardrails.md
|     |- verb-morphology.md
|     |- morphology-deep-dive.md
|     |- verb-paradigm-boundary.md
|     |- compound-writing-rules.md
|     |- normative-orthography.md
|     |- syntax-deep-dive.md
|     `- source-map.md
|- .github/
|  `- pull_request_template.md
|- CONTRIBUTING.md
|- LICENSE
|- NOTICE
`- .gitignore
```

## Install In Codex

Only the `georgian-grammar/` folder should be installed into Codex. Do not copy the entire repository into your skills directory.

If you cloned or unzipped this repository, run the following commands from the repository root.
These commands replace any existing local copy so stale files and accidental folder nesting do not survive an update.

### Windows PowerShell

```powershell
$SkillDir = "$HOME\.codex\skills\georgian-grammar"

Remove-Item -Recurse -Force $SkillDir -ErrorAction SilentlyContinue
New-Item -ItemType Directory -Force "$HOME\.codex\skills" | Out-Null
Copy-Item -Recurse -Force .\georgian-grammar $SkillDir
```

### macOS / Linux

```bash
rm -rf ~/.codex/skills/georgian-grammar
mkdir -p ~/.codex/skills
cp -R ./georgian-grammar ~/.codex/skills/georgian-grammar
```

### Fresh Clone Example

```bash
git clone https://github.com/levan-ildani/georgian-grammar-codex-skill.git
cd georgian-grammar-codex-skill
rm -rf ~/.codex/skills/georgian-grammar
mkdir -p ~/.codex/skills
cp -R ./georgian-grammar ~/.codex/skills/georgian-grammar
```

After copying, restart or reload Codex if the old skill version is still cached.

## Use In Chat

After installation, you can ask Codex to use the skill directly in the chat.

In Codex composer, you can mention the skill directly:

```text
@georgian-grammar
```

You can also use an explicit prompt form:

```text
Use $georgian-grammar for this task.
```

Examples:

```text
@georgian-grammar rewrite this text in correct, natural Georgian.
```

```text
Use $georgian-grammar when checking grammar and punctuation in the answer.
```

Depending on the Codex UI surface, either `@georgian-grammar` or `$georgian-grammar` may be the clearer way to invoke the skill. Do not use machine-specific local paths in normal chat usage.

## What This Repository Does Not Include

- Local backups
- Test reports
- Source PDFs and other maintenance-only research files
- Personal machine-specific setup files beyond the documented install path

This repository contains the public skill package itself, not the broader local workspace used while building it.

## Contributing

Contributions are welcome through GitHub pull requests.

See [CONTRIBUTING.md](CONTRIBUTING.md) for:

- what kinds of changes are useful
- how to describe a rule update clearly
- what to include in a pull request
- how to keep the skill rule-first and low-churn

The repository also includes a ready-to-use PR template at [.github/pull_request_template.md](.github/pull_request_template.md).

## Author

Created and maintained by **Levan Ildani**.

This project is focused on helping Codex produce clearer, more natural, and more grammatically correct Georgian text.

Contact: `levan.ildani@gmail.com`  
Website: [ildani.dev](https://ildani.dev)

## License

This project is licensed under the Apache License 2.0. See [LICENSE](LICENSE).
