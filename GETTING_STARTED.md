# Using the Community Specification License for your Specification Development Project

This repository is a **project template** for FINOS Standards projects. Working files already live in GitHub-conventional places at the repository root (`GOVERNANCE.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SCOPE.md`, `NOTICES.md`, `PARTICIPANTS.md`). The Contributor License Agreement and specification drafting template stay in [`governance-documents/`](governance-documents/). The numbered Community Specification 1.0 document set belongs upstream at the [Community Specification](https://github.com/CommunitySpecification/1.0) site.

Do not modify the legal text of the Community Specification License or the Contributor License Agreement.

## 1. Create your repository

Clone this blueprint (or use it as a GitHub template) into your new repository.

## 2. Fill in the required information

- **`SCOPE.md`.** Complete the scope of your Working Group. This sets the outer bounds of patent coverage. Drafting guidance is in that file.
- **`NOTICES.md`.** Add the contact(s) for code of conduct issues. Default contact is legal@linuxfoundation.org.
- **`MAINTAINERS.md`.** List the Working Group maintainers.
- **`PARTICIPANTS.md`.** Replace `{standard-name}` / `{standard-slug}` placeholders. Leave the participants list ready for enrollment pull requests.
- **`README.md`.** Replace this blueprint README with [`README.template.md`](README.template.md), then fill in `{standard-name}` and `{standard-slug}`.
- **`.github/` templates.** Replace `{standard-name}` / `{standard-slug}` in issue and pull request templates.
- **`LICENSE.spdx`.** Replace `{name of copyright owner}`, `{standard-name}`, and `{standard-slug}`. Keep `PackageLicenseDeclared` as `Community-Spec-1.0 AND Apache-2.0`.

The default source-code license for FINOS projects is Apache-2.0 and can only be changed with FINOS Governing Board approval. Do not rewrite the texts in `LICENSES/`.

| File | Purpose |
| --- | --- |
| `LICENSE` | Short dual-license notice pointing at both copies under `LICENSES/` |
| `LICENSES/SPECIFICATION-LICENSE` | Full Community Specification License 1.0 |
| `LICENSES/SOURCE-CODE-LICENSE` | Full Apache License 2.0 |
| `LICENSE.spdx` | SPDX document declaring `Community-Spec-1.0 AND Apache-2.0` |

After setup, delete this `GETTING_STARTED.md` file and `README.template.md`. They are template scaffolding, not Working Group deliverables.