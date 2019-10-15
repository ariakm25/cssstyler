## ساکھ کا اعلان

یہ منصوبہ کانٹا ہے۔ پر ایک نظر ڈالیں  [مین ریپو](https://github.com/senchalabs/cssbeautify)  .

# [](https://github.com/AmirMehrabi/cssstyler#css-beautify)سی ایس ایس کو خوبصورت بنائیں

سی ایس ایس بیوٹیفائف لکھا ہوا شیلیوں کے لئے قطبی ہرن اور فارمیٹر کا جاوا اسکرپٹ عمل ہے [سی ایس ایس](http://www.w3.org/Style/CSS/).

مندرجہ ذیل انداز دیئے گئے:

```cmenu{color:red} navigation{background-color:#333}c```

:سی ایس ایس خوبصورتی پیدا کرے گا
```css
menu {
    color: red
}

navigation {
    background-color: #333
}
```

اسے آن لائن پر آزمائیں[cssbeautify.com](http://cssbeautify.com/). کمانڈ لائن استعمال کے لئے ، نوڈ.js  [cssbeautify](https://npmjs.org/package/cssbeautify)  پیکیج.

مزید مثالوں کے لئے ، اس کو بھی دیکھیں  [ٹیسٹ سویٹ](http://cssbeautify.com/test/).

## [](https://github.com/AmirMehrabi/cssstyler#using-cssbeautify-function)استعمال کرنا cssbeautify() تقریب


چونکہ سی ایس ایس بیوٹیفائیو خالص جاوا اسکرپٹ میں لکھا گیا ہے ، لہذا یہ کہیں بھی چلا سکتا ہے جہاں جاوا اسکرپٹ چل سکتا ہے۔

:API بہت آسان ہے

```var result = cssbeautify(style, options);```

**اختیارات**  فارمیٹنگ کو ایڈجسٹ کرنے کے لئے ایک اختیاری شے ہے۔ ابھی تک معلوم اختیارات یہ ہیں


- `انڈین` ایک ڈور ہے جو اعلامیے کے انڈینٹیشن کے لئے استعمال کی جاتی ہے (پہلے سے طے شدہ جگہ 4 جگہ ہوتی ہے)
- `اوپنبریس` کھلی گھوبگھرالی منحنی خطوط وحدانی کی جگہ کی وضاحت کرتی ہے ، یا تو _end-of-line_ (default) یا _separate-line_۔
- آخری ضابطے کے بعد ہمیشہ se آٹوزیمکولون ایک سیمکولن داخل کرتا ہے (ڈیفالٹ _ فالس_ ہے)


:مثال کال

```js
var beautified = cssbeautify('menu{opacity:.7}', {
    indent: '  ',
    openbrace: 'separate-line',
    autosemicolon: true
});
```

## [](https://github.com/AmirMehrabi/cssstyler#contributing)تعاون کرنا

شراکت کا خیر مقدم کیا جاتا ہے! براہ کرم پڑھیں  [شراکت گائیڈ](https://github.com/AmirMehrabi/cssstyler/blob/master/CONTRIBUTING.md)  مزید معلومات کے ل.



## [](https://github.com/AmirMehrabi/cssstyler#license)لائسنس

]کاپی رائٹ (C) 2012 Sencha Inc. کاپی رائٹ (C) 2011 Sencha Inc.

کسی بھی شخص کو بغیر کسی پابندی کے اس سافٹ ویئر اور اس سے وابستہ دستاویزات فائلوں ("سافٹ ویئر") کی کاپی حاصل کرنے والے کو بلا معاوضہ اجازت دی گئی ہے ، بغیر کسی پابندی کے سافٹ ویئر میں نمٹنے کے ، استعمال کرنے ، کاپی ، ترمیم کرنے ، ضم کرنے کے حقوق سمیت ، سافٹ ویئر کی اشاعت ، تقسیم ، سبیلینس ، اور / یا اس کی کاپیاں بیچنا ، اور ان افراد کو اجازت دینے کے لئے جن کو یہ سافٹ ویئر پیش کیا گیا ہے ، مندرجہ ذیل شرائط کے تحت:

مذکورہ حق اشاعت کا نوٹس اور اس اجازت نامہ کو سافٹ ویئر کی تمام کاپیاں یا کافی حص .وں میں شامل کیا جائے گا۔

سافٹ ویئر کو "جیسا کہ" فراہم کیا جاتا ہے ، کسی قسم کی ضمانت ، اظہار یا اس کے بغیر ، کاروبار کی وارنٹیوں تک محدود نہیں ہوتا ہے ، لیکن خصوصی مقصد اور نامزدکاری کی فٹنس کی ضمانت ہوتی ہے۔ کسی بھی معاملے میں مصنف یا کاپی رائٹ ہولڈرز کسی بھی دعوی ، نقصان یا کسی اور ذمہ داری کے لئے ذمہ دار نہیں ہوسکتے ہیں ، معاہدے ، ٹورٹ یا کسی اور کام کے ذریعہ ، سافٹ ویئر کے ذریعہ یا اس سافٹ ویئر کے ذریعہ یا کسی اور رابطے میں سافٹ ویئر