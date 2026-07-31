---
title: "PdfFileSignature.Certify"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSignature. Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig"
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti tramite le proprietà corrispondenti dell'oggetto Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | La pagina su cui è effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visibile | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| docMdpSignature | DocMDPSignature | Il tipo MDP del documento della firma. |

### Vedi anche

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifica il documento con la firma MDP che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere il dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina corrispondente e Rectangle vengono presi dal campo firma trovato per nome della firma (vedi parametro sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sigName | String | Il nome del campo della firma. |
| docMdpSignature | DocMDPSignature | Il tipo della firma, potrebbe essere [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) e [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Vedi anche

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


