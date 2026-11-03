# Royal Mail Tracking API & Webhooks

Use Track123 to track Royal Mail shipments through one unified shipment tracking API.

Track123 lets your application register Royal Mail tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- Royal Mail carrier code: `royal-mail`

- [Track Royal Mail packages on Track123](https://www.track123.com/carriers/royal-mail)

- [Royal Mail API integration page](https://www.track123.com/carriers/royal-mail/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track Royal Mail shipments with Track123. It is not official Royal Mail API documentation.

## Royal Mail tracking API integration

When your application already knows that a shipment is handled by Royal Mail, set `courierCode` to `royal-mail` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [Royal Mail tracking webhook](webhook.md)
- [Royal Mail tracking statuses](tracking-status.md)
- [Royal Mail API errors and rate limits](errors-and-rate-limits.md)

## Royal Mail tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track Royal Mail packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [Royal Mail tracking on Track123](https://www.track123.com/carriers/royal-mail).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by Royal Mail unless explicitly stated.
