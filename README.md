# Encore Crash - TypeScript Backend Framework & Toolset

- <https://www.youtube.com/watch?v=tL01EzN2-xA>

* 9x Faster APIs than Express.js and 2x faster than Fastify
* Built-in type validation for security and robustness.
  - Automatic request validation.
* Integrate your infrastructure as type-safe objects in application code.
  - Enore.ts builds your application as a Docker image and you just supply the runtime configuration when deploying.
  * web url: <https://app.encore.dev/encore-url-shortener-5fmi>

- Install Encore

```bash
brew install encoredev/tap/encore
```

- Clone Hello World example

```bash
encore app create --example=ts/hello-world
```

- Run locally

```bash
encore run
```

```bash
 encore db shell url

 SELECT * FROM url;
```

```bash
git push encore
```

```bash
curl -X POST https://staging-encore-url-shortener-5fmi.encr.app/url -d '{"url": "https://twitter.com/traversymedia"}' -H 'Content-type: application/json'

curl https://staging-encore-url-shortener-5fmi.encr.app/url/7_NSjgbd
```
