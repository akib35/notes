---
layout: default
---

<link rel="icon" type="image/png" href="{{ '/favicon.png' | relative_url }}">

## 2026

* [Playwright Startup Guide](./content/2026/playwright-setup/)
* [GitHub CLI Guide](./content/2026/github-cli-guide/)

<style>
  /* Hide site footer */
  .site-footer { display: none; }

  /* Hide top navigation menu completely (removes '2026') */
  .site-nav { display: none; }

  /* Insert logo image before site title text */
  .site-title::before {
    content: "";
    display: inline-block;
    width: 24px;
    height: 24px;
    margin-right: 8px;
    vertical-align: sub;
    background-image: url('{{ "/favicon.png" | relative_url }}');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
  }
</style>
