---
title: "Clase Aspose::Pdf::Forms::CheckboxField"
linktitle: "CheckboxField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::CheckboxField. Clase que representa un campo de casilla de verificación en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class


Clase que representa un campo de casilla de verificación.

```cpp
class CheckboxField : public Aspose::Pdf::Forms::Field
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddOption](./addoption/)(const System::String\&) | Agrega una nueva casilla de verificación a un grupo de casillas, en el que como máximo una de las casillas puede estar marcada en cualquier momento. La nueva casilla se agrega al final del grupo. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Agrega una nueva casilla de verificación a un grupo de casillas, en el que como máximo una de las casillas puede estar marcada en cualquier momento. |
| [AddOption](./addoption/)(const System::String\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Agrega una nueva casilla de verificación a un grupo de casillas, en el que como máximo una de las casillas puede estar marcada en cualquier momento. |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor de la clase [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor de la clase [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)() | Crear una instancia de [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&) | Constructor para usar con Generator. |
| [Clone](./clone/)() override | Clonar la casilla de verificación. |
| [get_ActiveState](./get_activestate/)() override | Obtiene el estado actual de apariencia de la anotación. |
| [get_AllowedStates](./get_allowedstates/)() | Devuelve la lista de estados permitidos. |
| [get_Checked](./get_checked/)() | Obtiene el estado de la casilla de verificación. |
| [get_ExportValue](./get_exportvalue/)() | Obtiene el valor de exportación del campo CheckBox. |
| [get_Style](./get_style/)() | Obtiene el estilo de la casilla de verificación. |
| [get_Value](./get_value/)() override | Obtiene el valor del campo de casilla de verificación. |
| [set_ActiveState](./set_activestate/)(System::String) override | Establece el estado de apariencia de la anotación actual. |
| [set_Checked](./set_checked/)(bool) | Establece el estado de la casilla de verificación. |
| [set_ExportValue](./set_exportvalue/)(const System::String\&) | Establece el valor de exportación del campo CheckBox. |
| [set_Style](./set_style/)(BoxStyle) | Establece el estilo del cuadro de verificación. |
| [set_Value](./set_value/)(System::String) override | Establece el valor del campo de casilla de verificación. |
## Ver también

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
