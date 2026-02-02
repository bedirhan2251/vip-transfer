# Deploy (VIP Transfer)

## Hızlı kullanım
Bu proje **frontend (React)** + **backend** içerir.

### 1) Backend URL ayarı (kolay kurulum)
- Backend ve frontend **aynı domain** altında çalışacaksa ekstra ayar gerekmez (frontend `/api` kullanır).
- Backend farklı bir yerdeyse `frontend/.env` içine şunu ekleyin:
  `REACT_APP_BACKEND_URL=https://api.domaininiz.com`

### 2) Sitemap domain
`frontend/public/sitemap.xml` içinde `https://REPLACE_WITH_DOMAIN/` kısmını kendi domaininizle değiştirin.

## Build
Frontend:
- `cd frontend`
- `npm install`
- `npm run build`

Backend:
- `cd backend`
- `npm install`
- `npm start` (veya repo içindeki mevcut komut)

