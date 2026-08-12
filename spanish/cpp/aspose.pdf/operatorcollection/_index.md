---
title: "Aspose::Pdf::OperatorCollection class"
linktitle: "OperatorCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::OperatorCollection. La clase representa una colección de operadores en C++."
type: docs
weight: 12100
url: /es/cpp/aspose.pdf/operatorcollection/
---
## OperatorCollection class


Clase que representa una colección de operadores.

```cpp
class OperatorCollection : public Aspose::Pdf::BaseOperatorCollection,
                           public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Acepta el objeto visitante [IOperatorSelector](../ioperatorselector/) para procesar operadores. |
| [Add](./add/)(const System::SharedPtr\<Operator\>\&) override | Agrega un nuevo operador a la colección. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Añade operadores al final de los operadores de contenido. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) | Añade a la colección todos los operadores de otra colección. |
| [CancelUpdate](./cancelupdate/)() override | Cancela la última actualización. Este método puede llamarse cuando el cambio no debe generar una actualización de contenido. |
| [Clear](./clear/)() override | Elimina todos los operadores de la lista. |
| [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const override | Devuelve true si la colección contiene el operador dado. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) override | Copia los operadores en la lista de operadores. |
| [Delete](./delete/)(int32_t) | Elimina el operador de la colección. |
| [Delete](./delete/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Elimina los operadores de la colección. |
| [Delete](./delete/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Elimina los operadores de la colección. |
| [Dispose](./dispose/)() override | Ejecuta tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de operadores en la colección. |
| [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const override | Indica si la colección está limitada a la extracción rápida de texto. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene un valor que indica si la colección es de solo lectura. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador para la colección. |
| [idx_get](./idx_get/)(int32_t) override | Obtiene el operador por su índice. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) override | Obtiene el operador por su índice. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) override | Inserta el operador en la colección. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Inserta operadores en la posición indicada. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Inserta operadores en la posición indicada. |
| [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) override | Elimina el operador de la colección. |
| [Replace](./replace/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>\&) | Reemplaza los operadores en la colección con otros operadores. |
| [ResumeUpdate](./resumeupdate/)(bool) | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. Marca todos los operadores como "cambiado" si el parámetro invalidate es true. |
| [ResumeUpdate](./resumeupdate/)() override | Reanuda la actualización del documento. Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| [SuppressUpdate](./suppressupdate/)() override | Suprime la actualización de datos de contenido. El flujo de contenido no se actualiza hasta que se llame a ResumeUpdate. |
| [ToString](./tostring/)() const override | Devuelve la representación textual del operador. |
## Ver también

* Class [BaseOperatorCollection](../baseoperatorcollection/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
