---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Método CustomFontSubstitutionBase. Sustituye la fuente original por otra fuente
type: docs
weight: 20
url: /es/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Método CustomFontSubstitutionBase.TrySubstitute

Sustituye la fuente original por otra fuente.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Especificación de la fuente original. |
| substitutionFont | Font& | Fuente de sustitución. |

### Valor de Retorno

Verdadero en caso de que la sustitución haya sido exitosa.

## Observaciones

La clase CustomFontSubstitutionBase debe ser heredada para implementar la lógica de sustitución de fuentes personalizada. El método TrySubstitute debe ser anulado correctamente: Debe devolver verdadero en caso de que se requiera sustitución. substitutionFont debe ser establecido como un objeto Font válido. Debe devolver falso en caso de que no se requiera sustitución. substitutionFont puede ser establecido como nulo.

### Véase También

* clase [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* clase [Font](../../font/)
* clase [CustomFontSubstitutionBase](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)