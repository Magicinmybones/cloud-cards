# cloud-cards

Live site: [https://cloud-cards.spaceedu-planet-earth.workers.dev](https://cloud-cards.spaceedu-planet-earth.workers.dev)

Standalone static prototype from `cloud-cards(3).html`.

The deployable site is in `site/`. Embedded images and fonts were extracted to `site/assets/`.

The opening sequence runs once on page load, keeps the backdrop and card artwork still, skips itself for reduced-motion users, and clears its animation styles after 2.3 seconds.

## Deploy

```sh
npx wrangler deploy
```

## Extracted assets

- [`assets/fonts/font-1.woff2`](https://cloud-cards.spaceedu-planet-earth.workers.dev/assets/fonts/font-1.woff2)
- [`assets/fonts/font-2.woff2`](https://cloud-cards.spaceedu-planet-earth.workers.dev/assets/fonts/font-2.woff2)
- [`assets/images/image-1.png`](https://cloud-cards.spaceedu-planet-earth.workers.dev/assets/images/image-1.png)
