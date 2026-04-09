# aretos.id

Website company profile berbasis `Astro + Tailwind CSS`, dioptimalkan untuk tema putih profesional dan deploy ke Cloudflare Pages.

## Development

```bash
npm install
npm run dev
```

Buka `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```

Output production berada di folder `dist/`.

## Deploy ke Cloudflare Pages

1. Push repo ini ke GitHub/GitLab.
2. Di Cloudflare Dashboard, buka `Workers & Pages` lalu pilih `Create application`.
3. Pilih tab `Pages`, lalu `Connect to Git`.
4. Pilih repository `aretos.id`.
5. Set build config:
   - Build command: `npm run build`
   - Build output directory: `dist`
6. Klik `Save and Deploy`.
7. Setelah deploy sukses, hubungkan custom domain `aretos.id` di menu `Custom domains`.

## Struktur halaman

- `/` Home (landing-style)
- `/services`
- `/portfolio`
- `/about`
- `/contact`
- `/legal`
