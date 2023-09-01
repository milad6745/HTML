## div
از تگ `<div>` به عنوان یک کنتینر جهت گروه‌بندی و قالب‌بندی محتوای وبسایت استفاده می‌شود . با استفاده از این تگ، می‌توانید عناصر مختلفی را داخل یک کانتینر قرار داده و آن‌ها را با استفاده از CSS به طور دلخواه طراحی و سبک‌بندی کنید.

به عنوان مثال، شما می‌توانید از تگ `<div>` برای ایجاد قالب بخش‌های مختلف یک صفحه وب مانند هدر، منو، محتوا اصلی و فوتر استفاده کنید.

مثال:
```html
<div class="header">
  <!-- محتوای هدر -->
</div>

<div class="menu">
  <!-- محتوای منو -->
</div>

<div class="main-content">
  <!-- محتوای اصلی -->
</div>

<div class="footer">
  <!-- محتوای فوتر -->
</div>
```

در این مثال، از تگ `<div>` برای ایجاد بخش‌های مختلف صفحه وب استفاده شده است. سپس با استفاده از کلاس‌ها و CSS می‌توان هر بخش را طراحی و سبک‌بندی کرد.

```html
<!DOCTYPE html>
<html>
<body>

<div style="background-color: blue; color: white;" align="center">header</div>
<div>body</div>
<div>footer</div>

</body>
</html>
```

![image](https://github.com/milad6745/HTML/assets/113288076/343a3b0f-5dd8-461a-bd14-02588ad81cd1)

## span
سه تا قسمت مشخص کردیم
قسمت اول بکگراند را آبی کردیم و نوسته سفید و وسط چیسن و با تگ span نوشته red را قرمز کردیم
قسمت دوم هم بکگراند قرمز و یک لینک دادیم که قسمت click here را لینک دار و آبی کردیم.
```html
<!DOCTYPE html>
<html>
<body>

<div style="background-color: blue; color: white; height: 100px;" align="center">HEADER MY WEBSITE IS <span style="color: red;"> RED </span></div>
<div style=" background-color: red ; height: 100px; color: white;" align="center">for information<span style="color: blue;"><a href="https://example.com">click HERE</a></div>
<div>footer</div>

</body>
</html>
```
![image](https://github.com/milad6745/HTML/assets/113288076/f28b18e0-383d-4c9a-bf32-a68adb0a66b5)

