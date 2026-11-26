<div align="center">
  <img src="https://img.shields.io/badge/PYTHON%20BASICS%20NOTES-Learn%20by%20Practice-4b438f?style=for-the-badge&logo=python&logoColor=white" alt="Python Basics Notes" />
  <h1>🐍 Python Basics Notes</h1>
  <p><b>A friendly beginner guide to Python fundamentals, examples, exercises, and learning steps.</b></p>
  <img src="https://img.shields.io/badge/Python-d9d3f5?style=flat-square&logo=python&logoColor=4b438f" alt="Python" />
  <img src="https://img.shields.io/badge/Beginner%20Friendly-d5eee7?style=flat-square&logo=bookstack&logoColor=26735a" alt="Beginner friendly" />
  <img src="https://img.shields.io/badge/Examples-f9edb7?style=flat-square&logo=codepen&logoColor=756512" alt="Examples" />
</div>

> **Start simple, practice often, and let every error teach you something.**

## ✦ Inside this notebook

<table>
  <tr>
    <td width="50%" valign="top"><b>📘 Core Concepts</b><br />Variables, data types, conditions, loops, lists, and functions.</td>
    <td width="50%" valign="top"><b>🧩 Short Examples</b><br />Small snippets designed to be read, changed, and executed.</td>
  </tr>
  <tr>
    <td width="50%" valign="top"><b>🛠 Practice Ideas</b><br />Beginner projects such as calculators, games, and converters.</td>
    <td width="50%" valign="top"><b>☁ Learning Roadmap</b><br />A gradual path from first steps to object-oriented programming.</td>
  </tr>
</table>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python&theme=light" alt="Python icon" />
</div>

---

# ملاحظات أساسية حول لغة Python

مستودع تعليمي مبسط للمبتدئين في لغة **Python**. يشرح المفاهيم الأولى بطريقة عملية مع أمثلة قصيرة قابلة للتجربة، ويمكن استخدامه كمذكرة مراجعة أو نقطة بداية لبناء مشاريع صغيرة.

## لماذا Python؟

Python لغة برمجة عالية المستوى، سهلة القراءة والتعلم، وتستخدم في تطوير الويب، وتحليل البيانات والذكاء الاصطناعي، والأتمتة، والتعليم، وبناء النماذج الأولية.

## المتطلبات وطريقة التشغيل

1. ثبّت Python 3 من [الموقع الرسمي](https://www.python.org/downloads/).
2. تحقق من التثبيت:

```bash
python3 --version
```

3. انسخ المستودع أو نزّله كملف ZIP:

```bash
git clone https://github.com/mhndstalrwya-creator/python-basics-notes.git
cd python-basics-notes
```

4. شغّل أي ملف Python باستخدام:

```bash
python3 اسم_الملف.py
```

> الملاحظات الحالية موجودة في `README.md`، ويمكن إضافة ملفات تمارين مستقلة بامتداد `.py` داخل المستودع.

## المفاهيم المشروحة

### أول برنامج

```python
print("مرحبًا بالعالم!")
```

الدالة `print` تعرض نصًا أو قيمة على الشاشة.

### المتغيرات والأنواع

```python
name = "Roya"       # نص: str
age = 25             # عدد صحيح: int
price = 19.95        # عدد عشري: float
is_active = True     # قيمة منطقية: bool
```

لا تحتاج Python إلى التصريح بنوع المتغير مسبقًا؛ إذ تحدد النوع تلقائيًا بحسب القيمة.

### الشروط

```python
score = 85

if score >= 60:
    print("ناجح")
else:
    print("يحتاج إلى مراجعة")
```

المسافات البادئة جزء أساسي من بنية برنامج Python، لذلك يجب الحفاظ على ترتيبها.

### القوائم والحلقات

```python
languages = ["Python", "JavaScript", "Go"]

for language in languages:
    print(language)
```

تخزن `list` عدة قيم، وتسمح حلقة `for` بالمرور على العناصر واحدًا تلو الآخر.

### الدوال

```python
def greet(person):
    return f"مرحبًا يا {person}!"

message = greet("Roya")
print(message)
```

الدالة تجمع تعليمات قابلة لإعادة الاستخدام، ويمكنها استقبال مدخلات وإرجاع نتيجة.

## خطة تعلم مقترحة

1. المتغيرات وأنواع البيانات.
2. العمليات الحسابية والمقارنات.
3. الجمل الشرطية `if`.
4. الحلقات `for` و`while`.
5. القوائم والقواميس والمجموعات.
6. الدوال ونطاق المتغيرات.
7. قراءة الملفات ومعالجة النصوص.
8. التعامل مع الأخطاء باستخدام `try/except`.
9. البرمجة الكائنية باستخدام `class`.
10. إنشاء مشاريع صغيرة لتثبيت المفاهيم.

## تمارين مناسبة للمبتدئ

- آلة حاسبة بسيطة.
- برنامج يحسب متوسط الدرجات.
- قائمة مهام نصية.
- لعبة تخمين رقم.
- محول وحدات أو درجات حرارة.
- برنامج يحسب عدد الكلمات في نص.

## أخطاء شائعة

- نسيان النقطتين `:` بعد `if` أو `for` أو تعريف الدالة.
- استخدام مسافات بادئة غير متناسقة.
- الخلط بين `=` للإسناد و`==` للمقارنة.
- محاولة جمع نص مع رقم دون تحويل النوع.
- استخدام اسم متغير قبل تعريفه.

## أفضل ممارسات البداية

- اكتب برامج صغيرة واختبرها خطوة بخطوة.
- اقرأ رسالة الخطأ وحدد السطر المشار إليه قبل تعديل الكود.
- استخدم أسماء متغيرات واضحة باللغة الإنجليزية غالبًا.
- أضف تعليقات مختصرة عندما يكون سبب الكود غير واضح.
- جرّب الأمثلة بنفسك بدل الاكتفاء بقراءتها.

## المساهمة والتطوير

يمكن توسيع المستودع بإضافة ملفات تمارين مرتبة حسب المستوى:

```text
.
├── README.md
├── 01_variables.py
├── 02_conditions.py
├── 03_loops.py
├── 04_functions.py
└── exercises/
```

لإضافة تحسين، أنشئ فرعًا جديدًا، أضف المثال أو الشرح، ثم افتح Pull Request مع توضيح ما تم تغييره.

## الترخيص

المحتوى تعليمي ومتاح للاستخدام والمراجعة الشخصية. عند إعادة استخدام أجزاء كبيرة منه، يرجى الإشارة إلى هذا المستودع.
