# Microsoft UET Conversion API Tag for Google Tag Manager (server-side)

The Microsoft UET Conversion API Tag allows advertisers to send web events from their servers directly to the Conversions API. The tag simplifies dual tracking by triggering both CAPI and pixel hit from a single server-side tag, improving web performance, data governance, and ensuring effective event deduplication.

## Background

The Microsoft UET Conversion API (CAPI) is essential for overcoming the limitations of the UET client-side pixel, which has become less effective due to ad blockers and the decline of third-party cookies. Microsoft recommends using Microsoft UET Conversion API for optimal tracking.

## How does the Addingwell tag work?

This template is a tag that reads the standard event schema sent from the client running on a tagging server. It then converts events to the appropriate schema and sends them through the Conversion API. It also allows sending a response to the browser that triggers a call to the pixel.

The tag supports only GA4 client.

## Implementation

You can follow our [step-by-step instructions](https://docs.addingwell.com/en/microsoft-uet-conversion-api).

## Reporting Bugs/Feedback

Please raise any issues on GitHub or contact us directly at support@addingwell.com.

## Open Source

The Microsoft UET Conversion API Tag for GTM Server-Side is developed and maintained by [Addingwell](https://www.addingwell.com/) under the Apache 2.0 license.