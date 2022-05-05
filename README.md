# mai-ci-cd

> A GitHub App built with [Probot](https://github.com/probot/probot) that Mac@IBM CI/CD Pipelines

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t mai-ci-cd .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> mai-ci-cd
```

## Contributing

If you have suggestions for how mai-ci-cd could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 Jan Valentik <jvalentik@sk.ibm.com>
