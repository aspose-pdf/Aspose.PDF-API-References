---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор CertificateEncryptionOptions. Создаёт экземпляр класса CertificateEncryptionOptions"
type: docs
weight: 10
url: /ru/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

Создаёт экземпляр класса [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificatePath | String | Путь к файлу публичного сертификата. |
| pfxPath | String | Путь к файлу архива p12. |
| pfxPassword | String | Пароль к файлу архива p12. |

### См. также

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

Создаёт экземпляр класса [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificatePath | String | Путь к файлу публичного сертификата. |
| storeName | StoreName | Имя хранилища для получения сертификата закрытого ключа. |
| storeLocation | StoreLocation | Расположение хранилища для получения сертификата закрытого ключа. |

### См. также

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

Создаёт экземпляр класса [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Публичный сертификат. |
| storeName | StoreName | Имя хранилища для получения сертификата закрытого ключа. |
| storeLocation | StoreLocation | Расположение хранилища для получения сертификата закрытого ключа. |

### См. также

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

Создаёт экземпляр класса [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Публичный сертификат. |
| pfxPath | String | Путь к файлу архива p12. |
| pfxPassword | String | Пароль к файлу архива p12. |

### См. также

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


