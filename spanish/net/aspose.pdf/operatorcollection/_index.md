---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.OperatorCollection. La clase representa una colección de operadores
type: docs
weight: 7080
url: /es/net/aspose.pdf/operatorcollection/
---
## Clase OperatorCollection

La clase representa una colección de operadores

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Obtiene el conteo de operadores en la colección. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indica si la colección está limitada a la extracción de texto rápida. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Obtiene el operador por su índice. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Acepta el objeto visitante IOperatorSelector para procesar operadores. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Agrega a la colección todos los operadores de otra colección. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Agrega un nuevo operador a la colección. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Agrega operadores al final de los operadores de contenido. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Cancela la última actualización. Este método puede ser llamado cuando el cambio no debe provocar una actualización de contenido. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Elimina todos los operadores de la lista. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Devuelve verdadero si la colección contiene el operador dado. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copia operadores en la lista de operadores. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Elimina operadores de la colección. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Elimina un operador de la colección. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Elimina operadores de la colección. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Devuelve un enumerador para la colección |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Inserta operadores en la posición dada. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Inserta un operador en la colección. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Inserta operadores en la posición dada. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Elimina un operador de la colección. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Reemplaza operadores en la colección con otros operadores. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. Marca todos los operadores como "cambiados" si el parámetro invalidate es verdadero. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Suprime la actualización de los datos de contenido. El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Devuelve la representación de texto del operador. |

### Ver También

* clase [BaseOperatorCollection](../baseoperatorcollection/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)