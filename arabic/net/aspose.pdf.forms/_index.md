---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: يحتوي مساحة أسماء Aspose.Pdf.Forms على فئات تصف النماذج ثابتة، ديناميكية وأنواع مختلفة من الحقول مثل مربع النص، مربع القائمة، زر الاختيار، إلخ.
type: docs
weight: 110
url: /ar/net/aspose.pdf.forms/
---
تحتوي مساحة أسماء **Aspose.Pdf.Forms** على فئات تصف النماذج (ثابتة، ديناميكية) وأنواع مختلفة من الحقول مثل مربع النص، مربع القائمة، زر الاختيار، إلخ.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [BarcodeField](./barcodefield/) | تمثل الفئة حقل الباركود. |
| [ButtonField](./buttonfield/) | تمثل الفئة حقل زر الدفع. |
| [CheckboxField](./checkboxfield/) | تمثل الفئة حقل خانة الاختيار. |
| [ChoiceField](./choicefield/) | تمثل الفئة الفئة الأساسية لحقول الاختيار. |
| [ComboBoxField](./comboboxfield/) | تمثل الفئة حقل قائمة منسدلة للنموذج. |
| [DateField](./datefield/) | حقل تاريخ مع عرض تقويمي. |
| [DocMDPSignature](./docmdpsignature/) | تمثل الفئة نوع توقيع MDP (الكشف عن التعديل ومنعه) للوثيقة. |
| [ExternalSignature](./externalsignature/) | ينشئ توقيع PKCS#7 منفصل باستخدام X509Certificate2. يدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير. |
| [Field](./field/) | الفئة الأساسية لحقول نموذج أكرو. |
| [FileSelectBoxField](./fileselectboxfield/) | حقل لعنصر مربع اختيار الملف. |
| [Form](./form/) | تمثل الفئة كائن النموذج. |
| [IconFit](./iconfit/) | تصف كيفية عرض أيقونة التعليق داخل مستطيل التعليق الخاص بها. |
| [ListBoxField](./listboxfield/) | تمثل الفئة حقل قائمة. |
| [NumberField](./numberfield/) | حقل نصي مع أحرف صالحة محددة. |
| [Option](./option/) | تمثل الفئة خيار حقل الاختيار. |
| [OptionCollection](./optioncollection/) | تمثل الفئة مجموعة من خيارات حقل الاختيار. |
| [PasswordBoxField](./passwordboxfield/) | تصف الفئة حقل نصي لإدخال كلمة المرور. |
| [PKCS1](./pkcs1/) | تمثل الفئة كائن التوقيع وفقًا لمعيار PKCS#1. يتم استخدام خوارزمية تشفير RSA وطريقة تجزئة SHA-1 للتوقيع. |
| [PKCS7](./pkcs7/) | تمثل الفئة كائن PKCS#7 الذي يتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغة الرسالة التشفيرية، الإصدار 1.5. يتم تضمين `تجزئة SHA1` لنطاق بايت الوثيقة في حقل PKCS#7 SignedData. |
| [PKCS7Detached](./pkcs7detached/) | تمثل الفئة كائن PKCS#7 الذي يتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغة الرسالة التشفيرية، الإصدار 1.5. يتم دمج تجزئة الرسالة الموقعة الأصلية على نطاق بايت الوثيقة كحقل PKCS#7 SignedData العادي. لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData. |
| [RadioButtonField](./radiobuttonfield/) | تمثل الفئة حقل زر الاختيار. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | تمثل الفئة عنصر حقل زر الاختيار. |
| [RichTextBoxField](./richtextboxfield/) | تصف الفئة مكون محرر النص الغني. |
| [Signature](./signature/) | فئة مجردة تمثل كائن التوقيع في وثيقة PDF. التوقيعات هي حقول بقيم كائنات التوقيع، تحتوي الأخيرة على بيانات تُستخدم للتحقق من صحة الوثيقة. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | فئة مجردة تمثل كائن المظهر المخصص للتوقيع. |
| [SignatureField](./signaturefield/) | تمثل الفئة حقل توقيع النموذج. |
| [SignHash](./signhash/) | مفوض لتوقيع تجزئة الوثيقة بشكل مخصص. |
| [TextBoxField](./textboxfield/) | تمثل الفئة حقل مربع النص. |
| [XFA](./xfa/) | تمثل الفئة نموذج XML فيما يتعلق بهندسة النماذج XML (XFA). |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [BoxStyle](./boxstyle/) | تمثل الأنماط لرسم علامة في خانة الاختيار. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | أذونات الوصول الممنوحة لهذه الوثيقة. القيم الصالحة هي: 1 - لا يُسمح بإجراء تغييرات على الوثيقة؛ أي تغيير في الوثيقة يبطل التوقيع. 2 - التغييرات المسموح بها هي ملء النماذج، إنشاء قوالب الصفحات، والتوقيع؛ التغييرات الأخرى تبطل التوقيع. 3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات، الحذف، والتعديل؛ التغييرات الأخرى تبطل التوقيع. |
| [FormType](./formtype/) | تعداد لأنواع نموذج أكرو الممكنة. |
| [IconCaptionPosition](./iconcaptionposition/) | تصف موضع الأيقونة. |
| [ScalingMode](./scalingmode/) | نوع التحجيم الذي يجب استخدامه. |
| [ScalingReason](./scalingreason/) | الظروف التي يجب أن يتم فيها تحجيم الأيقونة داخل مستطيل التعليق. |
| [SubjectNameElements](./subjectnameelements/) | تعداد يصف العناصر في سلسلة موضوع التوقيع. |
| [Symbology](./symbology/) | يحدد (الباركود) الرمزية التفاصيل الفنية لنوع معين من الباركود: عرض القضبان، مجموعة الأحرف، طريقة الترميز، مواصفات مجموع التحقق، إلخ. |