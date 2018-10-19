---
title: Hello World C
localeTitle: Hello World C
---
## Hello World

.اللتان يحتيوان على مجموعة من الدوال <unistd.h> و المكتبة <stdio.h> لدينا المكتبة

.التي تسمح لنا بالكتابة على وحدة التحكم `printf()` لدينا الدالة <stdio.h> على سبيل المثال بالنسبة للمكتبة

.`write()` لدينا الدالة <unistd.h> و بالنسبة للمكتبة

: نضيف المكتبات في مقدمة الملف على الشكل التالي

`#include <stdio.h>`
أو
`#include <unistd.h>`

![alt text][library]

[library]: https://i.imgur.com/XDKpCrm.png "كيفية إضافة المكتبات"

كالتالي `int main(void)` بعد إضافة المكتبات نقوم بإضافة الدالة 

![alt text][main]

[main]: https://i.imgur.com/dkK1sXL.png " int main() إضافة الدالة"

داخل أقواس الهلال نقوم بكتابة الدالة التي نريد أن نستعمل و ما نريد بداخلها كما تبين الصور

فهي سهلة الإستعمال كالتالي `print(f)` فيما يخص الدالة

![alt text][printf]

[printf]: https://i.imgur.com/xWQcaV9.png "printf()"

فنقوم بإضافة معلمة = 1 ثم بعد كتابة ما نريد نضيف معلمة = عدد الحروف/الرموز `write()` أما بخصوص الدالة 

## : ملاحظة 
يعتبر رمز واحد وليس إثنين /n إضافة سطر جديد

![alt text][write]

[write]: https://i.imgur.com/ewIqPo7.png "write()"

## : تفسير

* **.بإضافة المكتبة نخبر البرنامج بأن يضمن محتويات المكتبة بلوحة التحكم**

* **.بدون كتابة # عند إضافة المكتبة لن تسمح باستعمال الدوال**

* **.`int main(void)` إنطلاقا وبتنفيد C يبدأ برنامج** 

* **. بإرسال وعرض الرموز على الشاشة `write()` و `printf()` تقوم كل من**

* **.بعبارة مبسطة يعني الخروج من الوضع، وينتهي البرنامج بهذا البيان Return(0) إعادة البيان 0 أي**

    
## : النتيجة    

> Hello World

![alt text][result]

[result]: https://i.imgur.com/FC4kISm.png "result"
