---
title: "Aspose::Pdf::Forms::ListBoxField clase"
linktitle: "ListBoxField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::ListBoxField clase. La clase representa el campo ListBox en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.forms/listboxfield/
---
## ListBoxField class


Clase que representa el campo ListBox.

```cpp
class ListBoxField : public Aspose::Pdf::Forms::ChoiceField
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_TopIndex](./get_topindex/)() | Obtiene el índice del elemento visible superior de la lista. |
| [ListBoxField](./listboxfield/)() | Constructor para [ListBoxField](./) que se usará en Generator. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea un nuevo campo ListBox. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor para el campo ListBox. |
| [set_Selected](./set_selected/)(int32_t) override | Establece el índice del elemento seleccionado. Los elementos están numerados a partir de 1. |
| [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) override | Establece la matriz de los elementos seleccionados en la lista de selección múltiple. Para una lista de selección única devuelve una matriz con un solo elemento. |
| [set_TopIndex](./set_topindex/)(int32_t) | Establece el índice del elemento visible superior de la lista. |
## Ver también

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
