---
title: "Clase Aspose::Pdf::Forms::RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::RadioButtonField. Clase que representa un campo de botón de opción en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class


Clase que representa el campo de botón de opción.

```cpp
class RadioButtonField : public Aspose::Pdf::Forms::ChoiceField
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<RadioButtonOptionField\>\&) | Agrega un nuevo campo de opción al campo RadioButton. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Agregar a la opción de botón de radio con rectángulo especificado. |
| [AddOption](./addoption/)(System::String) override | Agregar opción al botón de radio. |
|  | [get_NoToggleToOff](./get_notoggletooff/)() | Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si **true** |

, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si **false**

, al hacer clic en el botón seleccionado lo deselecciona, dejando ningún botón seleccionado. |
| [get_Options](./get_options/)() override | Obtiene la colección de opciones del botón de opción. |
| [get_PageIndex](./get_pageindex/)() override | Obtiene el índice de la página que contiene este campo RadioButton. |
| [get_Selected](./get_selected/)() override | Obtiene el índice del elemento seleccionado. La numeración de los elementos comienza en 1. |
| [get_Style](./get_style/)() | Estilo del cuadro de campo. |
| [get_Value](./get_value/)() override | Obtiene el valor del campo. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Constructor para RadiouttonField. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Document\>\&) | Constructor para [RadioButtonField](./). |
|  | [set_NoToggleToOff](./set_notoggletooff/)(bool) | Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si **true** |

, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si **false**

, al hacer clic en el botón seleccionado lo deselecciona, dejando ningún botón seleccionado. |
| [set_Selected](./set_selected/)(int32_t) override | Establece el índice del elemento seleccionado. La numeración de los elementos comienza en 1. |
| [set_Style](./set_style/)(BoxStyle) | Estilo del cuadro de campo. |
| [set_Value](./set_value/)(System::String) override | Establece el valor del campo. |
| [SetPosition](./setposition/)(System::SharedPtr\<Point\>) override | Mueve todos los subelementos del botón de opción a las posiciones especificadas en la página. |
## Ver también

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
