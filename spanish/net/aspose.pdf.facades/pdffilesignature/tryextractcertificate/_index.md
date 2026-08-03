---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método PdfFileSignature. Extrae el certificado único X.509 de la firma"
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extrae el certificado único X.509 de la firma.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | SignatureName | El nombre de la firma. |
| certificate | X509Certificate2& | Si se encontró un certificado, devuelve el objeto de certificado único X.509; de lo contrario, null. |

### Valor devuelto

Se encontró un certificado verdadero.

### Ver también

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extrae el certificado único X.509 de la firma como un flujo.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | SignatureName | El nombre de la firma. |
| stream | Stream& | Si se encontró un certificado, devuelve el flujo del certificado único X.509; de lo contrario, null. |

### Valor devuelto

Se encontró un certificado verdadero.

### Ver también

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


