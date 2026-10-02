<div align="center">

<img src=".github/assets/logo.png" alt="QuenchForge" width="420">

**One file. Every tool.**

[![Python](https://img.shields.io/badge/python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Supabase](https://img.shields.io/badge/backend-Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)
[![Status](https://img.shields.io/badge/status-beta-orange)](#)
[![Access](https://img.shields.io/badge/access-private-critical)](#access)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)](LICENSE)
[![Dependencies](https://img.shields.io/badge/dependencies-none-blue)](#requirements)

</div>

---

## Quick start

```bash
python manage.py
```

Sign in once. Everything else loads on demand.

## Requirements

| | |
|---|---|
| Python | 3.9+ |
| Packages | stdlib only |
| Network | HTTPS to `*.supabase.co` |

## Access

| Role | Status |
|---|---|
| Superadmin | Active |
| Admin | Active |
| Public (SSO) | Coming soon |

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow-light.svg" alt="manage.py signs in to Auth, receives a token, then loads Core" width="760">
  </picture>
</p>

No secrets ship in this repository. Updates roll out server-side; `manage.py` never changes.

## Security

Credentials are verified server-side and sessions expire after one hour.
See [SECURITY.md](.github/SECURITY.md) for reporting.

---

<div align="center">
<sub>
<a href="LICENSE">License</a> &nbsp;·&nbsp;
<a href=".github/SECURITY.md">Security</a> &nbsp;·&nbsp;
<a href=".github/CONTRIBUTING.md">Contributing</a>
<br><br>
© 2026 QuenchForge. All rights reserved.
</sub>
</div>
