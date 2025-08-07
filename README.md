Usage: `fnm use && npm ci && npm test`

Actual:

```
Exception during run: Error [ERR_INTERNAL_ASSERTION]: Unexpected status of a module that is imported again after being required. Status = 0
This is caused by either a bug in Node.js or incorrect usage of Node.js internals.
Please open an issue with this stack trace at https://github.com/nodejs/node/issues
```

Expected: A slightly more helpful error message.
