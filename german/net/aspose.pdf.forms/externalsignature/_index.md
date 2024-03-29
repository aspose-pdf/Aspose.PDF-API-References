---
title: ExternalSignature
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt eine getrennte PKCS7Detached-Signatur mit einem X509-Zertifikat2. Es unterstützt USB-Smartcards Token ohne exportierbare private Schlüssel.
type: docs
weight: 2990
url: /de/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

Erstellt eine getrennte PKCS#7Detached-Signatur mit einem X509-Zertifikat2. Es unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel.

```csharp
public class ExternalSignature : Signature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExternalSignature](externalsignature)(X509Certificate2) | Erstellt eine getrennte PKCS#7Detached-Signatur mit einem X509-Zertifikat2. Es unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | Der Name der Person oder Behörde, die das Dokument unterzeichnet. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Ein Array von Ganzzahlenpaaren (Start-Byte-Offset, Länge in Bytes) , das den genauen Byte-Bereich für die Digest-Berechnung beschreiben soll. |
| [Certificate](../../aspose.pdf.forms/externalsignature/certificate) { get; } | Das Zertifikat mit dem privaten Schlüssel. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo) { get; set; } | Vom Unterzeichner bereitgestellte Informationen, damit ein Empfänger den Unterzeichner kontaktieren kann, um die Signatur zu überprüfen, z. B. eine Telefonnummer. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance) { get; set; } | Ruft das benutzerdefinierte Erscheinungsbild ab/legt es fest. |
| [Date](../../aspose.pdf.forms/signature/date) { get; set; } | Zeitpunkt der Unterzeichnung. |
| [Location](../../aspose.pdf.forms/signature/location) { get; set; } | Der CPU-Hostname oder der physische Standort der Signatur. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings) { get; set; } | Ruft OCSP-Einstellungen ab/legt sie fest. |
| [Reason](../../aspose.pdf.forms/signature/reason) { get; set; } | Der Grund für die Unterzeichnung, z. B. (Ich stimme zuРІР‚В¦). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties) { get; set; } | Ein-/Ausblenden von Signatureigenschaften erzwingen. Falls ShowProperties wahr ist, hat das Signaturfeld ein vordefiniertes Darstellungsformat (Zeichenfolgen zur Darstellung): --------------------- ---------------------- Digital signiert von {Zertifikatssubjekt} Datum: {signature.Date} Grund: {signature.Reason} Ort: { Signatur.Location} --------------------------------------------x000d_ wo {X} ist ein Platzhalter für den X-Wert. Auch die Signatur kann ein Bild haben, in diesem Fall werden die aufgelisteten Zeichenfolgen über dem Bild platziert. ShowProperties ist standardmäßig wahr. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings) { get; set; } | Ruft/legt Zeitstempeleinstellungen ab. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv) { get; set; } | Holt/setzt LTV-Validierungs-Flag. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Verify](../../aspose.pdf.forms/signature/verify)() | Überprüfen Sie das Dokument bezüglich dieser Signatur und geben Sie wahr zurück, wenn das Dokument gültig oder andernfalls falsch ist. |

### Siehe auch

* class [Signature](../signature)
* namensraum [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
