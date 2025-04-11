---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature-Konstruktor. Erstellt eine abgetrennte PKCS7-Abgeschnittene Signatur unter Verwendung eines X509Certificate2. Es unterstützt USB-Smartcard-Token ohne exportierbare private Schlüssel
type: docs
weight: 10
url: /de/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Erstellt eine abgetrennte PKCS#7 `(detached)` Signatur unter Verwendung eines X509Certificate2. Es unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate2 | Das Zertifikat mit dem privaten Schlüssel. |

## Bemerkungen

Der Digest-Algorithmus wird automatisch basierend auf den Zertifikatsschlüsseldaten ausgewählt.

### Siehe auch

* Klasse [ExternalSignature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Erstellt eine abgetrennte PKCS#7 `(detached)` Signatur unter Verwendung eines X509Certificate2. Es unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate2 | Das Zertifikat mit dem privaten Schlüssel. |
| digestHashAlgorithm | DigestHashAlgorithm | Der Digest-Algorithmus zum Signieren eines Dokuments. |

### Siehe auch

* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Klasse [ExternalSignature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Erstellt eine abgetrennte PKCS#7 Signatur unter Verwendung eines X509Certificate2. Es unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate2 | Das Zertifikat mit dem privaten Schlüssel. |
| detached | Boolean | Wahr, wenn die Signatur abgetrennt sein soll, andernfalls falsch. |

## Bemerkungen

Für abgetrennt auf falsch wird der Digest-Algorithmus immer `SHA1` sein. Andernfalls wird der Digest-Algorithmus automatisch basierend auf den Zertifikatsschlüsseldaten ausgewählt (siehe Auto).

### Siehe auch

* Klasse [ExternalSignature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Erstellt eine PKCS#7 Signatur unter Verwendung eines X509Certificate2 als Base64-String.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| base64 | String | X509Certificate2 als Base64-String. |
| detached | Boolean | Wahr, wenn die Signatur abgetrennt sein soll, andernfalls falsch. |

## Bemerkungen

Für abgetrennt auf falsch wird der Digest-Algorithmus immer `SHA1` sein. Andernfalls wird der Digest-Algorithmus automatisch basierend auf den Zertifikatsschlüsseldaten ausgewählt (siehe Auto).

### Siehe auch

* Klasse [ExternalSignature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Erstellt eine PKCS#7 `(detached)` Signatur unter Verwendung eines X509Certificate2 als Base64-String.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| base64 | String | X509Certificate2 als Base64-String. |
| digestHashAlgorithm | DigestHashAlgorithm | Der Digest-Algorithmus zum Signieren eines Dokuments. |

### Siehe auch

* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Klasse [ExternalSignature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)