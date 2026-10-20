# checkout read-only example

Filled names in this slice:

- Namespace `checkout`
- ServiceAccount `checkout/checkout-read` with automount false
- Role `checkout-read` with get, list, and watch
- RoleBinding `checkout-read` to that Role inside `checkout`

The deploy account `checkout-deploy` is in the full pack. Check upstream docs before you apply these files.
