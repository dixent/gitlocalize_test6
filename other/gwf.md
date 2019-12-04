project_path: /web/fundamentals/_project.yaml
book_path: /web/fundamentals/_book.yaml
description: Learn who are involved in the Web Payments ecosystem, how they interact each other and how you can get involved.

{# wf_published_on: 2018-09-10 #}
{# wf_updated_on: 2019-02-22 #}
{# wf_blink_components: Blink>Payments #}

# How the payment ecosystem works {: .page-title }

{% include "web/_shared/contributors/agektmr.html" %}
{% include "web/_shared/contributors/dgash.html" %}

Let's see how the new payment ecosystem works with Web Payments.

## The anatomy of Web Payments

_Web Payments_ comprises multiple web standards.

*   **Payment Request API:** The [Payment Request
    API](https://www.w3.org/TR/payment-request/) enables fast and easy checkouts
    through a native browser UI. It provides a consistent checkout flow while
    reducing the need for users to enter their shipping and payment information
    on every checkout. Learn how it works at a high level at [How payment request
    api works](/web/fundamentals/payments/basics/how-payment-request-api-works) or in detail at
    [Deep Dive into the Payment Request
    API](/web/fundamentals/payments/merchant-guide/deep-dive-into-payment-request).
*   **Payment Handler API:** The [Payment Handler
    API](https://w3c.github.io/payment-handler/) opens up the ecosystem to
    payment providers by allowing their web-based payment applications to act as
    payment methods on merchant websites through the standard Payment Request
    API.
*   **Payment Method Identifiers:** The [Payment Method
    Identifiers](https://w3c.github.io/payment-method-id/) defines how strings
    (`basic-card`, `https://google.com/pay`, etc.) can be used to identify a
    payment method. Along with standardized payment method identifiers, it
    allows anyone to define their own payment method with URL-based payment
    method identifiers. Learn more at [Payment method
    basics](/web/fundamentals/payments/basics/payment-method-basics).
*   **Payment Method Manifest:** The [Payment Method
    Manifest](https://w3c.github.io/payment-method-manifest/) defines the
    machine-readable manifest file, known as a payment method manifest,
    describing how a payment method participates in the payment ecosystem, and
    how such files are to be used.