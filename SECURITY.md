# Security policy

## Supported releases

| Platform | Supported release |
| --- | ---: |
| Windows | 0.4.16 |
| macOS | 0.6.0 |

## Report a security concern

Use the private feedback form at [Team 357 Utility Lab](https://team357.com/utility-lab/) and identify the report as a security concern. Do not include passwords, authentication tokens, private account details, or live usage data in a public GitHub issue.

Include the platform, utility version, operating-system version, the action that triggered the problem, and a concise description of the observed result.

## Package verification

Official release filenames and SHA-256 values are listed in [CHECKSUMS.txt](CHECKSUMS.txt); byte sizes and the same hashes appear on each GitHub release. The Windows build is currently unsigned, and the Mac build is ad-hoc signed rather than Apple notarized. A checksum confirms that a download matches the Team 357 release file; it is not a publisher identity signature.
