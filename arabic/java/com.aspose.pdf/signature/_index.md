---
title: "Signature"
linktitle: "Signature"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة مجردة تمثل كائن التوقيع في مستند pdf. التواقيع هي حقول ذات قيم كائنات التوقيع، الأخيرة تحتوي على بيانات تُستخدم للتحقق منها."
type: docs
weight: 4490
url: /ar/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

فئة مجردة تمثل كائن التوقيع في مستند PDF. التوقيعات هي حقول ذات قيم كائنات التوقيع، وتحتوي الأخيرة على بيانات تُستخدم للتحقق من صحة المستند.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Signature](#Signature--) | يُنشئ مثيلاً جديدًا للفئة {@code Signature}. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | يُنشئ مثيلاً جديدًا للفئة {@code Signature}. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | يُنشئ مثيلاً جديدًا للفئة {@code Signature}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | المدمر الذي يغلق التدفقات المؤقتة (إن لزم الأمر). |
| [getAuthority](#getAuthority--) | اسم الشخص أو السلطة التي توقع المستند. |
| [getByteRange](#getByteRange--) | احصل على مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت البداية، الطول بالبايت) التي تصف النطاق الدقيق للبايت لحساب الملخص. |
| [getContactInfo](#getContactInfo--) | احصل على المعلومات التي يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم هاتف. |
| [getCustomAppearance](#getCustomAppearance--) | يحصل/يضبط المظهر المخصص. |
| [getCustomSign](#getCustomSign--) | المندوب لتجزئة مخصصة وتوقيع المستند (بيتا). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | المندوب لتوقيع تجزئة المستند مخصصًا (بيتا). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | يحصل على وقت التوقيع. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | يحصل أو يضبط الطول الافتراضي لبيانات التوقيع بالبايت. هذا تقدير لطول التوقيع بالبايت. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) إذا تم ضبط المعامل {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}). القيمة الافتراضية هي 3000. |
| [getImageInternal](#getImageInternal--) | يحصل على تدفق الصورة. للاستخدام الداخلي فقط |
| [getLocation](#getLocation--) | يحصل على اسم مضيف وحدة المعالجة المركزية أو الموقع الفيزيائي للتوقيع. |
| [getOcspSettings](#getOcspSettings--) | يحصل/يضبط إعدادات ocsp. |
| [getReason](#getReason--) | يحصل على سبب التوقيع، مثل (I agreed!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | يسترجع المعلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [getSignatureReferences](#getSignatureReferences--) | احصل على Signature References |
| [getTimestampSettings](#getTimestampSettings--) | يحصل على إعدادات الطابع الزمني. |
| [getUseLtv](#getUseLtv--) | يحصل/يضبط علم التحقق ltv. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | يحصل ويضبط خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع. يتجنب تقدير طول التوقيع قبل توقيع المستند. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) وعبر {@code ExternalSignature}. إذا كان {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) يُعيد توقيعًا أطول من {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), فسيتم رمي {@code SignatureLengthMismatchException}. القيمة الافتراضية هي {@code false}. |
| [isShowProperties](#isShowProperties--) | فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties true يكون حقل التوقيع له تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية): ------------------------------------------- موقع رقمياً بواسطة {certificate subject} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو العنصر النائب لقيمة X. يمكن أن يحتوي التوقيع أيضًا على صورة، وفي هذه الحالة تُوضع السلاسل المذكورة فوق الصورة. ShowProperties تكون true بشكل افتراضي. |
| [setAuthority](#setAuthority-java.lang.String-) | يضبط اسم الشخص أو السلطة التي توقع المستند. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | يحصل ويضبط خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع. يتجنب تقدير طول التوقيع قبل توقيع المستند. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) وعبر {@code ExternalSignature}. إذا كان {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) يُعيد توقيعًا أطول من {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), فسيتم رمي {@code SignatureLengthMismatchException}. القيمة الافتراضية هي {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | يضبط المعلومات التي يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم هاتف. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | يحصل/يضبط المظهر المخصص. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | المندوب لتجزئة مخصصة وتوقيع المستند (بيتا). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | المندوب لتوقيع تجزئة المستند مخصصًا (بيتا). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | يضبط وقت التوقيع. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | يحصل أو يضبط الطول الافتراضي لبيانات التوقيع بالبايت. هذا تقدير لطول التوقيع بالبايت. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) إذا تم ضبط المعامل {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}). القيمة الافتراضية هي 3000. |
| [setImage](#setImage-java.io.InputStream-) | يضبط تدفق الصورة. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | يضبط اسم مضيف وحدة المعالجة المركزية أو الموقع الفيزيائي للتوقيع. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | يحصل/يضبط إعدادات ocsp. |
| [setReason](#setReason-java.lang.String-) | يضبط سبب التوقيع، مثل (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties true يكون حقل التوقيع له تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية): ------------------------------------------- موقع رقمياً بواسطة {certificate subject} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو العنصر النائب لقيمة X. يمكن أن يحتوي التوقيع أيضًا على صورة، وفي هذه الحالة تُوضع السلاسل المذكورة فوق الصورة. ShowProperties تكون true بشكل افتراضي. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | يضبط إعدادات الطابع الزمني. |
| [setUseLtv](#setUseLtv-boolean-) | يحصل/يضبط علم التحقق ltv. |
| [verify](#verify--) | تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false. |

### Signature {#Signature--}
```
public Signature()
```

يُنشئ مثيلاً جديدًا للفئة {@code Signature}.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
يُنشئ مثيلاً جديدًا للفئة {@code Signature}.

### Signature {#Signature-java.lang.String-java.lang.String-}
يُنشئ مثيلاً جديدًا للفئة {@code Signature}.

### close {#close--}
```
public void close()
```

المدمر الذي يغلق التدفقات المؤقتة (إن لزم الأمر).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

اسم الشخص أو السلطة التي توقع المستند.

**Returns:**
قيمة سلسلة

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

احصل على مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت البداية، الطول بالبايت) التي تصف النطاق الدقيق للبايت لحساب الملخص.

**Returns:**
مصفوفة من قيم int

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

احصل على المعلومات التي يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم هاتف.

**Returns:**
قيمة سلسلة

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

يحصل/يضبط المظهر المخصص.

**Returns:**
مثيل SignatureCustomAppearance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

المندوب لتجزئة مخصصة وتوقيع المستند (بيتا). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
مثيل SignHash

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

المندوب لتوقيع تجزئة المستند مخصصًا (بيتا). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
مثيل SignHash

### getDate {#getDate--}
```
public Date getDate()
```

يحصل على وقت التوقيع.

**Returns:**
قيمة Date

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

يحصل أو يضبط الطول الافتراضي لبيانات التوقيع بالبايت. هذا تقدير لطول التوقيع بالبايت. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) إذا تم ضبط المعامل {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}). القيمة الافتراضية هي 3000.

**Returns:**
قيمة int

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

يحصل على تدفق الصورة. للاستخدام الداخلي فقط

**Returns:**
كائن Stream

### getLocation {#getLocation--}
```
public String getLocation()
```

يحصل على اسم مضيف وحدة المعالجة المركزية أو الموقع الفيزيائي للتوقيع.

**Returns:**
قيمة سلسلة

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

يحصل/يضبط إعدادات ocsp.

**Returns:**
مثيل OcspSettings

### getReason {#getReason--}
```
public String getReason()
```

يحصل على سبب التوقيع، مثل (I agreed!, Pip B.).

**Returns:**
قيمة سلسلة

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

يسترجع المعلومات حول خوارزمية التوقيع المستخدمة في التوقيع.

**Returns:**
مثيل من { SignatureAlgorithmInfo} يحتوي على تفاصيل حول خوارزمية التوقيع.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

احصل على Signature References

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

يحصل على إعدادات الطابع الزمني.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

يحصل/يضبط علم التحقق ltv.

**Returns:**
قيمة منطقية

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

يحصل ويضبط خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع. يتجنب تقدير طول التوقيع قبل توقيع المستند. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) وعبر {@code ExternalSignature}. إذا كان {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) يُعيد توقيعًا أطول من {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), فسيتم رمي {@code SignatureLengthMismatchException}. القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties true يكون حقل التوقيع له تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية): ------------------------------------------- موقع رقمياً بواسطة {certificate subject} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو العنصر النائب لقيمة X. يمكن أن يحتوي التوقيع أيضًا على صورة، وفي هذه الحالة تُوضع السلاسل المذكورة فوق الصورة. ShowProperties تكون true بشكل افتراضي.

**Returns:**
قيمة منطقية

### setAuthority {#setAuthority-java.lang.String-}
يضبط اسم الشخص أو السلطة التي توقع المستند.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

يحصل ويضبط خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع. يتجنب تقدير طول التوقيع قبل توقيع المستند. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) وعبر {@code ExternalSignature}. إذا كان {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) يُعيد توقيعًا أطول من {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), فسيتم رمي {@code SignatureLengthMismatchException}. القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setContactInfo {#setContactInfo-java.lang.String-}
يضبط المعلومات التي يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم هاتف.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
يحصل/يضبط المظهر المخصص.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
المندوب لتجزئة مخصصة وتوقيع المستند (بيتا). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
المندوب لتوقيع تجزئة المستند مخصصًا (بيتا). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
يضبط وقت التوقيع.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

يحصل أو يضبط الطول الافتراضي لبيانات التوقيع بالبايت. هذا تقدير لطول التوقيع بالبايت. يُستخدم للتوقيع عبر {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) إذا تم ضبط المعامل {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}). القيمة الافتراضية هي 3000.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setImage {#setImage-java.io.InputStream-}
يضبط تدفق الصورة.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
يضبط اسم مضيف وحدة المعالجة المركزية أو الموقع الفيزيائي للتوقيع.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
يحصل/يضبط إعدادات ocsp.

### setReason {#setReason-java.lang.String-}
يضبط سبب التوقيع، مثل (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties true يكون حقل التوقيع له تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية): ------------------------------------------- موقع رقمياً بواسطة {certificate subject} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو العنصر النائب لقيمة X. يمكن أن يحتوي التوقيع أيضًا على صورة، وفي هذه الحالة تُوضع السلاسل المذكورة فوق الصورة. ShowProperties تكون true بشكل افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
يضبط إعدادات الطابع الزمني.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

يحصل/يضبط علم التحقق ltv.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### verify {#verify--}
```
public boolean verify()
```

تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false.

**Returns:**
true إذا كان المستند صالحًا.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false.

**Returns:**
true إذا كان المستند صالحًا.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
تحقق من المستند بخصوص هذا التوقيع وأعد true إذا كان المستند صالحًا وإلا false.

**Returns:**
true إذا كان المستند صالحًا.
