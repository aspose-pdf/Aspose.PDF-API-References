---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Signatures.SignaturesCoverage. Representa el enum para el nivel de cobertura proporcionado por las firmas digitales en un documento
type: docs
weight: 10110
url: /es/net/aspose.pdf.signatures/signaturescoverage/
---
## Enumeración SignaturesCoverage

Representa el enum para el nivel de cobertura proporcionado por las firmas digitales en un documento.

```csharp
public enum SignaturesCoverage
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Undefined | `0` | Indica que el estado de la cobertura de las firmas digitales en el documento es indefinido. Este valor se utiliza típicamente cuando una o más firmas en el documento están comprometidas o no se pueden verificar, lo que impide una evaluación definitiva de la cobertura de firmas del documento. |
| EntirelySigned | `1` | Indica que el documento está completamente cubierto por firmas digitales. Este valor significa que todas las partes requeridas del documento han sido firmadas y ninguna firma está comprometida. |
| PartiallySigned | `2` | Indica que el documento está parcialmente firmado, lo que significa que algunas, pero no todas, de su contenido están cubiertas por firmas digitales. Este valor se utiliza cuando ciertas partes del documento permanecen sin firmar o están excluidas de la cobertura de firmas. |

### Ver También

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)