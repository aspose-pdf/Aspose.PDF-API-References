---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS1-Klasse. Stellt das Signaturobjekt gemäß dem PKCS1-Standard dar. RSA-Verschlüsselungsalgorithmus und SHA1-Hash-Methode werden zum Signieren verwendet.
type: docs
weight: 5170
url: /de/net/aspose.pdf.forms/pkcs1/
---
## PKCS1-Klasse

Stellt das Signaturobjekt gemäß dem PKCS#1-Standard dar. RSA-Verschlüsselungsalgorithmus und SHA-1-Hash-Methode werden zum Signieren verwendet.

```csharp
public sealed class PKCS1 : Signature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | Initialisiert eine neue Instanz der `PKCS1`-Klasse. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | Initialisiert eine neue Instanz der `PKCS1`-Klasse. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | Initialisiert eine neue Instanz der `PKCS1`-Klasse. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | Initialisiert eine neue Instanz der `PKCS1`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Der Name der Person oder Behörde, die das Dokument signiert. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Ruft eine Option ab und setzt sie, die angibt, ob die Schätzung der Länge einer Signatur vermieden werden soll. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Ein Array von Paaren von Ganzzahlen (startender Byte-Offset, Länge in Bytes), das den genauen Byte-Bereich für die Hash-Berechnung beschreibt. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informationen, die vom Unterzeichner bereitgestellt werden, um einem Empfänger zu ermöglichen, den Unterzeichner zu kontaktieren, um die Signatur zu überprüfen, z.B. eine Telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Ruft das benutzerdefinierte Erscheinungsbild ab/setzt es. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Der Delegierte für das benutzerdefinierte Signieren des Dokumenten-Hashes. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Der Zeitpunkt der Signatur. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Ruft die Standardlänge für die Signaturdaten in Bytes ab oder setzt sie. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Der CPU-Hostname oder der physische Standort der Signatur. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ruft die OCSP-Einstellungen ab/setzt sie. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Der Grund für die Signatur, wie z.B. (Ich stimme zu, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Erzwingt das Anzeigen/Verstecken der Signatureigenschaften. Falls ShowProperties wahr ist, hat das Signaturfeld ein vordefiniertes Format des Erscheinungsbilds (Strings zur Darstellung): ------------------------------------------- Digital signiert von {Zertifikatssubjekt} Datum: {signature.Date} Grund: {signature.Reason} Standort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X-Wert ist. Außerdem kann die Signatur ein Bild haben, in diesem Fall werden die aufgelisteten Strings über das Bild gelegt. ShowProperties ist standardmäßig wahr. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Ruft die Zeitstempel-Einstellungen ab/setzt sie. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ruft das LTV-Validierungsflag ab/setzt es. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Ruft Informationen über den in der Signatur verwendeten Signaturalgorithmus ab. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Überprüft das Dokument bezüglich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Überprüft das Dokument bezüglich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist, andernfalls false. |

### Siehe auch

* Klasse [Signature](../signature/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)