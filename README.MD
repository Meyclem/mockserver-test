# MockServer test app

## Usage

### Installation

```bash
asdf install
yarn install
```

### Mock server

To start the mock server, use:

```bash
yarn start:mockserver
```

It will be available on http://localhost:4010

### Openapi client

There's already a generated openapi client, located in `/connect-profile-client` but you can generate a new one if needed with:

```bash
yarn generate-connect-profile-client
```

## Examples

You can check the test suite in [`./test/mock-server.test.ts`](./test/mock-server.test.ts).

You can also run it:

```bash
yarn test
```
> Note that you need to have the mock server running to launch tests.
