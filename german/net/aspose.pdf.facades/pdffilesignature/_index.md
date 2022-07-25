---
title: PdfFileSignature
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse zum Signieren einer PDF-Datei mit einem Zertifikat.
type: docs
weight: 2570
url: /de/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Repräsentiert eine Klasse zum Signieren einer PDF-Datei mit einem Zertifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | Der Konstruktor der PdfFileSignature-Klasse. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Initialisiert neu[`PdfFileSignature`](../pdffilesignature) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Ruft das Flag ab, das bestimmt, ob ein Dokument zertifiziert ist oder nicht. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Ruft das Flag „LTV aktiviert“ ab. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Setzt oder erhält ein grafisches Erscheinungsbild für die Signatur. Der Eigenschaftswert stellt den Namen der Bilddatei dar. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Setzt oder erhält ein grafisches Erscheinungsbild für die Signatur. Der Eigenschaftswert stellt den Bildstream dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Bindet einen PDF-Stream zur Bearbeitung. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Bindet eine PDF-Datei zur Bearbeitung. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Bestätigen Sie das Dokument mit der MDP-Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, dh das Feld darf kein Signaturwörterbuch enthalten. Damit das PDF-Dokument bereits ein Signaturfeld hat, sollten Sie den Platz nicht angeben stempeln Sie die Signatur, die entsprechende Seite und das entsprechende Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Zertifizieren Sie das Dokument mit der MDP-Signatur. Solche Daten wie Signaturgrund, Kontakt und Ort müssen durch entsprechende Eigenschaften des Signaturobjekts sig. bereitgestellt werden. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Schließt die Fassade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Überprüft, ob das PDF eine digitale Signatur hat oder nicht. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Überprüft, ob das PDF Nutzungsrechte hat oder nicht. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Prüft, ob die Signatur das gesamte Dokument abdeckt. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Extrahiert das Bild der Signatur. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Gibt den Zugriffsberechtigungswert des zertifizierten Dokuments nach MDP-Signaturtyp zurück. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Ruft die Namen aller leeren Signaturfelder ab. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Ruft die Kontaktinformationen einer Signatur ab. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Ruft die Datumszeit der Signatur ab. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Ruft den Speicherort einer Signatur ab. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Ruft den Grund einer Signatur ab. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Ruft die Revision einer Signatur ab. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Ruft den Namen der Person oder Organisation ab, die das PDF-Dokument signiert. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Ruft die Namen aller nicht leeren Signaturen ab. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Ruft die Gesamtrevision ab. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Entfernen Sie die Signatur gemäß dem Namen der Signatur. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Entfernt die Signatur entsprechend dem Namen der Signatur. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Entfernt den Nutzungsrechteeintrag. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Speichert das Ergebnis-PDF im Stream. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Speichert das Ergebnis-PDF in einer Datei. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Zertifikatsdatei und Passwort für Signaturroutine festlegen. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Unterschreiben Sie das Dokument mit der gegebenen Unterschriftsart, die in das bereits vorhandene Unterschriftsfeld eingefügt wird. Vor dem Unterschreiben muss das Unterschriftsfeld leer sein, dh das Feld darf kein Unterschriftswörterbuch enthalten. Damit das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie den Ort nicht angeben Um die Signatur zu stempeln, werden die entsprechende Seite und das entsprechende Rechteck aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter SigName). Solche Daten wie Signaturgrund, Kontakt und Ort müssen von entsprechenden Eigenschaften des Signaturobjekts sig. bereitgestellt werden. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Unterschreiben Sie das Dokument mit der angegebenen Typsignatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Unterschreiben Sie das Dokument mit der gegebenen Unterschriftsart, die in das bereits vorhandene Unterschriftsfeld eingefügt wird. Vor dem Unterschreiben muss das Unterschriftsfeld leer sein, dh das Feld darf kein Unterschriftswörterbuch enthalten. Damit das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie den Ort nicht angeben Um die Signatur zu stempeln, werden die entsprechende Seite und das entsprechende Rechteck aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Unterschreiben Sie das PDF-Dokument. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Unterschreiben Sie das Dokument mit der angegebenen Typsignatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signieren Sie das Dokument mit der angegebenen Signatur, die in das bereits angezeigte Signaturfeld eingefügt wird. Vor dem Signieren des PDF-Dokuments sollte bereits ein Signaturfeld vorhanden sein. Die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe SigName-Parameter) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Prüft die Gültigkeit einer Signatur. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Prüft die Gültigkeit einer Signatur. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
