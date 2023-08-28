# Form


```html
<!DOCTYPE html>
<html>
<body>
<!-- برای ایجاد فرم ابتدا یه تگ فرم باز میکنیم -->
<!-- اکشن به مامیگه بعد از لاگین کجا بره -->
<!-- متد یعنی مقادیر را بگیر -->
<!-- قسمت input یعنی مواردی که قراره از ما بگیره -->
<!-- تایپ پسورد باعث میشه پسورد بصورت نقطه نمایش داده شود -->
<!-- قبل از ایمپوت اون یوزر و پسورد نشان دهنده مقداریه که قرار بگیره -->

    <form action="http://google.com" method="GET">
    username : <input type="text" name="username"><br/>
    password : <input type="password" name="password"><br/>
    <button type="submit"> Submit</button>
    </form>

</body>
</html>
```

# Radio & checkbox Tag
```html
<!DOCTYPE html>
<html>
<body>
<!-- برای ایجاد فرم ابتدا یه تگ فرم باز میکنیم -->
<!-- اکشن به مامیگه بعد از لاگین کجا بره -->
<!-- متد یعنی مقادیر را بگیر -->
<!-- قسمت input یعنی مواردی که قراره از ما بگیره -->
<!-- تایپ پسورد باعث میشه پسورد بصورت نقطه نمایش داده شود -->
<!-- قبل از ایمپوت اون یوزر و پسورد نشان دهنده مقداریه که قرار بگیره -->

<p style="color: rebeccapurple;"> SIGN IN  </p>
    <form action="http://google.com" method="GET">
    username :</br> <input type="text" name="username"><br/>
    password : </br> <input type="password" name="password"><br/>
    Email: </br><input type="email" name="mail"><br/>
    Are Youre Sure sign in <input type="checkbox"><br/>
    
    <!-- برای اینکه مورد بگذلزیم که کاربر تنها یک گزینه را بتواند انتخاب کند از تایپ رادیو استفاده میکنیم و حتما برای ارتباط موارد باید نام ها را یکی بگزاریم -->
    what's You Gender ? <br>
    male<input type="radio" name="gender" value="male">
    female<input type="radio" name="gender" value="female">

    <button type="submit" > Submit</button>
    </form>
</p>

</body>
</html>
```
