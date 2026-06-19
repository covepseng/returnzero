# ReturnZero

Source code for [return-zero.dev](https://return-zero.dev) — a blog dedicated to exploitability analysis and product security research.

Every advisory rates vulnerabilities as CRITICAL. Few people verify whether the real-world impact matches the rating. This blog documents that verification process: real containers, real source code references, honest verdicts.

**Beyond PoCs. Real impact.**

## Stack

Built with [Hugo](https://gohugo.io), deployed to [GitHub Pages](https://pages.github.com) via GitHub Actions on every push to `main`.

```
returnzero/
├── content/posts/       # Articles
├── layouts/              # Page templates
├── static/                # CSS, images, CNAME
└── .github/workflows/    # CI/CD — build + deploy
```

## Local development

```bash
hugo server
# → http://localhost:1313
```

```bash
hugo --minify
# build verification before pushing
```

## Related

PoC repositories for each CVE analysed live separately, e.g. [cve-2026-43512-poc](https://github.com/covepseng/cve-2026-43512-poc), [cve-2026-43515-poc](https://github.com/covepseng/cve-2026-43515-poc).