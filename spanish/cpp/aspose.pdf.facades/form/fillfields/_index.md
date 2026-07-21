---
title: "Aspose::Pdf::Facades::Form::FillFields método"
linktitle: "FillFields"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::Form::FillFields método. Rellena los campos de cuadro de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Aviso: Solo se aplica a Cuadro de Texto. Tanto el nombre de los campos como los valores distinguen mayúsculas y minúsculas en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.facades/form/fillfields/
---
## Form::FillFields method


Rellena los campos de cuadro de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Aviso: Solo se aplica al cuadro de [Text](../../../aspose.pdf.text/). Tanto el nombre de los campos como los valores distinguen mayúsculas y minúsculas.

```cpp
bool Aspose::Pdf::Facades::Form::FillFields(const System::ArrayPtr<System::String> &fieldNames, const System::ArrayPtr<System::String> &fieldValues, System::SharedPtr<System::IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldNames | const System::ArrayPtr\<System::String\>\& | Nombres de los campos. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | Nuevos valores de los campos. |
| output | System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se guardará el documento. |

### ReturnValue

verdadero si los campos fueron encontrados y rellenados con éxito.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
