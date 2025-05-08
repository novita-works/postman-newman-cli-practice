# postman-newman-cli-practice
This is a simple practice for running Postman collections using the CLI tool Newman.

## How to Run

```bash
newman run Newman-Functional-testing.postman_collection.json
```

## CLI Execution Result Example
When running the collection using Newman, you will see an output like this:
┌─────────────────────────┬──────────┬─────────┐
│                         │ executed │ failed  │
├─────────────────────────┼──────────┼─────────┤
│ iterations              │        1 │       0 │
│ requests                │        9 │       0 │
│ test-scripts            │       20 │       0 │
│ prerequest-scripts      │       20 │       0 │
│ assertions              │       19 │       0 │
└─────────────────────────┴──────────┴─────────┘
total run duration: 6s
total data received: 708B (approx)
average response time: 633ms [min: 278ms, max: 2.9s, s.d.: 808ms]
All assertions passed, indicating that the API tests are working as expected.
