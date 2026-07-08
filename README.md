# TTL BioTech Image CDN

Generated: 2026-07-08 21:06:26 Asia/Taipei

## Structure

- `product-images/products/`：商品主圖
- `product-images/gifts/`：贈品圖片
- `product-images/extras/`：ZIP 內未被目前產品表引用的備援圖片

## Front-end setting

```js
const IMG_BASE = "https://<your-cloudflare-pages-project>.pages.dev/product-images/";
```

The product sheet `Photos url` column should use the relative file path, for example:

```txt
products/341371-12-x4-ume-plum-black-malt-drink-6pack.jpg
```

## Stats

- Product sheet references: 95
- Extra/unreferenced assets: 24
- Unique deployed files: 113
- Original ZIP image total: 57.37 MB
- Optimized output total: 35.70 MB
