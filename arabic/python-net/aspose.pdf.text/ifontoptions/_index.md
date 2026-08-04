---
title: "IFontOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "خصائص مفيدة لضبط سلوك الخط"
type: docs
weight: 180
url: /ar/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

خصائص مفيدة لضبط سلوك الخط

يعرض نوع IFontOptions الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| notify_about_font_embedding_error | أحيانًا لا يمكن تضمين الخط المطلوب في المستند. هناك العديد من الأسباب، على سبيل المثال<br/>            قيود الترخيص أو عندما لا يتم العثور على الخط المطلوب على جهاز الوجهة.<br/>            عندما يحدث هذا الوضع ليس من السهل اكتشافه، لأن الخط المطلوب يتم تضمينه عبر تعيين <br/>            علم الخاصية Font.IsEmbedded = true؛ بالطبع يمكن قراءة هذه الخاصية فور تعيينها لكن<br/>            ذلك ليس نهجًا ملائمًا. يفرض علم NotifyAboutFontEmbeddingError آلية استثناء <br/>            للحالات التي يفشل فيها محاولة تضمين الخط. إذا تم تعيين هذا العلم سيتم رمي استثناء من النوع<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) . يكون القيمة الافتراضية false. |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

