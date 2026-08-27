# pagebrew

My tiny static site generator, ~100 lines of Python

Side project, maintained when I have time.

## Highlights

- Markdown posts with fenced code and tables
- Single template, plain str.format, no Jinja
- RSS feed generation
- Index page with post list by date

## Getting started

```bash
pip install -r requirements.txt
```

## How to use

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── build.py
└── requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
