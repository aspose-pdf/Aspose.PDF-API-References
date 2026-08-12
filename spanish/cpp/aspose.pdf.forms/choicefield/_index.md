---
title: "Clase Aspose::Pdf::Forms::ChoiceField"
linktitle: "ChoiceField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::ChoiceField. Representa la clase base para campos de elección en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.forms/choicefield/
---
## ChoiceField class


Representa la clase base para campos de selección.

```cpp
class ChoiceField : public Aspose::Pdf::Forms::Field
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddOption](./addoption/)(System::String) | Agrega una nueva opción con el nombre especificado. |
| virtual [AddOption](./addoption/)(System::String, System::String) | Agrega una nueva opción con el valor de exportación y el nombre especificados. |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor de [ChoiceField](./). |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&) | Crea un campo de elección (para Generator) |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor de [ChoiceField](./). |
| virtual [DeleteOption](./deleteoption/)(System::String) | Elimina la opción por su nombre. |
| [get_CommitImmediately](./get_commitimmediately/)() | Obtiene la bandera de confirmar al cambiar la selección. |
| [get_MultiSelect](./get_multiselect/)() | Obtiene la bandera de selección múltiple. |
| virtual [get_Options](./get_options/)() | Obtiene la colección de opciones de elección. |
| virtual [get_Selected](./get_selected/)() | Obtiene el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| virtual [get_SelectedItems](./get_selecteditems/)() | Obtiene la matriz de elementos seleccionados. Para una lista de selección múltiple la matriz contiene más de un elemento. Para una lista de selección única contiene un solo elemento. |
| [get_Value](./get_value/)() override | Obtiene el valor del campo. |
| [set_CommitImmediately](./set_commitimmediately/)(bool) | Establece la bandera de confirmar al cambiar la selección. |
| [set_MultiSelect](./set_multiselect/)(bool) | Establece la bandera de selección múltiple. |
| virtual [set_Selected](./set_selected/)(int32_t) | Establece el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| virtual [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) | Establece la matriz de elementos seleccionados. Para una lista de selección múltiple la matriz contiene más de un elemento. Para una lista de selección única contiene un solo elemento. |
| [set_Value](./set_value/)(System::String) override | Establece el valor del campo. |
## Ver también

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
