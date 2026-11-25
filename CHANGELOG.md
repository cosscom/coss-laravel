# Changelog

## 0.1.1

- Package metadata links the public source mirror, cosscom/coss-laravel, instead of the monorepo,
  which is now private. No code changes.

## 0.1.0

- Initial release: the `coss` mail transport for Laravel 12 and 13. Mailables and notifications
  send through `POST /v1/emails` with retries and an idempotency key; `tag()` becomes the
  category and `metadata()` the tags; `coss()` (`SendsWithCoss`) and `CossOptions::apply()` set
  coss.com's own fields; the sent message's id is the coss.com email id.
