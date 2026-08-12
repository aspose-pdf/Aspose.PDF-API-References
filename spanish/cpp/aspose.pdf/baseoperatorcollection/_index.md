---
title: "Aspose::Pdf::BaseOperatorCollection class"
linktitle: "BaseOperatorCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::BaseOperatorCollection class. Representa la clase base para la colección de operadores en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class


Representa la clase base para la colección de operadores.

```cpp
class BaseOperatorCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Operator>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<Operator\>\&) | Agrega un nuevo operador a la colección. |
| virtual [CancelUpdate](./cancelupdate/)() | Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización de contenido. |
| virtual [Clear](./clear/)() | Limpia la colección. |
| virtual [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const | Comprueba si el operador existe en la colección. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) | Copia los operadores en la lista de operadores. |
| virtual [get_Count](./get_count/)() const | Obtiene el recuento de operadores en la colección. |
| virtual [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const | Indica si la colección está limitada a la extracción rápida de texto. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Devuelve verdadero si la colección es de solo lectura. |
| virtual [GetEnumerator](./getenumerator/)() | Devuelve el enumerador para la colección. |
| virtual [idx_get](./idx_get/)(int32_t) | Obtiene el operador por su índice. |
| virtual [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) | Obtiene el operador por su índice. |
| virtual [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) | Inserta el operador en la colección. |
| virtual [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) | Elimina el operador de la colección. |
| virtual [ResumeUpdate](./resumeupdate/)() | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| virtual [SuppressUpdate](./suppressupdate/)() | Suprime la actualización de datos de contenido. El flujo de contenido no se actualiza hasta que se llame a ResumeUpdate. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
