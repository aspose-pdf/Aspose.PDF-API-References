---
title: "واجهة ICustomSecurityHandler"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "واجهة Aspose.Pdf.Security.ICustomSecurityHandler. واجهة معالج الأمان المخصص."
type: docs
weight: 10150
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

واجهة معالج الأمان المخصص

```csharp
public interface ICustomSecurityHandler
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | يحصل على اسم الفلتر. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | يحصل على طول المفتاح. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | يحصل على مراجعة المعالج أو خوارزمية التشفير. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | يحصل على اسم الفلتر الفرعي. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | يحصل على نسخة المعالج أو خوارزمية التشفير. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | احسب EncryptionKey. عادةً يتم حساب المفتاح بناءً على UserKey. يمكنك استخدام القيم من EncryptionParams، التي تحتوي على المعلمات الحالية وقت الاستدعاء. يتم تمرير هذه القيمة كمعامل المفتاح في [`Encrypt`](./encrypt/) و[`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | فك تشفير مصفوفة البيانات. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | تشفير مصفوفة البيانات. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | تشفير حقل أذونات المستند. سيتم كتابة النتيجة إلى حقل القاموس المشفر Perms. عند فتح مستند، يمكن الحصول على القيمة في [`EncryptionParameters`](../encryptionparameters/) عبر حقل Perms. يتيح لك التحقق مما إذا كانت أذونات المستند قد تغيرت. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | ينشئ مصفوفة مشفرة بناءً على كلمات المرور التي ستكتب إلى الحقل O في قاموس التشفير. يجب الاعتماد فقط على الوسائط الممررة. يمكن حساب كلمة مرور المستخدم من هذا الحقل باستخدام كلمة مرور المالك. يُستدعى أثناء التشفير لإعداده وتعبئة قاموس التشفير. ستكون القيمة متاحة في [`CalculateEncryptionKey`](./calculateencryptionkey/) للحصول على المفتاح من UserKey. سيتم تمرير كلمات المرور التي حددها المستخدم عند استدعاء تشفير المستند. قد لا يتم تحديد كلمات مرور أو قد يتم تحديد كلمة واحدة فقط. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | ينشئ مصفوفة مشفرة بناءً على كلمة مرور المستخدم. تُستخدم هذه القيمة عادةً للتحقق مما إذا كانت كلمة المرور تخص المستخدم أو المالك، وللحصول على مفتاح التشفير. يُستدعى أثناء التشفير لإعداده وتعبئة القاموس المشفر. يتم تمرير كلمة مرور المستخدم المحددة كوسيط عند استدعاء تشفير المستند. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | يُستدعى لتهيئة المثيل الحالي للتشفير. لاحظ أنه عند التشفير، سيتم ملؤه ببيانات الخصائص المنقولة `ICustomSecurityHandler`، وعند فتح المستند من قاموس التشفير. إذا تم استدعاء الطريقة أثناء تشفير جديد، فإن [`UserKey`](../encryptionparameters/userkey/) و[`OwnerKey`](../encryptionparameters/ownerkey/) ستكونان فارغتين. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | تحقق مما إذا كانت كلمة المرور هي كلمة مرور مالك المستند. تُستدعى الطريقة بعد Initialize. يُستخدم استدعاء الطريقة في واجهة برمجة تطبيقات PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | تحقق مما إذا كانت كلمة المرور تخص المستخدم (كلمة المرور لفتح المستند). يتم استدعاء الطريقة بعد Initialize. يتم استخدام استدعاء الطريقة في واجهة برمجة تطبيقات PDF. |

### انظر أيضًا

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


