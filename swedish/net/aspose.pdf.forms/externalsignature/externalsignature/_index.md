---
title: "ExternalSignature.ExternalSignature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ExternalSignature konstruktor. Skapar en fristående PKCS7‑signatur med en X509Certificate2. Den stöder USB‑smartkort‑token utan exporterbara privata nycklar"
type: docs
weight: 10
url: /sv/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Skapar en fristående PKCS#7 `(detached)`-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certifikat | X509Certificate2 | Certifikatet med den privata nyckeln. |

## Anmärkningar

Digest‑algoritmen kommer att väljas automatiskt baserat på certifikatnyckelns data.

### Se även

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Skapar en fristående PKCS#7 `(detached)`-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certifikat | X509Certificate2 | Certifikatet med den privata nyckeln. |
| digestHashAlgorithm | DigestHashAlgorithm | Digest‑algoritmen för att signera ett dokument. |

### Se även

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certifikat | X509Certificate2 | Certifikatet med den privata nyckeln. |
| frånkopplad | Boolean | Sant om signaturen ska vara fristående, annars falskt. |

## Anmärkningar

Om fristående är satt till falskt kommer digest‑algoritmen alltid att vara `SHA1`. Annars kommer digest‑algoritmen att automatiskt väljas baserat på certifikatnyckeldata (se Auto).

### Se även

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Skapar en PKCS#7-signatur med en X509Certificate2 som base64-sträng.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | String | X509Certificate2 som base64‑sträng. |
| frånkopplad | Boolean | Sant om signaturen ska vara fristående, annars falskt. |

## Anmärkningar

Om fristående är satt till falskt kommer digest‑algoritmen alltid att vara `SHA1`. Annars kommer digest‑algoritmen att automatiskt väljas baserat på certifikatnyckeldata (se Auto).

### Se även

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Skapar en PKCS#7 `(detached)`-signatur med en X509Certificate2 som base64-sträng.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | String | X509Certificate2 som base64‑sträng. |
| digestHashAlgorithm | DigestHashAlgorithm | Digest‑algoritmen för att signera ett dokument. |

### Se även

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


