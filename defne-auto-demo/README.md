# Defne Auto — Demo Sitesi

Bu klasör, Defne Auto demo web sitesinin tam kaynak kodunu içerir.

## Vercel'e yükleyip canlı link almak (kod bilmeden, ~10 dakika)

1. https://vercel.com adresine git, "Sign Up" ile ücretsiz hesap aç (GitHub, Google veya e-posta ile).
2. Giriş yaptıktan sonra "Add New..." > "Project" butonuna bas.
3. "Deploy without Git" / "Continue with..." gibi bir seçenek görürsen, bu projeyi ZIP olarak sürükle-bırak ile yükleyebileceğin ekrana gel.
   - Not: Vercel'in arayüzü zaman zaman güncellenebilir. Sürükle-bırak seçeneğini bulamazsan, en kolay yol: bu klasörü bir GitHub deposuna yükleyip (GitHub Desktop ile kod bilmeden de yapılabilir), Vercel'de "Import Git Repository" ile o depoyu seçmek.
4. Yükleme bittiğinde Vercel otomatik olarak projeyi tanır (Vite + React), "Deploy" butonuna basman yeterli.
5. 1-2 dakika içinde sana `defne-auto-demo-xxxx.vercel.app` gibi gerçek bir link verecek. Bu linki doğrudan müşteriye atabilirsin.

## Yerel bilgisayarında önizlemek istersen

Node.js kurulu bir bilgisayarda:

```
npm install
npm run dev
```

Tarayıcıda `http://localhost:5173` adresini aç.

## Önemli not

Bu, görsel/akış demosudur. Veriler tarayıcı belleğinde tutulur (sayfa yenilenince sıfırlanır), gerçek sahibinden API bağlantısı yoktur. Müşteriden onay alındıktan sonra, gerçek veri tabanı ve sahibinden senkronizasyonu eklenerek canlıya alınacaktır.
