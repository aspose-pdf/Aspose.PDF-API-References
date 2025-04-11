---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature-Klasse. Stellt eine Klasse dar, um eine PDF-Datei mit einem Zertifikat zu signieren
type: docs
weight: 4560
url: /de/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature-Klasse

Stellt eine Klasse dar, um eine PDF-Datei mit einem Zertifikat zu signieren.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Der Konstruktor der PdfFileSignature-Klasse. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initialisiert ein neues `PdfFileSignature`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Gibt das Flag zurück, das bestimmt, ob ein Dokument zertifiziert ist oder nicht. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Gibt das LTV-aktivierte Flag zurück. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Setzt oder gibt ein grafisches Erscheinungsbild für die Signatur zurück. Der Wert der Eigenschaft stellt den Dateinamen des Bildes dar. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Setzt oder gibt ein grafisches Erscheinungsbild für die Signatur zurück. Der Wert der Eigenschaft stellt den Bildstream dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Bindet einen PDF-Stream zur Bearbeitung. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Bindet eine PDF-Datei zur Bearbeitung. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Zertifiziert das Dokument mit der MDP-Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor der Signatur muss das Signaturfeld leer sein, d.h. das Feld darf kein Signaturwörterbuch enthalten. Da das PDF-Dokument bereits ein Signaturfeld hat, sollten Sie den Platz zum Stempeln der Signatur nicht angeben, die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe sigName-Parameter). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Zertifiziert das Dokument mit der MDP-Signatur. Solche Daten wie Signaturgrund, Kontakt und Standort müssen durch die entsprechenden Eigenschaften des Signaturobjekts sig bereitgestellt werden. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Schließt die Fassade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Überprüft, ob die PDF eine digitale Signatur hat oder nicht. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Überprüft, ob die PDF Nutzungsrechte hat oder nicht. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Überprüft, ob die Signatur das gesamte Dokument abdeckt. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extrahiert das Bild der Signatur. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Gibt den Wert der Zugriffsberechtigungen des zertifizierten Dokuments nach dem MDP-Signaturtyp zurück. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Gibt die Namen aller leeren Signaturfelder zurück. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Gibt die Kontaktinformationen einer Signatur zurück. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Gibt das Datum und die Uhrzeit der Signatur zurück. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Gibt den Standort einer Signatur zurück. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Gibt den Grund einer Signatur zurück. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Gibt die Revision einer Signatur zurück. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Gibt die Namen aller nicht leeren Signaturen zurück. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Ruft Informationen über alle Signaturalgorithmen ab, die im PDF-Dokument vorhanden sind. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Gibt den Namen der Person oder Organisation zurück, die das PDF-Dokument signiert. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Gibt die gesamte Revision zurück. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Entfernt die Signatur gemäß dem Namen der Signatur. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Entfernt die Signatur gemäß dem Namen der Signatur. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Entfernt alle Signaturen. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Entfernt den Eintrag für die Nutzungsrechte. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Speichert das Ergebnis-PDF im Stream. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Speichert das Ergebnis-PDF in einer Datei. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Setzt die Zertifikatdatei und das Passwort für die Signierroutine. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Signiert das Dokument mit dem angegebenen Typ der Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor der Signatur muss das Signaturfeld leer sein, d.h. das Feld darf kein Signaturwörterbuch enthalten. Da das PDF-Dokument bereits ein Signaturfeld hat, sollten Sie den Platz zum Stempeln der Signatur nicht angeben, die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe SigName-Parameter). Solche Daten wie Signaturgrund, Kontakt und Standort müssen durch die entsprechenden Eigenschaften des Signaturobjekts sig bereitgestellt werden. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Signiert das Dokument mit dem angegebenen Typ der Signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Signiert das Dokument mit dem angegebenen Typ der Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor der Signatur muss das Signaturfeld leer sein, d.h. das Feld darf kein Signaturwörterbuch enthalten. Da das PDF-Dokument bereits ein Signaturfeld hat, sollten Sie den Platz zum Stempeln der Signatur nicht angeben, die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe SigName-Parameter). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Erstellt eine Signatur im PDF-Dokument. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signiert das Dokument mit dem angegebenen Typ der Signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signiert das Dokument mit dem angegebenen Typ der Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor der Signatur sollte das PDF-Dokument bereits ein Signaturfeld haben, die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe SigName-Parameter). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Überprüft die Gültigkeit einer Signatur. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Überprüft die Gültigkeit einer Signatur. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)