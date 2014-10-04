# Test-server-middleware

To demonstrate the problem, run

```
ember serve
```

The process should exit immediately, but it doesn't, because the addon's `serverMiddleware` hook never gets called.
