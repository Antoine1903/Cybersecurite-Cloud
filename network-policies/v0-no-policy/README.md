v0 – No NetworkPolicy

Description:
No NetworkPolicy is applied.
Kubernetes default behavior allows all ingress and egress traffic.

Observed behavior:
- frontend → checkoutservice: allowed
- frontend → redis-cart: allowed (should be denied)
- cartservice → redis-cart: allowed
- cartservice → paymentservice: allowed (should be denied)

Conclusion:
Default Kubernetes networking is too permissive and does not satisfy the security requirements.
