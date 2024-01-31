# Testcontainers

A beautiful start to my CI/CD journey?

Read More: <https://github.com/flolu/node-integration-testing/blob/master/index.test.ts>

- **Testcontainers** is a lightweight Node module for bootstrapping **integration tests** with (mostly) **databases and message brokers** wrapped in **Docker** containers.
- You can also use **GenericContainers** to define and start any container you want.
- Before running tests, the right containers must be setup in a specific desired state. **One test might interefere with another** after execution.
- Now your teammates can clone the project and run tests without installing Postgres on their computers
- More Modules: <https://testcontainers.com/modules/?language=nodejs>

## Getting Started

```sh
pnpm init
pnpm install pg --save
pnpm install jest @testcontainers/postgresql --save-dev

pnpm test
```
