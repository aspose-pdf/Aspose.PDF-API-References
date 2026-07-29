---
title: "Document.Encrypt"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. تشفر المستند"
type: docs
weight: 640
url: /ar/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

يشفر المستند.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| permissions | Permissions | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | خوارزمية تشفير، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) للحصول على التفاصيل. |
| publicCertificates | IList`1 | الشهادات العامة المستخدمة للتشفير — واحدة لكل مستلم. |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

يشفر المستند.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privileges | DocumentPrivilege | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| customHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

يشفر المستند.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| permissions | Permissions | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| customHandler | ICustomSecurityHandler | معالج الأمان المخصص. |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

يشفر المستند.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privileges | DocumentPrivilege | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | خوارزمية تشفير، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) للحصول على التفاصيل. |
| usePdf20 | Boolean | دعم للمراجعة 6 (الامتداد 8). |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

يشفر المستند.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| permissions | Permissions | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | خوارزمية تشفير، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) للحصول على التفاصيل. |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

يشفر المستند.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| permissions | Permissions | أذونات Document، انظر [`Permissions`](../permissions/) للحصول على التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | خوارزمية تشفير، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) للحصول على التفاصيل. |
| usePdf20 | Boolean | دعم للمراجعة 6 (الامتداد 8). |

## ملاحظات

هذه الطريقة تُعد للتشفير. لتشفير مستند، تحتاج إلى استدعاء طريقة Save لحفظه.

### انظر أيضًا

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


