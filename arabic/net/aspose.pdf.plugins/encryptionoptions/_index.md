---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.EncryptionOptions. تمثل خيارات التشفير لملحق الأمان
type: docs
weight: 8540
url: /ar/net/aspose.pdf.plugins/encryptionoptions/
---
## فئة خيارات التشفير

تمثل خيارات التشفير لملحق [`Security`](../security/) .

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | يقوم بتهيئة مثيل جديد من كائن `EncryptionOptions` مع خيارات افتراضية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | إغلاق تدفقات الإدخال بعد اكتمال العملية. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | إغلاق تدفقات الإخراج بعد اكتمال العملية. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | الخوارزمية التشفيرية، انظر [`CryptoAlgorithm`](./cryptoalgorithm/) لمزيد من التفاصيل. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | أذونات الوثيقة، انظر [`Permissions`](../../aspose.pdf/permissions/) لمزيد من التفاصيل. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | يعيد مجموعة بيانات ملحق OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | يحصل على مجموعة من الأهداف المضافة لنتائج عملية الحفظ. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | كلمة مرور المالك. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | كلمة مرور المستخدم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات ملحق PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات ملحق PdfOrganizer. |

### انظر أيضًا

* فئة [OrganizerBaseOptions](../organizerbaseoptions/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)