<div dir="rtl">

## سوال اول

خروجی کد زیر چیسن؟

<div dir="ltr">

```
class parent:
    def __init__(self, param):
        self.v1 = param

class child(parent):
    def __init__(self, param):
        self.v2 = param

obj = child(11)
print(obj.v1 + " " + obj.v2)
```

</div>

1. None None
2. None 11
3. 11 None
4. 11 11
5. خطا ایجاد می‌شود


## سوال دوم

خروجی کد زیر چیست؟

<div dir="ltr">

```
class Account:
    def __init__(self, id):
        self.id = id
        id = 666 

acc = Account(123)
print(acc.id)
```

</div>

1. None
2. 123
3. 666
4. این برنامه SyntaxError داشته و اجرا نخواهد شد


## سوال سوم

کدام گزینه درست نیست؟

1. پایتون به طور رسمی از Abstraction پشتیبانی نمی‌کند و برای Abstraction لازم است از ماژول abc استفاده کنیم.
2. پایتون ۳ از multi inheritance پشتیبانی می‌کند اما پایتون ۲ خیر
3. پایتون ۲ دو نوع ارث بری به به نام های old و new دارد اما پایتون ۳ فقط یکی دارد و آن هم همانی است که در پایتون ۲ با نام new شناخته می‌شود.
4. در پایتون ۳ همه کلاس ها به صورت پیش‌فرض از کلاسی به نام object ارثبری می‌کنند.


## سوال چهارم

اگر کد زیر در پایتون ۳ اجرا شود، خروجی آن چیست؟

<div dir="ltr">

```
class A(object):
    pass

class B(A):
    pass

class C(A):
    pass

class D(B, C):
    pass

d = D()
print(D.mro())
```


>>1. `[<class '__main__.D'>, <class '__main__.B'>, <class '__main__.C'>, <class '__main__.A'>, <class 'object'>]`
2. `[<class 'object'>, <class '__main__.A'>, <class '__main__.C'>, <class '__main__.B'>, <class '__main__.D'>]`
3. `[<class '__main__.D'>, <class '__main__.A'>, <class '__main__.B'>, <class '__main__.C'>, <class 'object'>]`
4. `[<class 'object'>, <class '__main__.A'>, <class '__main__.B'>, <class '__main__.C'>, <class '__main__.D'>]`

</div>


## سوال پنجم

کدام گزینه درست نیست؟

1. متد __init__ نباید خروجی داشته باشد.
2. متد __new__ فقط در پایتون ۳ وجود دارد.
3. __slot__ ها در ارث بری به ارث برده نمی‌شوند.
>>4. متد __del__ وظیفه اش صدا کردن Garbage Collector است.


## سوال ششم

کدام گزینه در مورد Abstraction درست نیست؟

1. پایتون به صورت رسمی از Abstraction پشتیبانی می‌کند.
2. Abstract Class کلاسی است که نمی‌توان از آن هیچ instance ای ساخت
3. Abstract Class کلاسی است که علاوه بر اینکه از ABC ارثبری می‌کند، حداقل یک Abstract Method دارد
4. تا زمانی که Abstract Method ها را در کلاس فرزند که از یک کلاس abstract ارث بری کرده override نکنید، امکان ساخت instance از آن وجود ندارد.



## سوال هفتم

کدام گزینه در مورد تابع super درست نیست؟

1. فقط در پایتون ۳ وجود دارد
2. فقط در new style inheritance وجود دارد
3. امکان فراخوانی یک متد را به صورت داینامیک از والدین فراهم می‌کند.
4. یکی از کاربرد های اصلی آن در override کردن یک متد از یک کلاس است.
</div>