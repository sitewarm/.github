<h1 align="center">See which pages your CDN serves from cache after a deploy.</h1>

<p align="center">
  <a href="https://sitewarm.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://sitewarm.dev/brand/sitewarm-lockup-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://sitewarm.dev/brand/sitewarm-lockup-light.svg">
      <img src="https://sitewarm.dev/brand/sitewarm-lockup-light.svg" alt="sitewarm" width="320">
    </picture>
  </a>
</p>

<p align="center">
  sitewarm requests the pages of your sitemap after a deploy or purge and reports the cache state your CDN returned for each URL.<br>
  When a CDN exposes no cache status, it reports <code>unknown</code> instead of guessing.
</p>

<p align="center">
  <a href="https://github.com/sitewarm/sitewarm/releases/latest">Get sitewarm</a> ·
  <a href="https://github.com/sitewarm/sitewarm/issues/new/choose">Report a bug</a> ·
  <a href="https://github.com/sitewarm/sitewarm/blob/master/CONTRIBUTING.md">Contribute</a> ·
  <a href="https://sitewarm.dev">sitewarm.dev</a>
</p>

---

### What is open source here

The sitewarm command-line tool is open source under the Apache License 2.0, in
[sitewarm/sitewarm](https://github.com/sitewarm/sitewarm). The hosted app and API are proprietary and live
outside this organization. See [what is open source](https://sitewarm.dev/open-source).

### What it measures

- The cache state your CDN returns for each URL, read from its response headers.
- A HIT is confirmed by a second pass, not guessed from timings.
- The vantage point each measurement was taken from. It reports what it measured and promises no search ranking or indexing result.

### Contributing

Bug reports, documentation fixes and code are welcome. Read the
[contributing guide](https://github.com/sitewarm/sitewarm/blob/master/CONTRIBUTING.md) first, and
follow the [code of conduct](https://github.com/sitewarm/sitewarm/blob/master/CODE_OF_CONDUCT.md) when you take part in
issues and pull requests.

### Security

Report vulnerabilities privately, as described in the
[security policy](https://github.com/sitewarm/sitewarm/blob/master/SECURITY.md). Please do not open a public issue for them.

### Follow along

[sitewarm.dev](https://sitewarm.dev) · [X @sitewarm_dev](https://x.com/sitewarm_dev)
