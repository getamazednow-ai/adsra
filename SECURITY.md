# Security and sensitive reporting

ADSRA is a published framework, not running software, so "security" here means the integrity of
what is published and the safety of what people post. Some things must **not** be raised as a
public issue. Report them privately instead.

## Report these privately

- **Exposed credentials** — a password, key, token or secret anywhere in this repository, its
  issues or its history.
- **Accidental disclosure** — client information, personal data or confidential workload details
  posted in an issue or comment, by you or by someone else.
- **Suspected tampering** — a file that looks altered from what was released, or activity on the
  repository that looks unauthorised.
- **A checksum mismatch** — a file whose SHA-256 does not match the value listed for it in
  `RELEASE.json`.
- **A tag that does not match its release** — a `v*` tag whose content differs from the release
  it names.

Disagreements with the framework's content — including errors in a control, mapping or citation —
are not security issues. Raise those through the issue forms; see [CONTRIBUTING.md](CONTRIBUTING.md).

## How to report

Use either channel:

1. **GitHub private vulnerability reporting** — on this repository, open the **Security** tab and
   choose **Report a vulnerability**. Only the maintainers can see the report.
2. **Email** — [contact@getamazednow.ai](mailto:contact@getamazednow.ai).

Please do not open a public issue, and do not repeat the sensitive material in a public comment.
If you posted something by mistake, report it here; do not try to work around it by posting again.

Include what you found, where (file, issue number or tag), and — for a checksum or tag report —
the value you expected and the value you got.

## What happens next

- **Acknowledgement within 10 business days** of your report.
- The report is assessed and handled privately. How long a fix or clean-up takes depends on what
  is found, so no resolution date is promised; you are kept informed of the outcome.
- Credit is given if you want it, once the matter is closed.

## Releases are immutable

`v*` release tags are never moved or rewritten. If a released file needs correcting, the
correction ships in a **new release under a new tag**, and the earlier tag stays as it was. Each
release's `RELEASE.json` lists every file with its SHA-256, so you can check what you downloaded
against it.

## Conduct

Behaviour in this repository is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).
