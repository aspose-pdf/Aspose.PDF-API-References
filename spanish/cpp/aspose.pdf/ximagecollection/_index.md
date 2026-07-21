---
title: "Clase Aspose::Pdf::XImageCollection"
linktitle: "XImageCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XImageCollection. Clase que representa la colección XImage en C++."
type: docs
weight: 19900
url: /es/cpp/aspose.pdf/ximagecollection/
---
## XImageCollection class


Clase que representa la colección de [XImage](../ximage/).

```cpp
class XImageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Pdf::XImage>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::ImageFilterType) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&, Aspose::Pdf::ImageFilterType) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| [AddWithName](./addwithname/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Agrega una nueva imagen a la lista de [Image](../image/). Este método agrega la imagen como referencia al mismo PdfObject (lo que permite reducir el tamaño del archivo) |
| [Clear](./clear/)() override | Limpia todos los elementos de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) const override | Determina si la colección contiene un valor específico. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::XImage\>\>, int32_t) override | Copia la matriz de imágenes en la colección. |
| [Delete](./delete/)(int32_t) | Elimina el índice de la colección por índice. |
| [Delete](./delete/)(int32_t, Aspose::Pdf::ImageDeleteAction) | Elimina la imagen de la colección por índice realizando la acción especificada por el parámetro action. |
| [Delete](./delete/)(const System::String\&) | Elimina el elemento de la colección por nombre. |
| [Delete](./delete/)(const System::String\&, Aspose::Pdf::ImageDeleteAction) | Elimina el elemento de la colección por nombre. |
| [Delete](./delete/)() | Elimina imágenes de la colección. |
| [get_Count](./get_count/)() const override | Recuento de imágenes en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve true si el objeto está sincronizado. |
| [get_Names](./get_names/)() | Obtiene una matriz de nombres de imágenes. |
| [get_SyncRoot](./get_syncroot/)() const | Devuelve el objeto de sincronización. |
| [GetEnumerator](./getenumerator/)() override | Devuelve enumerador de la colección. |
| [GetImageName](./getimagename/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Devuelve el nombre en la lista de imágenes que es la clave de la imagen proporcionada. |
| [idx_get](./idx_get/)(int32_t) | Obtiene la imagen de la colección por su índice. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene la imagen de la colección por su nombre. |
|  | [Remove](./remove/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) override | Elimina el elemento de la colección, lanza NotImplementedException |
. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Reemplazar la imagen en la colección con otra imagen. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) | Reemplazar la imagen en la colección con otra imagen. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Reemplazar la imagen en la colección con otra imagen. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
