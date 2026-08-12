---
title: "Clase Aspose::Pdf::Annotations::AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::AnnotationCollection. Clase que representa una colección de anotaciones en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.annotations/annotationcollection/
---
## AnnotationCollection class


Clase que representa una colección de anotaciones.

```cpp
class AnnotationCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Annotation>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<AnnotationSelector\>\&) | Acepta un visitante para procesar la anotación. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&, bool) | Añade la anotación a la colección. Si la página está rotada, el rectángulo de la anotación se recalculará en consecuencia. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&) override | Añade la anotación a la colección. |
| [Clear](./clear/)() override | Elimina todas las anotaciones de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<Annotation\>\&) const override | Comprueba si la anotación especificada pertenece a la colección. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>, int32_t) override | Copia la matriz de anotaciones en la colección. |
| [Delete](./delete/)(int32_t) | Elimina la anotación de la colección por índice. |
| [Delete](./delete/)() | Elimina todas las anotaciones de la colección. |
| [Delete](./delete/)(const System::SharedPtr\<Annotation\>\&) | Elimina la anotación especificada de la colección. |
| [FindByName](./findbyname/)(const System::String\&) | Devuelve la anotación por su nombre. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de anotaciones en la colección. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() | Obtiene un valor que indica si el acceso a [Aspose.Pdf.Annotations.AnnotationCollection](./) está sincronizado (seguro para subprocesos). |
| [get_SyncRoot](./get_syncroot/)() const | Obtiene un objeto que puede usarse para sincronizar el acceso a [Aspose.Pdf.Annotations.AnnotationCollection](./). |
| [GetEnumerator](./getenumerator/)() override | Devuelve enumerador de la colección. |
| [idx_get](./idx_get/)(int32_t) | El índice del elemento a obtener. |
| [Remove](./remove/)(const System::SharedPtr\<Annotation\>\&) override | Elimina la anotación especificada de la colección. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
