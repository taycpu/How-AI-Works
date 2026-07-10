# How AI Works

Yapay zekâyla daha iyi çalışmak üzerine interaktif sunum: **Prompt · Context · Harness**.

19 slayt, tamamı tek HTML dosyası (`index.html`), bağımlılık yok. Ok tuşları veya kaydırma ile gezinilir. İçinde canlı demolar var: token bölme, tek nöron (bias/aktivasyon), backpropagation eğitim döngüsü, attention görselleştirmesi, prompt kurucu, context rot.

## Deploy (Cloudflare Workers)

```bash
npx wrangler deploy
```

`wrangler.jsonc` statik asset olarak kök dizini servis edecek şekilde ayarlı.
