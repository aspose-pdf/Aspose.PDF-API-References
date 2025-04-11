---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSignature. Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti dalle corrispondenti proprietà dell'oggetto Signature sig
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti dalle corrispondenti proprietà dell'oggetto Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | La pagina su cui viene effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| docMdpSignature | DocMDPSignature | Il tipo di firma MDP del documento. |

### Vedi Anche

* classe [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifica il documento con la firma MDP che è posizionata nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per apporre la firma, la pagina e il rettangolo corrispondenti vengono presi dal campo di firma che si trova per nome della firma (vedi parametro sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sigName | String | Il nome del campo di firma. |
| docMdpSignature | DocMDPSignature | Il tipo di firma, potrebbe essere [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) e [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Vedi Anche

* classe [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)