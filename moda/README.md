# MODA — Geyim Alış-Veriş Saytı

## 📁 Fayl Strukturu

```
moda/
│
├── index.html              ← Ana səhifə (məhsul siyahısı)
│
├── pages/
│   ├── product.html        ← Məhsul detay səhifəsi       (TODO)
│   ├── cart.html           ← Səbət səhifəsi               (TODO)
│   ├── checkout.html       ← Ödəniş səhifəsi              (TODO)
│   ├── profile.html        ← İstifadəçi profili           (TODO)
│   ├── favorites.html      ← Sevimli məhsullar            (TODO)
│   └── orders.html         ← Sifarişlər tarixi            (TODO)
│
├── css/
│   ├── global.css          ← CSS dəyişənlər, reset, utilitylar (ORTAQ)
│   ├── layout.css          ← Header, Footer, Hero Strip   (ORTAQ)
│   └── components.css      ← Kartlar, düymələr, formlar, modlar (ORTAQ)
│
├── js/
│   ├── auth.js             ← Giriş / Qeydiyyat / Çıxış
│   ├── cart.js             ← Səbət əməliyyatları
│   ├── products.js         ← Məhsul məlumatları və render
│   └── components.js       ← Header, Footer, Toast, Modal (ORTAQ)
│
└── assets/
    ├── images/             ← Lokal şəkillər
    └── icons/              ← SVG ikonalar
```

## 🔗 Hər HTML səhifəsinin başına əlavə ediləcək

```html
<link rel="stylesheet" href="../css/global.css" />
<link rel="stylesheet" href="../css/layout.css" />
<link rel="stylesheet" href="../css/components.css" />
```

```html
<script src="../js/auth.js"></script>
<script src="../js/cart.js"></script>
<script src="../js/products.js"></script>
<script src="../js/components.js"></script>
```

> ⚠️ `index.html` üçün yol `css/` , `pages/` qovluğundakı fayllar üçün `../css/` olmalıdır.

## 🚀 Növbəti Addımlar

- [ ] Firebase Authentication əlavə et
- [ ] Firebase Firestore ilə məhsul verilənləri
- [ ] Məhsul detay səhifəsi
- [ ] Ödəniş sistemi (Stripe və ya yerli)
- [ ] Admin paneli

## 🌐 GitHub Pages

1. Bu qovluğun içindəkiləri `Reynoncode.github.io` repo-suna yüklə
2. Settings → Pages → Deploy from main branch
3. `https://Reynoncode.github.io` ünvanında aktiv olacaq
