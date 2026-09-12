# نواة | Nawah — هبوط الصفحة

صفحة تواصل لشركة نواة، جاهزة للنشر على Vercel.

## البنية
```
nawah-vercel/
├─ index.html        ← الصفحة الرئيسية
├─ vercel.json       ← إعدادات النشر (تخزين مؤقت للصور)
└─ images/           ← الصور
   ├─ images.jpg     ← الصورة الرئيسية
   ├─ nawah-logo.png ← الشعار
   ├─ deco-1.jpg     ← خلفية زخرفية
   ├─ deco-2.jpg     ← خلفية زخرفية
   └─ deco-3.png     ← خلفية زخرفية
```

## طرق النشر على Vercel

### 1) بواجهة Vercel (الأسهل — بدون تثبيت)
1. ارفع الملفات إلى مستودع GitHub (البنية فوق).
2. ادخل على [vercel.com](https://vercel.com) وسجّل الدخول.
3. اضغط **Add New → Project**.
4. اختر المستودع واضغط **Deploy** (Framework Preset: **Other**).
   - لا حاجة لأي Build Command — مجرد ملفات ثابتة.

### 2) بCommand Line (Vercel CLI)
```bash
npm i -g vercel
cd nawah-vercel
vercel        # نشر تجريبي
vercel --prod # نشر نهائي
```

### 3) بسحب الملفات للمتصفح (drag & drop)
- على Dashboard: **Add New → Project → Import** وارفع مجلد `nawah-vercel` كاملاً.

## ملاحظة
جميع مسارات الصور مبدئية بعامة (`images/...`)، لا حاجة لمزيد من الإعداد.
