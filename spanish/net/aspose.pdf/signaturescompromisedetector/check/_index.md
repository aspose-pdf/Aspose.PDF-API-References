---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: Método SignaturesCompromiseDetector. Verifica las firmas digitales del documento para detectar compromisos
type: docs
weight: 20
url: /es/net/aspose.pdf/signaturescompromisedetector/check/
---
## Método SignaturesCompromiseDetector.Check

Verifica las firmas digitales del documento para detectar compromisos.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | El resultado de la verificación del documento. |

### Valor de Retorno

Verdadero, si no se detecta el compromiso de las firmas.

## Observaciones

El uso de este método para un documento en el que no hay firmas digitales devolverá `True`.

### Véase También

* clase [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* clase [SignaturesCompromiseDetector](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)