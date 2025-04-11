---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature-konstruktorn. Skapar en fristående PKCS7-fristående signatur med hjälp av en X509Certificate2. Den stöder usb-smartkortstokens utan exportabla privata nycklar
type: docs
weight: 10
url: /sv/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Skapar en fristående PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2. Den stöder usb-smartkort, tokens utan exportabla privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate2 | Certifikatet med den privata nyckeln. |

## Anmärkningar

Digest-algoritmen kommer automatiskt att väljas baserat på certifikatets nyckeldatat.

### Se Även

* klass [ExternalSignature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Skapar en fristående PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2. Den stöder usb-smartkort, tokens utan exportabla privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate2 | Certifikatet med den privata nyckeln. |
| digestHashAlgorithm | DigestHashAlgorithm | Digest-algoritmen för att signera ett dokument. |

### Se Även

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* klass [ExternalSignature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Skapar en fristående PKCS#7 signatur med hjälp av en X509Certificate2. Den stöder usb-smartkort, tokens utan exportabla privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate2 | Certifikatet med den privata nyckeln. |
| detached | Boolean | Sant om signaturen ska vara fristående, annars falskt. |

## Anmärkningar

För fristående inställt på falskt kommer digest-algoritmen alltid att vara `SHA1`. Annars kommer digest-algoritmen automatiskt att väljas baserat på certifikatets nyckeldatat (se Auto).

### Se Även

* klass [ExternalSignature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Skapar en PKCS#7 signatur med hjälp av en X509Certificate2 som base64-sträng.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | String | X509Certificate2 som base64-sträng. |
| detached | Boolean | Sant om signaturen ska vara fristående, annars falskt. |

## Anmärkningar

För fristående inställt på falskt kommer digest-algoritmen alltid att vara `SHA1`. Annars kommer digest-algoritmen automatiskt att väljas baserat på certifikatets nyckeldatat (se Auto).

### Se Även

* klass [ExternalSignature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Skapar en PKCS#7 `(detached)` signatur med hjälp av en X509Certificate2 som base64-sträng.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | String | X509Certificate2 som base64-sträng. |
| digestHashAlgorithm | DigestHashAlgorithm | Digest-algoritmen för att signera ett dokument. |

### Se Även

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* klass [ExternalSignature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)