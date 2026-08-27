---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSignature-metod. Extraherar signaturens enskilda X.509-certifikat"
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extraherar signaturens enda X.509‑certifikat.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| certifikat | X509Certificate2& | Om ett certifikat hittades returneras ett X.509‑enkelt certifikatobjekt; annars null. |

### Returvärde

Sant certifikat hittades.

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extraherar signaturens enda X.509-certifikat som en ström.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| ström | Stream& | Om ett certifikat hittades returneras en X.509‑enkelt certifikatström; annars null. |

### Returvärde

Sant certifikat hittades.

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


