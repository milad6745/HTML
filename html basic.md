# HTML

تگ html :  تگ اصلی که ساختار کلی صفحه HTML را تعریف می‌کند.
  
تگ head : در این تگ، معلومات مرتبط با سند (مانند عنوان صفحه) قرار می‌گیرد. این اطلاعات به صورت مستقیم در صفحه نمایش داده نمی‌شوند.

تگ body : در این تگ، محتوای اصلی صفحه (مثل متن، تصاویر، و ...) قرار می‌گیرد

تگ title: این تگ عنوان (Title) صفحه را تعیین می‌کند که در نوار عنوان مرورگر نمایش داده می‌شود.
 
تگ p : ایجاد یک پاراگراف

```html
<html>
<head>
    <title> HTML Page </title>
</head>
<body>
    <h1>Hello World!!</h1>
    <p> A Simple Paragrapgh</p>
</body>
</html>
```
![image](https://github.com/milad6745/HTML/assets/113288076/88499dbd-d759-4164-9b99-698646cdcc69)

---


## br
بطور کلی، تگbr برای ایجاد یک شکستن خط (line break) در محتوای متنی یا در موارد دیگر مانند آدرس‌ها یا تاریخ‌ها استفاده می‌شود. در مثال زیر، می‌توانید نحوه استفاده از تگ <br> را ببینید:
```html
<html>
<head>
    <title>Line Break Example</title>
</head>
<body>
    <p>This is a paragraph.<br>It has a line break in the middle.</p>
</body>
</html>
```
![image](https://github.com/milad6745/HTML/assets/113288076/1d83451b-8793-4b95-8f06-d26a3298f6d3)


## b بولد کردن متن
```html
<html>
<head>
    <title>Line Break Example</title>
</head>
<body>
    <b>This is a paragraph It has a line break in the middle.</b>
</body>
</html>
```

## other tag
```html
<html>
<head>
    <title>Page HTML</title>
</head>
<body>
    <b>This is bold</b>
    <big>
        this is big
    </big>
    <i>
        this is italic
    </i>
    <small>
        this is small
    </small>
    <strong>
        this is strong
    </strong>
    
</body>
</html>
```
![image](https://github.com/milad6745/HTML/assets/113288076/0581fd32-95b0-4914-87ef-fe3443e03ef1)

## sub

حالت "sub" در HTML یک تگ است که برای نمایش متن به عنوان زیرنویس (subscript) در متن استفاده می‌شود. این تگ معمولاً برای نمایش شماره‌های شیمیایی، فرمول‌های ریاضی، نمایه‌ها و موارد مشابه استفاده می‌شود. در زیر یک مثال از استفاده از تگ "sub" در HTML آمده است:

```html
<p>در فرمول شیمیایی H<sub>2</sub>O، شماره‌ها به عنوان زیرنویس نشان داده می‌شوند.</p>
```
![image](https://github.com/milad6745/HTML/assets/113288076/660ab85e-b36f-4957-9ba5-e36d1cde0338)


## sup
حالت "sup" در HTML نیز یک تگ است که برای نمایش متن به عنوان بالانویس (superscript) در متن استفاده می‌شود. این تگ نیز معمولاً برای نمایش توان‌ها، بالانویس‌ها، اعداد بالانویس و موارد مشابه استفاده می‌شود. در زیر یک مثال از استفاده از تگ "sup" در HTML آمده است:

```html
<p>سرعت نور در خلاء تقریباً برابر با 3x10<sup>8</sup> متر بر ثانیه است.</p>
```
![image](https://github.com/milad6745/HTML/assets/113288076/660aec90-b028-4c17-ab85-2daa25829193)


## ins
تگ `<ins>` در HTML برای نشان دادن متنی که به تازگی درج شده است (اضافه شده)، استفاده می‌شود. این تگ معمولاً برای نمایش تغییرات و ویرایش‌های جدید در متن استفاده می‌شود. در زیر یک مثال از استفاده از تگ `<ins>` آمده است:

```html
<p>مقاله اصلی در <ins>تاریخ ۲۰ مرداد ۱۴۰۲</ins> منتشر شد.</p>
```
زیرش یه خط میکشه


## Header Tag
```html
<h1>عنوان سطح 1</h1>
<h2>عنوان سطح 2</h2>
<h3>عنوان سطح 3</h3>
<h4>عنوان سطح 4</h4>
<h5>عنوان سطح 5</h5>
<h6>عنوان سطح 6</h6>
```
![image](https://github.com/milad6745/HTML/assets/113288076/c1dc0aa9-5c05-4691-b7da-ab8ce7295fab)

## hr tag
تگ `<hr>` در HTML برای ایجاد خط افقی (افقی‌کش) در صفحه مورد استفاده قرار می‌گیرد. این تگ معمولاً برای جدا کردن قسمت‌های مختلف یک صفحه از یکدیگر یا ایجاد تقسیمات بین محتواها استفاده می‌شود. تگ `<hr>` در واقع یک خط افقی افقی بدون محتوا ایجاد می‌کند.

```html
<p>این یک متن است.</p>
<hr>
<p>این متن دیگری است که با یک خط افقی جدا شده است.</p>
```
![image](https://github.com/milad6745/HTML/assets/113288076/bb202183-cab1-4874-bc24-225d28474383)


## comment کامنت
<body>
    
    <h1>این یک متن است.</h1>
    <hr />
    <!-- کامنت نمایش داده نمیشد -->
    <h2>این متن دیگری است که با یک خط افقی جدا شده است.</h2>
    
</body>
