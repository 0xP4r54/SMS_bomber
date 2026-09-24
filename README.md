# SMS Bomber — Educational / Authorized Testing

> **Important:** This repository is provided only for educational purposes and authorized security testing.
> Do not use it to send unsolicited messages, spam third-party services, or disrupt systems you do not own
> or have explicit permission to test.

## Overview

This project is a Python-based HTTP request testing project.

It was originally written to demonstrate how automated requests can interact with web APIs and services.
Because automated OTP/SMS requests can affect real third-party systems, use this code only in a controlled
environment or against services for which you have explicit authorization.

## Requirements

- Python 3.8+
- `requests`
- `urllib3`

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Responsible Use

By using this project, you agree to:

- Test only systems you own or are explicitly authorized to test.
- Avoid sending unsolicited SMS or OTP requests.
- Avoid rate-limit bypassing or service disruption.
- Never publish or use private API keys, cookies, tokens, or credentials.
- Respect the terms of service and applicable laws.

## Security Notice

Before publishing this project, review the source code and remove any credentials, authentication tokens,
cookies, API keys, or other secrets. If any real credentials have already been exposed, revoke or rotate
them before publishing the repository.

## License

See `LICENSE` for the copyright and usage terms of this repository.
