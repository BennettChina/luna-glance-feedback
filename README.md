[English](README.md) | [简体中文](README.zh-CN.md)

# Luna Glance Feedback

This repository is the public feedback and feature request tracker for Luna Glance.

Luna Glance is an unofficial Lunar Arcanum card exchange tool for Genshin Impact players. It lets players anonymously publish, find, and match card exchange requests. The project is not affiliated with miHoYo or HoYoverse.

Website: <https://lunaglance.app/>

## Repository Scope

- Collect reproducible functional defects, UI problems, and usability feedback.
- Collect feature suggestions and improvements that align with the product goals.
- Track confirmed issues, discussion scope, and progress.
- Does not host Luna Glance source code, deployment configuration, or production data.

Development, builds, deployment, and architecture maintenance are handled internally by the project maintainers and are outside the scope of this repository.

## Product Capabilities

- Find card exchange requests by server or region across CN and international servers.
- Anonymously publish the Lunar Arcanum cards and quantities you can offer and need.
- Calculate candidate matches and exact matches within the same server or region.
- Reveal another player's in-game UID only after the server confirms a currently valid match.
- Edit, pause, renew, revoke, or find your own exchange requests using the management credential stored in your browser.
- Report suspected abusive, incorrect, or malicious exchange requests for maintainer review.
- Support Simplified Chinese, Traditional Chinese, English, Japanese, Korean, Russian, German, and French.

## Submitting Feedback

Search existing issues first to make sure the problem or suggestion has not already been reported, then choose the appropriate form:

- [Submit a bug report](https://github.com/BennettChina/luna-glance-feedback/issues/new?template=bug_report.yml)
- [Submit a feature request](https://github.com/BennettChina/luna-glance-feedback/issues/new?template=feature_request.yml)

### Bug Reports Should Include

- The reproducible page, feature, or action.
- Reproduction steps, actual behavior, and expected behavior.
- The time of occurrence, browser, device, operating system, and current language.
- Redacted screenshots or screen recordings when necessary.

### Feature Requests Should Explain

- The user problem you are facing, not only a proposed implementation.
- The expected outcome and typical use cases.
- How the change would affect existing player workflows.
- Known alternatives or tradeoffs.

## Privacy and Security

GitHub issues are public. Before submitting, remove or obscure all sensitive information, including but not limited to:

- Game UIDs, account information, or other personally identifiable information.
- Exchange request management links, management credentials, or browser local storage contents.
- Passkeys, recovery codes, cookies, session tokens, or Turnstile tokens.
- Secrets, tokens, or complete request headers from Cloudflare, GitHub, or other services.
- Undisclosed security vulnerability details or directly exploitable reproduction steps.

If an issue involves a security vulnerability, credential exposure, or privacy risk, do not create a public issue. Contact the maintainers privately using the information on the [maintainer's GitHub profile](https://github.com/BennettChina) and share only the minimum reproduction details necessary.

## Feedback Scope

Appropriate for this repository:

- Problems with publishing, searching, matching, managing, or reporting exchange requests.
- Incorrect card or server/region catalog data.
- Page rendering, responsive layout, keyboard operation, or accessibility problems.
- Translation, copywriting, and cross-language behavior issues.
- Feature or usability suggestions that align with the product boundaries.

Outside the scope of this repository:

- Game accounts, in-game friends, trade disputes, or player integrity issues.
- Issues related to official miHoYo or Genshin Impact services.
- Requests that conflict with the product boundaries, such as enforced buying or selling, escrow, in-site messaging, payments, or cross-region matching.
- Investigation requests that require another player's UID or private communication records.

## Issue Handling

Maintainers confirm and prioritize issues based on reproducibility, impact, product boundaries, and security risk. Creating an issue does not guarantee that it will be implemented or that a fixed completion date will be provided. Confirmed issues will have their status or conclusions added to the discussion.

## Links

- [Visit Luna Glance](https://lunaglance.app/)
- [Issues in This Repository](https://github.com/BennettChina/luna-glance-feedback/issues)
