---
title: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class. Representa una clase para generar la representación html de las diferencias de textos. Los saltos de línea eliminados se indican con la marca de párrafo en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class


Representa una clase para generar una representación HTML de las diferencias de textos. Los saltos de línea eliminados se indican con el símbolo de párrafo.

```cpp
class HtmlDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [get_DeleteStyle](./get_deletestyle/)() const | Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_EqualStyle](./get_equalstyle/)() const | Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_InsertStyle](./get_insertstyle/)() const | Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_StrikethroughDeleted](./get_strikethroughdeleted/)() const | Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es **False**. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)() | Crea una instancia de la clase [HtmlDiffOutputGenerator](./). |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Crea una instancia de la clase [HtmlDiffOutputGenerator](./). |
| [set_DeleteStyle](./set_deletestyle/)(const System::String\&) | Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_EqualStyle](./set_equalstyle/)(const System::String\&) | Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_InsertStyle](./set_insertstyle/)(const System::String\&) | Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_StrikethroughDeleted](./set_strikethroughdeleted/)(bool) | Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es **False**. |
## Ver también

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
