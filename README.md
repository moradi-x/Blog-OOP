# وبلاگ مرادیکس | Moradix Blog

یک وبلاگ پویا و ساده که با استفاده از **PHP OOP** و **JSON** به‌عنوان سیستم ذخیره‌سازی اطلاعات توسعه داده شده است.

این پروژه یک سیستم وبلاگ کاملاً پویاست که بدون استفاده از پایگاه‌داده‌های سنتی مانند MySQL پیاده‌سازی شده است.

تمام اطلاعات، از جمله کاربران، مطالب و تنظیمات، داخل فایل‌های **JSON** ذخیره می‌شوند.

این پروژه با رویکرد **برنامه‌نویسی شیءگرا (OOP)** توسعه داده شده و امکاناتی مانند پنل مدیریت، سیستم اعتبارسنجی، احراز هویت، جستجو، دسته‌بندی مطالب و موارد دیگر را ارائه می‌دهد.

---

## 📸 تصاویر پروژه

### 👨‍💻 بخش کاربران

<table>
  <tr>
    <td align="center">
      <img src="assets/images/homePage.png" width="400"><br>
      <strong>صفحه اصلی</strong>
    </td>
    <td align="center">
      <img src="assets/images/singlePage.png" width="400"><br>
      <strong>صفحه مطلب</strong>
    </td>
  </tr>
</table>

### 🔐 پنل مدیریت

<table>
  <tr>
    <td align="center">
      <img src="assets/images/loginPage.png" width="400"><br>
      <strong>صفحه ورود</strong>
    </td>
    <td align="center">
      <img src="assets/images/adminPage.png" width="400"><br>
      <strong>داشبورد مدیریت</strong>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="assets/images/adminCreatePage.png" width="400"><br>
      <strong>ایجاد مطلب جدید</strong>
    </td>
    <td align="center">
      <img src="assets/images/adminEditPage.png" width="400"><br>
      <strong>ویرایش مطلب</strong>
    </td>
  </tr>
</table>

---

## 🚀 امکانات پروژه

### 🧑‍💻 بخش کاربران

- مشاهده تمام مطالب منتشرشده
- فیلتر مطالب بر اساس دسته‌بندی‌های علمی، فناوری، پژوهش و طراحی
- جستجو بر اساس عنوان و محتوای مطالب
- نمایش مطالب برتر بر اساس تعداد بازدید
- نمایش آخرین مطالب بر اساس تاریخ انتشار
- صفحه اختصاصی هر مطلب شامل تصویر، محتوا، تاریخ انتشار و تعداد بازدید

---

### 🔐 پنل مدیریت

- سیستم ورود امن مدیر
- نمایش فهرست مطالب شامل شناسه، عنوان، تعداد بازدید، تاریخ و عملیات
- ایجاد مطلب جدید با عنوان، دسته‌بندی، محتوا و تصویر
- ویرایش و حذف مطالب
- نمایش نام مدیر در سربرگ پنل
- امکان خروج از حساب کاربری

---

## 🧱 فناوری‌های استفاده‌شده

- **PHP 8+**
- ساختار برنامه‌نویسی شیءگرا (OOP)
- بارگذاری خودکار کلاس‌ها با Composer Autoload
- ذخیره‌سازی اطلاعات با استفاده از فایل‌های JSON
- HTML و CSS خالص
- بدون استفاده از JavaScript
- بدون استفاده از معماری MVC
- سیستم قالب‌بندی اختصاصی (Custom Template System)

---

## 📂 ساختار پوشه‌های پروژه

```text
├── assets
│   ├── css
│   └── images
├── database
├── src
│   ├── Classes
│   ├── Entities
│   ├── Exceptions
│   ├── Models
│   └── Templates
├── vendor
├── composer.json
└── index.php
```

---


