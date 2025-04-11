---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached-Klasse. Stellt das PKCS7-Objekt dar, das der PKCS7-Spezifikation in Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5 entspricht. Der ursprüngliche signierte Nachrichten-Hash über den Byte-Bereich des Dokuments ist als normales PKCS7 SignedData-Feld integriert. Es dürfen keine Daten im PKCS7 SignedData-Feld kapselt werden.
type: docs
weight: 5190
url: /de/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached-Klasse

Stellt das PKCS#7-Objekt dar, das der PKCS#7-Spezifikation in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5 entspricht. Der ursprüngliche signierte Nachrichten-Hash über den Byte-Bereich des Dokuments ist als normales PKCS#7 SignedData-Feld integriert. Es dürfen keine Daten im PKCS#7 SignedData-Feld kapselt werden.

```csharp
public sealed class PKCS7Detached : Signature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Initialisiert eine neue Instanz der `PKCS7Detached`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Der Name der Person oder Behörde, die das Dokument unterschreibt. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Ruft eine Option ab und setzt sie, die angibt, ob die Schätzung der Länge einer Signatur vermieden werden soll. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Ein Array von Paaren von Ganzzahlen (startender Byte-Offset, Länge in Bytes), das den genauen Byte-Bereich für die Hash-Berechnung beschreibt. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informationen, die vom Unterzeichner bereitgestellt werden, um einem Empfänger zu ermöglichen, den Unterzeichner zu kontaktieren, um die Signatur zu überprüfen, z. B. eine Telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Ruft das benutzerdefinierte Erscheinungsbild ab/setzt es. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Der Delegierte für das benutzerdefinierte Signieren des Dokumenten-Hashes. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Der Zeitpunkt der Unterzeichnung. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Ruft die Standardlänge für die Signaturdaten in Bytes ab oder setzt sie. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Der CPU-Hostname oder der physische Standort der Unterzeichnung. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ruft die OCSP-Einstellungen ab/setzt sie. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Der Grund für die Unterzeichnung, wie z. B. (Ich stimme zu, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Erzwingt das Anzeigen/Verstecken von Signatureigenschaften. Falls ShowProperties wahr ist, hat das Signaturfeld ein vordefiniertes Format des Erscheinungsbilds (Strings zur Darstellung): ------------------------------------------- Digital signiert von {Zertifikat-Subjekt} Datum: {signature.Date} Grund: {signature.Reason} Standort: {signature.Location} ------------------------------------------- wobei {X} ein Platzhalter für den X-Wert ist. Außerdem kann die Signatur ein Bild haben, in diesem Fall werden die aufgelisteten Strings über das Bild gelegt. ShowProperties ist standardmäßig wahr. |
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