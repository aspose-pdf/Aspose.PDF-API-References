---
title: "الفئة EncryptionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.EncryptionOptions. تمثل خيارات التشفير لإضافة Security"
type: docs
weight: 8670
url: /ar/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

تمثل خيارات التشفير لإضافة [`Security`](../security/)

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | يُنشئ نسخة جديدة من كائن `EncryptionOptions` مع الخيارات الافتراضية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | إغلاق تدفقات الإدخال بعد إكمال العملية. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | إغلاق تدفقات الإخراج بعد إكمال العملية. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | خوارزمية تشفيرية، راجع [`CryptoAlgorithm`](./cryptoalgorithm/) للحصول على التفاصيل. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | أذونات المستند، راجع [`Permissions`](../../aspose.pdf/permissions/) للحصول على التفاصيل. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | يعيد مجموعة بيانات إضافة OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | يحصل على مجموعة الأهداف المضافة لحفظ نتائج العملية. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | كلمة مرور المالك. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | كلمة مرور المستخدم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات إضافة PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات إضافة PdfOrganizer. |

### انظر أيضًا

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


