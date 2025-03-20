# GibbonLMS File Write to RCE
Arbitrary file write in Gibbon LMS can leverage to RCE in versions < 25.0.01, this is a proof of concept of the article created by Herolabs detailed here https://herolab.usd.de/security-advisories/usd-2023-0025/

## Usage

```
python3 CVE-2023-45878.py url command
```
## Example
```
python3 CVE-2023-45878 http://example.com whoami
```
## Disclamer
For educationals purposes only
