---
title: "ExternalSignature.ExternalSignature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор ExternalSignature. Создаёт откреплённую подпись PKCS7, используя X509Certificate2. Поддерживает USB‑смарткарты‑токены без экспортируемых закрытых ключей"
type: docs
weight: 10
url: /ru/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Создает отдельную подпись PKCS#7 `(detached)` с использованием X509Certificate2. Поддерживает USB‑смарткарты, токены без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | X509Certificate2 | Сертификат с закрытым ключом. |

## Примечания

Алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата.

### См. также

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Создает отдельную подпись PKCS#7 `(detached)` с использованием X509Certificate2. Поддерживает USB‑смарткарты, токены без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | X509Certificate2 | Сертификат с закрытым ключом. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

### См. также

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Создаёт отдельную подпись PKCS#7 с использованием X509Certificate2. Поддерживает USB‑смарт‑карты, токены без экспортируемых закрытых ключей.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | X509Certificate2 | Сертификат с закрытым ключом. |
| откреплённый | Boolean | True, если подпись должна быть откреплённой, иначе false. |

## Примечания

Если откреплённая подпись установлена в false, алгоритм хеширования всегда будет `SHA1`. В противном случае алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата (см. Auto).

### См. также

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Создает подпись PKCS#7 с использованием X509Certificate2 в виде строки base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | String | X509Certificate2 в виде строки base64. |
| откреплённый | Boolean | True, если подпись должна быть откреплённой, иначе false. |

## Примечания

Если откреплённая подпись установлена в false, алгоритм хеширования всегда будет `SHA1`. В противном случае алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата (см. Auto).

### См. также

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Создает подпись PKCS#7 `(detached)` с использованием X509Certificate2 в виде строки base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | String | X509Certificate2 в виде строки base64. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

### См. также

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


