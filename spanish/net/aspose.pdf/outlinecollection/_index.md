---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.OutlineCollection. Representa la jerarquía del esquema del documento
type: docs
weight: 8000
url: /es/net/aspose.pdf/outlinecollection/
---
## Clase OutlineCollection

Representa la jerarquía del esquema del documento.

```csharp
public sealed class OutlineCollection : Outlines
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Conteo de elementos de la colección. Por favor, no confundir con VisibleCount: VisibleCount obtiene el número de elementos de esquema visibles en todos los niveles. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Obtiene un elemento de esquema que representa el primer elemento de nivel superior en el esquema. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Obtiene un valor que indica si el acceso a esta colección está sincronizado (seguro para hilos). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Obtiene un elemento de esquema de la colección por índice. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Obtiene un elemento de esquema que representa el último elemento de nivel superior en el esquema. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso a esta colección. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | El conteo es la suma del número de elementos de esquema descendientes visibles en todos los niveles. Nota: por favor, no confundir con Count, que es el número de elementos en la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Agrega un elemento de esquema a la colección. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Limpia todos los elementos de la colección. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Verifica si la colección contiene el elemento dado. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copia los elementos de esquema a un System.Array, comenzando en un índice particular de System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Elimina todos los elementos de esquema del esquema del documento. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Elimina el elemento de esquema con el título especificado del esquema del documento. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Elimina un elemento por índice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Siempre lanza NotImplementedException |

### Ver También

* clase [Outlines](../outlines/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)