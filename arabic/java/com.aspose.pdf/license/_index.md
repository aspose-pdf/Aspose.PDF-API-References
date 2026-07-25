---
title: "License"
linktitle: "License"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يوفر طرقًا لتفعيل المكوّن. في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، في الـ"
type: docs
weight: 2670
url: /ar/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

يوفر طرقًا لترخيص المكوّن. في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic");

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License](#License--) | ينشئ مثيلًا جديدًا لهذه الفئة. في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على التجميع المستدعي، في مجلد التجميع الرئيسي ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic"); |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [clearLicense](#clearLicense--) | يمسح الترخيص الحالي. |
| [getLicenseInfo](#getLicenseInfo--) | يحصل على معلومات الترخيص الحالي. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | بشكل افتراضي، نحن نستخدم أمان jdk الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | بشكل افتراضي، نحن نستخدم أمان jre الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا. <p> لاحظ أيضًا: وفقًا لخوارزمية JVM SecureRandom على بعض أنظمة التشغيل، ينتظر /dev/random كمية معينة من “الضوضاء” لتُولد على الجهاز المضيف قبل إرجاع النتيجة. المكتبة المستخدمة لتوليد الأرقام العشوائية في JVM الخاص بأوراكل تعتمد على /dev/random بشكل افتراضي لمنصات UNIX. على الرغم من أن /dev/random أكثر أمانًا، يُنصح باستخدام /dev/urandom إذا كان تكوين JVM الافتراضي يسبب تأخيرات، أو إضافة أجهزة تولد إنتروبيا لـ /dev/random. <p> خيار جافا التالي يمكن أن يساعد على تجنب التأخيرات وتجاوز إعداد securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | يفعل المكوّن. تدفق يحتوي على الترخيص. استخدم هذه الطريقة لتحميل الترخيص من تدفق. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | يفعل المكوّن. يحاول العثور على الترخيص في المواقع التالية: 1. مسار صريح. 2. مجلد ملف jar الخاص بالمكوّن. في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على التجميع المستدعي، في مجلد التجميع الرئيسي ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

ينشئ مثيلًا جديدًا لهذه الفئة. في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على التجميع المستدعي، في مجلد التجميع الرئيسي ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

يمسح الترخيص الحالي.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

يحصل على معلومات الترخيص الحالي.

**Returns:**
مثيل LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

بشكل افتراضي، نحن نستخدم أمان jdk الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا.

**Returns:**
قيمة منطقية

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

بشكل افتراضي، نحن نستخدم أمان jre الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا. <p> لاحظ أيضًا: وفقًا لخوارزمية JVM SecureRandom على بعض أنظمة التشغيل، ينتظر /dev/random كمية معينة من “الضوضاء” لتُولد على الجهاز المضيف قبل إرجاع النتيجة. المكتبة المستخدمة لتوليد الأرقام العشوائية في JVM الخاص بأوراكل تعتمد على /dev/random بشكل افتراضي لمنصات UNIX. على الرغم من أن /dev/random أكثر أمانًا، يُنصح باستخدام /dev/urandom إذا كان تكوين JVM الافتراضي يسبب تأخيرات، أو إضافة أجهزة تولد إنتروبيا لـ /dev/random. <p> خيار جافا التالي يمكن أن يساعد على تجنب التأخيرات وتجاوز إعداد securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| internalFIPSSecurity |  | قيمة منطقية |

### setLicense {#setLicense-java.io.InputStream-}
يفعل المكوّن. تدفق يحتوي على الترخيص. استخدم هذه الطريقة لتحميل الترخيص من تدفق. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
يفعل المكوّن. يحاول العثور على الترخيص في المواقع التالية: 1. مسار صريح. 2. مجلد ملف jar الخاص بالمكوّن. في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على التجميع المستدعي، في مجلد التجميع الرئيسي ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic");
