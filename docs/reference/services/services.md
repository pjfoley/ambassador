## Services

You may need an API Gateway to enforce policies specific to your organization. Ambassador supports custom policies through external services. The policy logic specific to your organization is implemented in the external service, and Ambassador is configured to send RPC requests to your service.

Currently, Ambassador supports external services for authentication and rate limiting.

* [AuthService](auth-service.md)
* [RateLimitService](rate-limit-service.md)
