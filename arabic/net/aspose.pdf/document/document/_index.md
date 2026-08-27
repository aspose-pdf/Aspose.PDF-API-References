---
title: "Document.Document"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ Document. تهيئة نسخة جديدة من Document من التدفق الإدخالي"
type: docs
weight: 10
url: /ar/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق يحتوي على مستند pdf. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق يحتوي على مستند pdf. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق الدفق الداخلي قبل الخروج؛ وإلا، لا يتم ذلك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | كائن دفق الإدخال، المستند pdf المقابل محمي بكلمة مرور. |
| password | String | كلمة مرور المستخدم أو المالك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | كائن دفق الإدخال، المستند pdf المقابل محمي بكلمة مرور. |
| certOptions | CertificateEncryptionOptions | خيارات تشفير الشهادة. |

### انظر أيضًا

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق يحتوي على مستند pdf. |
| certOptions | CertificateEncryptionOptions | خيارات تشفير الشهادة. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق التدفق الداخلي قبل الخروج؛ وإلا لا يتم ذلك. |

### انظر أيضًا

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| certOptions | CertificateEncryptionOptions | خيارات تشفير الشهادة. |

### انظر أيضًا

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| certOptions | CertificateEncryptionOptions | خيارات تشفير الشهادة. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق الدفق الداخلي قبل الخروج؛ وإلا، لا يتم ذلك. |

### انظر أيضًا

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | كائن دفق الإدخال، المستند pdf المقابل محمي بكلمة مرور. |
| password | String | كلمة مرور المستخدم أو المالك. |
| customSecurityHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

### انظر أيضًا

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق يحتوي على مستند pdf. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق التدفق الداخلي قبل الخروج؛ وإلا لا يتم ذلك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

تهيئة نسخة جديدة من Document من تدفق *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق يحتوي على مستند pdf. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق التدفق الداخلي قبل الخروج؛ وإلا لا يتم ذلك. |
| customSecurityHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

### انظر أيضًا

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

فقط قم بتهيئة Document باستخدام *filename*. نفس ما هو `Document`.

```csharp
public Document(string filename)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف مستند pdf. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

فقط قم بتهيئة Document باستخدام *filename*. نفس ما هو `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف مستند pdf. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق التدفق الداخلي قبل الخروج؛ وإلا لا يتم ذلك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| password | String | كلمة مرور المستخدم أو المالك. |
| customSecurityHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

### انظر أيضًا

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| password | String | كلمة مرور المستخدم أو المالك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق الدفق الداخلي قبل الخروج؛ وإلا، لا يتم ذلك. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

تهيئ نسخة جديدة من الفئة [`Document`](../) للعمل مع مستند مشفر.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق الدفق الداخلي قبل الخروج؛ وإلا، لا يتم ذلك. |
| customSecurityHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

### انظر أيضًا

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

يُهيئ مستندًا فارغًا.

```csharp
public Document()
```

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

يُهيئ مستندًا فارغًا حسب الإصدار.

```csharp
public Document(PdfVersion version)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الإصدار | PdfVersion | إصدار PDF. |

### انظر أيضًا

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

يفتح مستندًا موجودًا من ملف مع توفير خيارات التحويل الضرورية للحصول على مستند pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | ملف الإدخال للتحويل إلى مستند pdf. |
| options | LoadOptions | يمثل الخصائص لتحويل *filename* إلى مستند pdf. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

يفتح مستندًا موجودًا من تدفق مع توفير التحويل الضروري للحصول على مستند pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| input | Stream | دفق الإدخال للتحويل إلى مستند pdf. |
| options | LoadOptions | يمثل الخصائص لتحويل *input* إلى مستند pdf. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


