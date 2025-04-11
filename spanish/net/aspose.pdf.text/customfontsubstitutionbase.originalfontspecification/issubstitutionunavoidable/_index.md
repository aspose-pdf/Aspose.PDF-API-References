---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Propiedad OriginalFontSpecification. Obtiene un valor que indica que la sustitución es inevitable
type: docs
weight: 20
url: /es/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Propiedad CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Obtiene un valor que indica que la sustitución es inevitable.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Observaciones

Devuelve verdadero en caso de que se solicitara la sustitución debido a la ausencia de la fuente original o en caso de que la fuente original no pueda ser utilizada en el contexto de alguna tarea. En caso de que el usuario ignore la bandera y no sustituya la fuente, se realiza el procedimiento de sustitución de fuente predeterminado. Pero proporciona la oportunidad al usuario de alternar el procedimiento estándar de sustitución de fuentes y establecer una mejor fuente para el sistema. Devuelve falso en caso de que la fuente original esté presente, sea válida, pero se permite al usuario sustituirla.

### Véase también

* clase [OriginalFontSpecification](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../../)