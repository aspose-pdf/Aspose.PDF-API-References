---
title: Class RootElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Structure.RootElement. Elemento de estructura raíz
type: docs
weight: 10170
url: /es/net/aspose.pdf.structure/rootelement/
---
## Clase RootElement

Elemento de estructura raíz.

```csharp
public class RootElement : Element
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Opcional; PDF 1.4) Texto que es un reemplazo exacto para el elemento de estructura y sus hijos. Este texto de reemplazo (que debe aplicarse a la menor cantidad de contenido posible) es útil al extraer el contenido del documento en apoyo a la accesibilidad para usuarios con discapacidades u otros propósitos. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Opcional) Una descripción alternativa del elemento de estructura y sus hijos en un formato legible por humanos, que es útil al extraer el contenido del documento en apoyo a la accesibilidad para usuarios con discapacidades u otros propósitos. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Obtiene la colección de elementos hijos. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Opcional; PDF 1.5) La forma expandida de una abreviatura. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Opcional; PDF 1.4) Un idioma que especifica el idioma natural para todo el texto en el elemento de estructura, excepto donde se anula por especificaciones de idioma para elementos de estructura anidados o contenido marcado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Eliminar elemento. |

### Ver También

* clase [Element](../element/)
* espacio de nombres [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* ensamblaje [Aspose.PDF](../../)