---
title: "Clase System::Text::RegularExpressions::CaptureCollection"
linktitle: "CaptureCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::RegularExpressions::CaptureCollection. Lista de capturas realizadas por un solo grupo de captura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.text.regularexpressions/capturecollection/
---
## CaptureCollection class


Lista de capturas realizadas por un solo grupo de captura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const CapturePtr\&) override | Desactiva la enmienda de la colección. |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Método de servicio para agregar una captura a la colección. |
| [Clear](./clear/)() override | Desactiva la limpieza de la colección. |
| [get_Count](./get_count/)() const override | Obtiene el número de capturas. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Marca la colección como solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() const | Marca la colección como no sincronizada. |
| [idx_get](./idx_get/)(int) const override | [Capture](../capture/) accesor. |
| [operator[]](./operator[]/)(int) | [Capture](../capture/) accesor. |
| [operator[]](./operator[]/)(int) const | [Capture](../capture/) accesor. |
| [Remove](./remove/)(const CapturePtr\&) override | Desactiva la enmienda de la colección. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Base](./base/) | [Base](./base/) tipo. |
## Ver también

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
