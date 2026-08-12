---
title: "Aspose::Pdf::Forms::TextBoxField clase"
linktitle: "TextBoxField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::TextBoxField clase. Clase que representa un campo de cuadro de texto en C++."
type: docs
weight: 2900
url: /es/cpp/aspose.pdf.forms/textboxfield/
---
## TextBoxField class


Clase que representa el campo de cuadro de texto.

```cpp
class TextBoxField : public Aspose::Pdf::Forms::Field
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddBarcode](./addbarcode/)(const System::String\&) | Agrega el código de barras 128 al campo. El valor de [Field](../field/) se cambiará al código y el campo se volverá de solo lectura. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Agrega una imagen a los recursos del campo y la dibuja. |
| [get_ForceCombs](./get_forcecombs/)() | Obtiene la bandera que indica si el campo está dividido en posiciones espaciadas. |
| [get_MaxLen](./get_maxlen/)() | Obtiene la longitud máxima del texto en el campo. |
| [get_Multiline](./get_multiline/)() | Obtiene la bandera multilínea del campo. Si Multiline es verdadero, el campo puede contener múltiples líneas de texto. |
| [get_Scrollable](./get_scrollable/)() | Obtiene la bandera desplazable del campo. Si es verdadero, el campo puede desplazarse. |
| [get_SpellCheck](./get_spellcheck/)() | Obtiene la bandera de corrección ortográfica del campo. Si es verdadero, el campo será revisado ortográficamente. |
| [get_TextVerticalAlignment](./get_textverticalalignment/)() const | Obtiene la alineación vertical del texto para la anotación. |
| [get_Value](./get_value/)() override | Obtiene el valor del campo. |
| [set_ForceCombs](./set_forcecombs/)(bool) | Establece la bandera que indica si el campo está dividido en posiciones espaciadas. |
| [set_MaxLen](./set_maxlen/)(int32_t) | Establece la longitud máxima del texto en el campo. |
| [set_Multiline](./set_multiline/)(bool) | Establece la bandera multilínea del campo. Si Multiline es verdadero, el campo puede contener múltiples líneas de texto. |
| [set_Scrollable](./set_scrollable/)(bool) | Establece la bandera desplazable del campo. Si es verdadero, el campo puede desplazarse. |
| [set_SpellCheck](./set_spellcheck/)(bool) | Establece la bandera de corrección ortográfica del campo. Si es verdadero, el campo será revisado ortográficamente. |
| [set_TextVerticalAlignment](./set_textverticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece la alineación vertical del texto para la anotación. |
| [set_Value](./set_value/)(System::String) override | Establece el valor del campo. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&) | Constructor que debe usarse con Generator. |
| [TextBoxField](./textboxfield/)() | Crear instancia de [TextBoxField](./). |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor del campo TextBox. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Constructor del campo TextBox. |
| [TextBoxField](./textboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor del campo TextBox. |
## Ver también

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
