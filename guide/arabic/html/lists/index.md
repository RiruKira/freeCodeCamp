---
title: Lists
localeTitle: قوائم
---
# قوائم

.يتم استخدام القوائم لعرض العناصر/البيانات و لدينا 3 أنواع من القوائم

## قوائم مرتبة

يتم استخدام القوائم المرتبة لوصف مجموعة مرتبة من العناصر/البيانات وعادة ما تعرض المتصفحات القائمة المرتبة برموز

.`<ol>` لأنشاء قائمة مرتبة نستعمل ميزة 

![alt text][ol]

[ol]: https://i.imgur.com/sPv8C6o.png "قائمة مرتبة"

:وتنقسم القوائم المرتبة إلى خمسة أصناف

**: الأرقام**

![alt text][num]

[num]: https://i.imgur.com/XrZgr68.png "الأرقام"

**: حروف لاتينية صغيرة**

![alt text][a]

[a]: https://i.imgur.com/gAVVnAY.png "حروف لاتينية صغيرة"

**: حروف لاتينية كبيرة**

![alt text][Aa]

[Aa]: https://i.imgur.com/DuBWJmD.png "حروف لاتينية كبيرة"

**: أرقام لاتينية صغيرة**

![alt text][i]

[i]: https://i.imgur.com/W2qeWHH.png "أرقام لاتينية صغير"

**: أرقام لاتينية كبيرة**

![alt text][Ii]

[Ii]: https://i.imgur.com/KnE08JC.png "أرقام لاتينية كبيرة"

## قوائم غير مرتبة

يتم استخدام القوائم الغير المرتبة لوصف مجموعة غير مرتبة من العناصر/البيانات وعادة ما تعرض المتصفحات القائمة الغير المرتبة باستخدام علامات

.`<ul>` لأنشاء قائمة غير مرتبة نستعمل ميزة 

![alt text][ul]

[ul]: https://i.imgur.com/1xzVd6u.png "قائمة غير مرتبة"

:وتنقسم القوائم الغير المرتبة إلى ثلاثة أصناف

**: القرص**

![alt text][disc]

[disc]: https://i.imgur.com/poCezMZ.png "القرص"

**: الدائرة**

![alt text][circle]

[circle]: https://i.imgur.com/se2Dx8n.png "الدائرة"

**: المربع**

![alt text][square]

[square]: https://i.imgur.com/JIoqzO4.png "المربع"

## قائمة المواد

هي التي تحتوي على العناصر التي تكون داخل القوائم `<li>` قائمة المواد 

وتضاف على النحو التالي

![alt text][ol-li]

[ol-li]: https://i.imgur.com/wvYN2jY.png "ol-li"

![alt text][ul-li]

[ul-li]: https://i.imgur.com/bcybzPy.png "ul-li"

## أمثلة

:تتم كتابة قائمة مرتبة كالتالي

`<ol type="A"> 
  <li>January </li> 
  <li>February </li> 
  <li>March </li> 
</ol>`

![alt text][ol-A]

[ol-A]: https://i.imgur.com/PfmRr0E.png "ol-A"

:ويتم عرضها على النحو التالي

![alt text][final-ol]

[final-ol]: https://i.imgur.com/nPAaIuP.png "final-ol"

:تتم كتابة قائمة غير مرتبة كالتالي

`
<ul type="square"> 
  <li>Macintosh </li> 
  <li>Fuji </li> 
  <li>Gala </li> 
</ul>
` 

![alt text][ul-square]

[ul-square]: https://i.imgur.com/OIlFMDC.png "ul-square"

:ويتم عرضها على النحو التالي

![alt text][final-ul]

[final-ul]: https://i.imgur.com/cOU6OOo.png "final-ul"


## نقاط رصاص التصميم

يمكن استخدام قائمة مرتبة لمجموعة متنوعة من الوظائف وفي عدد من الأنماط. نظرًا لأن تغيير ألوان العلامة الشاملة لا يؤدي إلى تغيير لون الرموز النقطية نفسها ، فيمكنك تنسيقها من خلال إزالة الرموز السوداء التقليدية وإدخال التعدادات الخاصة بك:

إزالة الرموز النقطية:

 `ul { 
  list-style: none; 
  } 
` 

قم بإدخال الخاص بك:

 `ul li::before { 
  content: "\2022"; 
  color: orange; 
  display: inline-block; 
  width: 1em; 
  } 
` 

يضيف نمط المحتوى نقطية جديدة بينما يعمل نمط العرض والعرض على إنشاء مسافة بين الرمز النقطي والكلمة. يمكن تطبيق أنماط الخطوط العادية هنا إذا كنت ترغب في جعل الرمز النقطي أكبر أو أكثر جرأة.

## قوائم الوصف

قائمة الوصف هي قائمة من المصطلحات ، مع وصف لكل مصطلح. يتم إجراء قائمة وصف باستخدام العلامة `<dl>` . يتكون كل عنصر في القائمة من علامتين: عبارة `<dt>` ، ووصف لهذا المصطلح `<dd>` . يطلق عليها قوائم تعريف في HTML 4.

في ما يلي مثال لقائمة الوصف:

 `<dl> 
  <dt>Programming</dt> 
  <dd>The process of writing computer programs.</dd> 
  <dt>freeCodeCamp</dt> 
  <dd>An awesome non-profit organization teaching people how to code.</dd> 
 </dl> 
` 

والتي من شأنها أن تبدو وكأنها:

برمجة

عملية كتابة برامج الكمبيوتر.

freeCodeCamp

منظمة غير هادفة للربح رائعة تعليم الناس كيفية رمز.

## معلومات اكثر:

*   [قوائم HTML على w3schools](https://www.w3schools.com/html/html_lists.asp)
