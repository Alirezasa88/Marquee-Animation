# 🌀 Marquee Animation - Infinite Brand Slider

این پروژه یک اسلایدر برند افقی (Marquee Style) با استفاده از **HTML** و **CSS** است که آیتم‌ها (مانند لوگوی برندها) را به‌صورت پیوسته و بی‌وقفه از راست به چپ اسکرول می‌دهد.

## ✨ ویژگی‌ها

- اسکرول افقی بی‌نهایت (infinite loop)
- انیمیشن روان فقط با CSS
- توقف انیمیشن هنگام هاور (pause on hover)
- بازگشت رنگ تصاویر از خاکستری به رنگی در هاور
- طراحی ریسپانسیو برای نمایش در اندازه‌های مختلف

## 📷 پیش‌نمایش

![demo](preview.png)

## 💻 ساختار فایل‌ها

```bash
.
├── index.html         # ساختار HTML اسلایدر
├── style.css          # استایل‌ها و انیمیشن‌ها
└── README.md          # توضیحات پروژه
```

## 🚀 روش استفاده

1. این پروژه را دانلود یا کلون کنید:

```bash
git clone https://github.com/your-username/marquee-animation.git
```

2. فایل `index.html` را در مرورگر خود باز کنید.

3. برای تغییر برندها، تصاویر خود را درون `brand-item` قرار دهید:

```html
<div class="brand-item">
  <img src="your-logo.png" alt="Brand Name">
</div>
```

## 🎨 تنظیمات قابل تغییر

- سرعت انیمیشن: در فایل CSS مقدار `animation-duration` را تغییر دهید:

```css
animation: scroll 20s linear infinite; /* سرعت حرکت */
```

- اندازه آیتم‌ها: در کلاس `.brand-item` قابل تغییر است.

- فیلتر رنگی تصاویر:

```css
.brand-item img {
  filter: grayscale(100%);
}
.brand-item:hover img {
  filter: grayscale(0%);
}
```

## 📱 طراحی واکنش‌گرا

پروژه با استفاده از Flexbox طراحی شده و می‌تواند به‌راحتی با Media Queryها برای موبایل نیز بهینه شود.

## 📜 لایسنس

این پروژه رایگان و Open Source است. می‌توانید آن را کپی، ویرایش و استفاده تجاری کنید بدون نیاز به کسب اجازه.
