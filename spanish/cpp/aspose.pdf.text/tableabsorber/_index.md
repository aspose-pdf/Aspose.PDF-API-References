---
title: "Clase Aspose::Pdf::Text::TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TableAbsorber. Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección TableAbsorber::TableList en C++."
type: docs
weight: 3300
url: /es/cpp/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class


Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda mediante la colección [TableAbsorber::TableList](../).

```cpp
class TableAbsorber : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_TableList](./get_tablelist/)() | Devuelve un IList de solo lectura que contiene las tablas encontradas. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Obtiene opciones de búsqueda de texto. |
| [get_UseFlowEngine](./get_useflowengine/)() const |  |
| [Remove](./remove/)(const System::SharedPtr\<AbsorbedTable\>\&) | Elimina un [AbsorbedTable](../absorbedtable/) de la página. |
| [Replace](./replace/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<AbsorbedTable\>\&, const System::SharedPtr\<Table\>\&) | Reemplaza un [AbsorbedTable](../absorbedtable/) con [Table](../../aspose.pdf/table/) en la página. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Establece opciones de búsqueda de texto. |
| [set_UseFlowEngine](./set_useflowengine/)(bool) |  |
| [TableAbsorber](./tableabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de [TableAbsorber](./) con opciones de búsqueda de texto. |
| [TableAbsorber](./tableabsorber/)() | Inicializa una nueva instancia de [TableAbsorber](./). |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extrae tablas en la página especificada. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Extrae tablas en el documento especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
