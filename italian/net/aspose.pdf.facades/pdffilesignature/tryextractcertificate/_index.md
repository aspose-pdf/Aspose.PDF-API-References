---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSignature. Estrae il singolo certificato X.509 della firma"
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Estrae il singolo certificato X.509 della firma.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| certificato | X509Certificate2& | Se è stato trovato un certificato, restituisce l'oggetto certificato X.509 singolo; altrimenti, null. |

### Valore di ritorno

È stato trovato un certificato valido.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Estrae il singolo certificato X.509 della firma come stream.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| stream | Stream& | Se è stato trovato un certificato, restituisce lo stream del certificato X.509 singolo; altrimenti, null. |

### Valore di ritorno

È stato trovato un certificato valido.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


