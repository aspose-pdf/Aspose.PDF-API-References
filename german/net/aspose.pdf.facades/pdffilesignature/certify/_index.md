---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-Methode. Zertifizieren Sie das Dokument mit der MDP-Signatur. Solche Daten wie Signaturgrund, Kontakt und Standort müssen durch die entsprechenden Eigenschaften des Signature-Objekts sig bereitgestellt werden.
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Zertifizieren Sie das Dokument mit der MDP-Signatur. Solche Daten wie Signaturgrund, Kontakt und Standort müssen durch die entsprechenden Eigenschaften des Signature-Objekts sig bereitgestellt werden.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seite, auf der die Signatur erfolgt. |
| SigReason | String | Der Grund der Signatur. |
| SigContact | String | Der Kontakt der Signatur. |
| SigLocation | String | Der Standort der Signatur. |
| visible | Boolean | Die Sichtbarkeit der Signatur. |
| annotRect | Rectangle | Das Rechteck der Signatur. |
| docMdpSignature | DocMDPSignature | Der Dokument-MDP-Typ der Signatur. |

### Siehe auch

* Klasse [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Zertifizieren Sie das Dokument mit der MDP-Signatur, die im bereits vorhandenen Signaturfeld platziert ist. Vor der Unterzeichnung muss das Signaturfeld leer sein, d.h. das Feld darf kein Signaturwörterbuch enthalten. Da das PDF-Dokument bereits ein Signaturfeld hat, sollten Sie nicht den Platz zum Stempeln der Signatur, die entsprechende Seite und das Rechteck angeben, diese werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sigName | String | Der Name des Signaturfeldes. |
| docMdpSignature | DocMDPSignature | Der Typ der Signatur, könnte [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) und [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) sein. |

### Siehe auch

* Klasse [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)