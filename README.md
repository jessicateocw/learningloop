# Learning Loop: Main Takeaway

[DEMO](https://jessicateocw.github.io/learningloop)

localhost working, Having issue with webhooks connection.

Learning about stripe integration and document reading.
All code is found and learnt from
(https://stripe.com/docs)

## Accept a payment with Stripe Checkout

This integration shows you how to accept payments with Stripe
[Checkout](https://stripe.com/docs/checkout).

We built [Checkout](https://stripe.com/docs/payments/checkout) to do that
work for you so now you can focus on building the best storefront
experience for your customers.

Once your customer is ready to pay, use Stripe.js to redirect them to the
URL of your Stripe hosted payment page. 🥳

## How to run locally

Recommended approach is to install with the [Stripe CLI](https://stripe.com/docs/stripe-cli#install):

```sh
stripe samples create accept-a-payment
```

Then pick:

```sh
prebuilt-checkout-page
```

This sample includes several different server implementations and several
different client implementations. The servers all implement the same routes and
the clients all work with the same server routes.

Picked server:

- [node](./server/node)

Picked client:

- [html](./client/html)
  "# learingloop"
