 # دليل استخدام لغة Apm#

## المقدمة:
هذا الدليل يوضح كيفية استخدام لغة البرمجة Apm#.

## الجزئيات الأساسية:
### المكونات:
يتيح لك لغة Apm# تحديد مكونات مثل الأزرار، النصوص، الصور، ومكونات أخرى.

### التخطيطات:
يمكنك تنظيم المكونات داخل تخطيطات، مثل صفوف وأعمدة.

## الأمثلة:
### مثال 1: إنشاء زر
```apm#
.Component[
    "button" → type
    "Click me" → text
    "#FFFFFF" → background_color
    "#000000" → text_color
    "100px" → width
    "50px" → height
    "active" → state
    "bold" → font_style
    "rounded" → shape
]
