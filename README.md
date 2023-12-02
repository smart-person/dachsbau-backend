
# Dachsbau Backend

> [!NOTE]
> Forked from [🍫 Cacao Kit Backend](https://github.com/johannschopplich/cacao-kit-backend). All of the features and settings apply here as well.

This website is intended as the backend for the Nuxt 3 frontend. If the URL is called and no `Authentication` header is sent with the requerst, the user will automatically forwarded to the Kirby Panel.

👉 See the [Dachsbau Frontend](https://github.com/johannschopplich/dachsbau-frontend) repository for the whole frontend code!

## Prerequisites

- PHP 8.1+

Kirby is not a free software. You can try it for free on your local machine but in order to run Kirby on a public server you must purchase a [valid license](https://getkirby.com/buy).

## Setup

### Composer

Kirby-related dependencies are managed via [Composer](https://getcomposer.org) and located in the `vendor` directory. To install them, run:

```bash
composer install
```

### Environment Variables

Duplicate the [`.env.development.example`](.env.development.example) as `.env`:

```bash
cp .env.development.example .env
```

Optionally, adapt it's values.

## Usage

See the [Dachsbau Frontend](https://github.com/johannschopplich/dachsbau-frontend) repository.

### Deployment

> [!NOTE]
> See [ploi-deploy.sh](./scripts/ploi-deploy.sh) for exemplary deployment instructions.
>
> Some hosting environments require to uncomment `RewriteBase /` in [`.htaccess`](public/.htaccess) to make site links work.

## License

[MIT](./LICENSE) License © 2022-PRESENT [Johann Schopplich](https://github.com/johannschopplich)
