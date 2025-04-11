---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Конструктор ExternalSignature. Создает отделенную подпись PKCS7 с использованием X509Certificate2. Поддерживает токены usb смарт-карт без экспортируемых закрытых ключей
type: docs
weight: 10
url: /ru/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Создает отделенную подпись PKCS#7 `(detached)` с использованием X509Certificate2. Поддерживает токены usb смарт-карт без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate2 | Сертификат с закрытым ключом. |

## Примечания

Алгоритм дайджеста будет автоматически выбран на основе данных ключа сертификата.

### См. также

* класс [ExternalSignature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Создает отделенную подпись PKCS#7 `(detached)` с использованием X509Certificate2. Поддерживает токены usb смарт-карт без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate2 | Сертификат с закрытым ключом. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм дайджеста для подписи документа. |

### См. также

* перечисление [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* класс [ExternalSignature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Создает отделенную подпись PKCS#7 с использованием X509Certificate2. Поддерживает токены usb смарт-карт без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | X509Certificate2 | Сертификат с закрытым ключом. |
| detached | Boolean | True, если подпись должна быть отделенной, иначе false. |

## Примечания

Для detached, установленного в false, алгоритм дайджеста всегда будет `SHA1`. В противном случае алгоритм дайджеста будет автоматически выбран на основе данных ключа сертификата (см. Auto).

### См. также

* класс [ExternalSignature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Создает подпись PKCS#7 с использованием X509Certificate2 в виде строки base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | String | X509Certificate2 в виде строки base64. |
| detached | Boolean | True, если подпись должна быть отделенной, иначе false. |

## Примечания

Для detached, установленного в false, алгоритм дайджеста всегда будет `SHA1`. В противном случае алгоритм дайджеста будет автоматически выбран на основе данных ключа сертификата (см. Auto).

### См. также

* класс [ExternalSignature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Создает отделенную подпись PKCS#7 `(detached)` с использованием X509Certificate2 в виде строки base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | String | X509Certificate2 в виде строки base64. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм дайджеста для подписи документа. |

### См. также

* перечисление [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* класс [ExternalSignature](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)