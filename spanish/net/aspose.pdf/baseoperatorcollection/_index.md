---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.BaseOperatorCollection. Representa la clase base para la colección de operadores
type: docs
weight: 2830
url: /es/net/aspose.pdf/baseoperatorcollection/
---
## Clase BaseOperatorCollection

Representa la clase base para la colección de operadores.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Obtiene el conteo de operadores en la colección. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indica si la colección está limitada a la extracción de texto rápida. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Devuelve verdadero si la colección es de solo lectura. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Obtiene el operador por su índice. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Agrega un nuevo operador a la colección. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Cancela la última actualización. Este método puede ser llamado cuando el cambio no debe provocar una actualización de contenidos. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Limpia la colección. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Verifica si el operador existe en la colección. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copia operadores en la lista de operadores. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Devuelve un enumerador para la colección. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Inserta un operador en la colección. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Elimina un operador de la colección. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Reanuda la actualización del documento. Actualiza el flujo de contenidos en caso de que haya cambios pendientes. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Suprime la actualización de los datos de contenido. El flujo de contenidos no se actualiza hasta que se llama a ResumeUpdate. |

### Ver También

* clase [Operator](../operator/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)