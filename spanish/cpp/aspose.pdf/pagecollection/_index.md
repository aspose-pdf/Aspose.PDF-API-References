---
title: "Aspose::Pdf::PageCollection clase"
linktitle: "PageCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageCollection clase. Colección de páginas de documentos PDF en C++."
type: docs
weight: 13200
url: /es/cpp/aspose.pdf/pagecollection/
---
## PageCollection class


[Collection](../collection/) of PDF document pages.

```cpp
class PageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Page>>,
                       public Aspose::Pdf::ISupportsMemoryCleanup
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Annotations::AnnotationSelector\>\&) | Acepta el objeto visitante [AnnotationSelector](../) que proporciona funcionalidad para trabajar con anotaciones. |
| [Accept](./accept/)(const System::SharedPtr\<ImagePlacementAbsorber\>\&) | Acepta el objeto visitante [ImagePlacementAbsorber](../imageplacementabsorber/) que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextFragmentAbsorber\>\&) | Acepta el objeto visitante [TextFragmentAbsorber](../) que proporciona funcionalidad para trabajar con objetos de texto. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextAbsorber\>\&) | Acepta el objeto visitante [TextAbsorber](../) que proporciona funcionalidad para trabajar con objetos de texto. |
| [Add](./add/)() | Agrega una página vacía. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Agrega a la colección todas las páginas de la lista. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Agrega a la colección todas las páginas del arreglo. |
| [BeginUpdate](./beginupdate/)() | Actualiza cuando comienzan los cambios de grupo. Detiene la recalculación de la caché de páginas en cada operación. Recomendamos llamar a los métodos BeginUpdate/EndUpdate dentro de un bloque try-finally. |
| [Clear](./clear/)() override | Limpia la colección de páginas. |
| [Contains](./contains/)(const System::SharedPtr\<Page\>\&) const override | Determina si esta instancia contiene el objeto. |
| [CopyPage](./copypage/)(const System::SharedPtr\<Page\>\&) | Agrega la página a la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Page\>\>, int32_t) override | Copia páginas al documento. |
| [Delete](./delete/)(int32_t) | Elimina la página especificada. |
| [Delete](./delete/)() | Elimina todas las páginas de la colección. |
| [Delete](./delete/)(const System::ArrayPtr\<int32_t\>\&) | Elimina las páginas cuyos números están especificados en el arreglo. |
| [EndUpdate](./endupdate/)() | Actualiza cuando se completan los cambios de grupo. Restaura la recalculación de la caché de páginas en cada operación. Recomendamos llamar a los métodos BeginUpdate/EndUpdate dentro de un bloque try-finally. |
| [Flatten](./flatten/)() | Elimina todos los campos ubicados en las páginas y coloca sus valores en su lugar. |
| [FreeMemory](./freememory/)() override | Borra los datos en caché. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de páginas en el documento. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene el valor que indica si la colección es de solo lectura. Siempre devuelve false. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si el objeto está sincronizado. |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene el objeto de sincronización de la colección. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador de páginas. |
| [idx_get](./idx_get/)(int32_t) | Obtiene la página por índice. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Page\>\&) const | Devuelve el índice de la página especificada. |
| [Insert](./insert/)(int32_t) | Inserta una página vacía en la colección en la posición especificada. Si el documento ya contiene páginas con tamaños variados, se seleccionará el tamaño de la página que ocurre con mayor frecuencia. En caso de que solo haya dos páginas diferentes, se usará el tamaño de la primera página. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Page\>\&) | Inserta la página en la colección de páginas en el lugar especificado. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Inserta páginas de la colección en el documento. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Inserta páginas del arreglo en el documento. |
|  | [Remove](./remove/)(const System::SharedPtr\<Page\>\&) override | Elimina el elemento especificado, lanza NotSupportedException |
. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
