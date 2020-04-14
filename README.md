# otp-authenticator-webapp

## Attribution

This project was originally forked from https://github.com/qoomon/otp-authenticator-webapp

## How to use:

A _Google Authenticator_ like offline webapp.

## ☂️ No External Services are used, local JavaScript execution only ☂️

### Features

- generate totp codes
- show remaining valid seconds for totp code
- generate QR-code with OTPAuth URL
  - click on QR-code to copy OTPAuth URL
- parse OTPAuth URLs in the `secret` input field
  - e.g. `otpauth://totp/john.doe?secret=N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G&issuer=example.org`
- parse OTP Secrets within the query param of the URL for bookmarking
