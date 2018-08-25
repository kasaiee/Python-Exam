<div dir="rtl">

## سوال اول

خروجی کد زیر چیسن؟

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

1. None None
2. None 11
3. 11 None
4. 11 11
5. خطا ایجاد می‌شود


## سوال دوم

خروجی کد زیر چیست؟

```
class Account:
    def __init__(self, id):
        self.id = id
        id = 666 

acc = Account(123)
print(acc.id)
```

1. None
2. 123
3. 666
4. این برنامه SyntaxError داشته و اجرا نخواهد شد

</div>