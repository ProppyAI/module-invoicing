# module-invoicing

HARNESS module: Invoice lifecycle — creation, sending, payment tracking, overdue management.

## Entity Contract

- **Produces:** invoice, payment
- **Consumes:** client, job, estimate, line-item

## Tools

- `create-invoice` — Create an invoice from an approved estimate
- `send-invoice` — Send an invoice to the client
- `record-payment` — Record a payment against an invoice

## Validation

```bash
harness module validate .
```
