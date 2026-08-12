---
title: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator class"
linktitle: "MarkdownDiffOutputGenerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator class. Representa una clase para generar la representación markdown de las diferencias de texto. Debido a la sintaxis markdown, no es posible mostrar cambios en los caracteres de espacio en blanco. La selección de cambios implica agregar caracteres de espacio en blanco alrededor del formato, de lo contrario el visor markdown no mostrará correctamente el texto. Los saltos de línea eliminados se indican con el signo - de marca de párrafo en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class


Representa una clase para generar una representación markdown de las diferencias de textos. Debido a la sintaxis markdown, no es posible mostrar cambios en los caracteres de espacio en blanco. La selección de cambios implica añadir caracteres de espacio en blanco alrededor del formato, de lo contrario el visor markdown no mostrará correctamente el texto. Los saltos de línea eliminados se indican con el signo - de párrafo.

```cpp
class MarkdownDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                    public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [MarkdownDiffOutputGenerator](./markdowndiffoutputgenerator/)() | Crea una instancia de la clase [MarkdownDiffOutputGenerator](./). |
## Ver también

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
