# CLAUDE.md — دستور المشروع

## اسم المشروع
Pro Cafe — موقع ثابت (Static Site)

## الهدف
موقع لمقهى Pro Cafe يشمل صفحات: الرئيسية، دعم العملاء، وعروض المنتجات.

## هيكل المشروع

```
hasan/
├── CLAUDE.md              ← دستور المشروع (هذا الملف)
├── .claude/
│   ├── skills/            ← مهارات Claude المخصصة للمشروع
│   └── settings.local.json
├── tools/                 ← سكربتات بايثون ومساعدات
├── workflows/             ← خطوات العمل والأتمتة
├── .env                   ← مفاتيح سرية (لا يُرفع على git)
├── index.html             ← الصفحة الرئيسية
├── pro-cafe.html          ← صفحة المقهى
├── customer-support.html  ← صفحة دعم العملاء
└── customer-support-v2.html
```

## ملاحظات للمساعد (Claude)

- المشروع موقع ثابت (HTML فقط) — لا يوجد build system أو npm
- ملف `.env` يحتوي مفاتيح سرية — لا تُضمّنها في الكود أو الكوميتات
- الاستضافة عبر Vercel (مجلد `.vercel/` موجود)
