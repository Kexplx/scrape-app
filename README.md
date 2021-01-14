![CI](https://github.com/Kexplx/scrapestar/workflows/CI/badge.svg)

# ⭐ Scrapestar ⭐

HTML scraping made easy. Schedule recurring jobs and fetch their results from a simple REST API.

See the <a href="https://www.youtube.com/watch?v=V1UMi-HkJvI" target="_blank">Demo</a> on YouTube.

## Prerequisites

In order to run the project you'll need <strong>docker</strong> and <strong>docker-compose</strong> installed.

Because of a modern `docker-compose.yml` format, you need a docker-compose version >= 1.6.

### Usage

#### Run the application

```shell
docker-compose up
```

|         | Endpoint                |
| ------------- |-------------|
| UI      | `http://localhost:5005` |
| API      | `http://localhost:3000` |

## Contribute

Please use `npm run format` inside `/ui` or `/api` before pushing to apply our style guidelines and make the linter pass 👍.
