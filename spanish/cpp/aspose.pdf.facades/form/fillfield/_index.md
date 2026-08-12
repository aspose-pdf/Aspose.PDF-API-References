---
title: "Aspose::Pdf::Facades::Form::FillField method"
linktitle: "FillField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::Form::FillField method. Rellena el campo de casilla de verificación con un valor booleano. Aviso: Solo se aplica a Check Box. Tenga en cuenta que Aspose.Pdf.Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo \"Form.Subform.CheckBoxField\" debe especificar el nombre completo y no \"CheckBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/form/fillfield/
---
## Form::FillField(const System::String\&, bool) method


Rellena el campo de casilla de verificación con un valor booleano. Aviso: Solo se aplica a Check Box. Tenga en cuenta que [Aspose.Pdf.Facades](../../) admite solo nombres de campo completos y no funciona con nombres parciales, en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField" debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, bool beChecked)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre del campo a rellenar. |
| beChecked | bool | Una bandera booleana: true significa marcar la casilla, mientras que false significa desmarcarla. |

### ReturnValue

true si el campo fue encontrado y rellenado con éxito.

## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::ArrayPtr\<System::String\>\&) method


Rellena un campo con múltiples selecciones. Nota: solo para el campo de Caja de Lista AcroForm.

```cpp
void Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::ArrayPtr<System::String> &fieldValues)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre de campo totalmente calificado. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | Una matriz de cadenas que contiene varios elementos para seleccionar. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&) method


Rellena el campo con un valor válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, se deben conocer todos los nombres de los campos y sus valores válidos correspondientes. Tanto el nombre del campo como los valores son sensibles a mayúsculas y minúsculas. Tenga en cuenta que [Aspose.Pdf.Facades](../../) solo admite nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo \"Form.Subform.TextField\" debe especificar el nombre completo y no \"TextField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &fieldValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre del campo a rellenar. |
| fieldValue | const System::String\& | El valor del campo que debe ser un valor válido para algunos campos. |

### ReturnValue

true si el campo se encuentra y se rellena con éxito.

## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&, bool) method


Rellena el campo con el valor especificado.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &value, bool fitFontSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | Nombre del campo |
| valor | const System::String\& | Nuevo valor del campo |
| fitFontSize | bool | Si es true, el tamaño de fuente en los cuadros de edición se ajustará. |

### ReturnValue

true si el campo fue encontrado y rellenado con éxito.

## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, int32_t) method


Rellena el campo de caja de radio con un índice válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, solo se debe conocer el nombre del campo. El valor puede especificarse por su índice. Aviso: Solo se aplica a campos de Radio Box, Combo Box y List Box. Tenga en cuenta que [Aspose.Pdf.Facades](../../) solo admite nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo \"Form.Subform.ListBoxField\" debe especificar el nombre completo y no \"ListBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, int32_t index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | Nombre del campo a rellenar. |
| índice | int32_t | Índice del elemento elegido. |

### ReturnValue

true si el campo fue encontrado y rellenado con éxito.
## Observaciones




```cpp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```cpp
//cómo buscar un campo por su nombre parcial:
Form form = new Form("input.pdf", "output.pdf");
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
