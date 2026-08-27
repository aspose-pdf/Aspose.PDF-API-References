---
title: "Aspose.Pdf.Forms"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "مساحة الأسماء Aspose.Pdf.Forms تحتوي على فئات تصف معايير النماذج الثابتة والديناميكية وأنواع مختلفة من الحقول مثل مربع النص، مربع القائمة، زر الراديو، إلخ."
type: docs
weight: 110
url: /ar/net/aspose.pdf.forms/
---
تحتوي مساحة الاسم **Aspose.Pdf.Forms** على فئات تصف النماذج (قياسية، ثابتة، ديناميكية) وأنواع مختلفة من الحقول مثل مربع النص، مربع القائمة، زر الاختيار إلخ.

## الفئات

| فئة | الوصف |
| --- | --- |
| [BarcodeField](./barcodefield/) | الفئة تمثل حقل الباركود. |
| [ButtonField](./buttonfield/) | الفئة تمثل حقل زر الضغط. |
| [CheckboxField](./checkboxfield/) | الفئة تمثل حقل خانة الاختيار |
| [ChoiceField](./choicefield/) | تمثل الفئة الأساسية لحقول الاختيار. |
| [ComboBoxField](./comboboxfield/) | الفئة تمثل حقل القائمة المنسدلة في النموذج. |
| [DateField](./datefield/) | حقل تاريخ مع عرض تقويم. |
| [DocMDPSignature](./docmdpsignature/) | تمثل الفئة لنوع توقيع MDP (كشف التعديل ومنعه) للمستند. |
| [ExternalSignature](./externalsignature/) | ينشئ توقيع PKCS#7 منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB، ورموز بدون مفاتيح خاصة قابلة للتصدير. |
| [Field](./field/) | الفئة الأساسية لحقول نموذج Acro. |
| [FileSelectBoxField](./fileselectboxfield/) | حقل لعنصر مربع اختيار ملف. |
| [Form](./form/) | الفئة تمثل كائن النموذج. |
| [IconFit](./iconfit/) | يصف كيفية عرض أيقونة التعليق التوضيحي للودجت داخل مستطيل التعليق الخاص به. |
| [ListBoxField](./listboxfield/) | الفئة تمثل حقل مربع القائمة. |
| [NumberField](./numberfield/) | حقل نص مع أحرف صالحة محددة |
| [Option](./option/) | الفئة تمثل خيارًا لحقل الاختيار. |
| [OptionCollection](./optioncollection/) | الفئة تمثل مجموعة من الخيارات لحقل الاختيار. |
| [PasswordBoxField](./passwordboxfield/) | الفئة تصف حقل نص لإدخال كلمة المرور. |
| [PKCS1](./pkcs1/) | يمثل كائن التوقيع المتعلق بمعيار PKCS#1. يتم استخدام خوارزمية تشفير RSA وطريقة التجزئة SHA-1 للتوقيع. |
| [PKCS7](./pkcs7/) | يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغ الرسائل المشفرة، الإصدار 1.5. يتم تضمين `SHA1 digest` لنطاق بايتات المستند في حقل PKCS#7 SignedData. |
| [PKCS7Detached](./pkcs7detached/) | يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغ الرسائل المشفرة، الإصدار 1.5. يتم دمج تجزئة الرسالة الموقعة الأصلية على نطاق بايتات المستند كحقل PKCS#7 SignedData العادي. لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData. |
| [RadioButtonField](./radiobuttonfield/) | فئة تمثل حقل زر الاختيار. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | الفئة تمثل عنصرًا من حقل RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | الفئة تصف مكوّن محرر النص الغني. |
| [Signature](./signature/) | فئة مجردة تمثل كائن التوقيع في مستند pdf. التوقيعات هي حقول ذات قيم كائنات توقيع، وتحتوي الأخيرة على بيانات تُستخدم للتحقق من صحة المستند. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | فئة مجردة تمثل كائن مظهر التوقيع المخصص. |
| [SignatureField](./signaturefield/) | يمثل حقل نموذج التوقيع. |
| [SignHash](./signhash/) | مفوض لتوقيع تجزئة المستند بشكل مخصص. |
| [TextBoxField](./textboxfield/) | فئة تمثل حقل مربع النص. |
| [XFA](./xfa/) | يمثل نموذج XML المتعلق بـ XML Forms Architecture (XFA). |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [BoxStyle](./boxstyle/) | يمثل الأنماط لرسم علامة الاختيار في مربع الاختيار. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | أذونات الوصول الممنوحة لهذا المستند. القيم الصالحة هي: 1 - لا يُسمح بأي تغييرات على المستند؛ أي تعديل على المستند يبطل التوقيع. 2 - التغييرات المسموح بها هي ملء النماذج، إنشاء قوالب الصفحات، والتوقيع؛ التغييرات الأخرى تبطل التوقيع. 3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات التوضيحية، حذفها، وتعديلها؛ التغييرات الأخرى تبطل التوقيع. |
| [FormType](./formtype/) | تعداد الأنواع المحتملة لنموذج Acro Form. |
| [IconCaptionPosition](./iconcaptionposition/) | يصف موضع الأيقونة. |
| [ScalingMode](./scalingmode/) | نوع التحجيم الذي سيُستخدم. |
| [ScalingReason](./scalingreason/) | الظروف التي يتم فيها تحجيم الأيقونة داخل مستطيل Annotation. |
| [SubjectNameElements](./subjectnameelements/) | التعداد يصف العناصر في سلسلة موضوع التوقيع. |
| [Symbology](./symbology/) | تحدد رمزية (Barcode) التفاصيل التقنية لنوع معين من الباركود: عرض الخطوط، مجموعة الأحرف، طريقة الترميز، مواصفات المجموع الاختباري، إلخ. |


