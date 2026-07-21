---
title: "Aspose::Pdf::Comparison::ComparisonOptions class"
linktitle: "ComparisonOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::ComparisonOptions class. Representa una clase de opciones de comparación de documentos PDF en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class


Representa una clase de opciones de comparación de documentos PDF.

```cpp
class ComparisonOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ComparisonOptions](./comparisonoptions/)() | Crea una instancia de la clase [ComparisonOptions](./). |
| [get_EditOperationsOrder](./get_editoperationsorder/)() const | Obtiene y establece el orden de las operaciones de edición. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Obtenga y establezca las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con [ExcludeTables](../). Esta opción no puede configurarse junto con la opción [ExtractionArea](../). |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Obtenga y establezca las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con [ExcludeTables](../). Esta opción no puede configurarse junto con la opción [ExtractionArea](../). |
| [get_ExcludeTables](./get_excludetables/)() const | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción [ExtractionArea](../). El valor predeterminado es **false**. |
| [get_ExtractionArea](./get_extractionarea/)() const | Obtenga y establezca el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
| [set_EditOperationsOrder](./set_editoperationsorder/)(Aspose::Pdf::Comparison::EditOperationsOrder) | Obtiene y establece el orden de las operaciones de edición. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Obtenga y establezca las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con [ExcludeTables](../). Esta opción no puede configurarse junto con la opción [ExtractionArea](../). |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Obtenga y establezca las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con [ExcludeTables](../). Esta opción no puede configurarse junto con la opción [ExtractionArea](../). |
| [set_ExcludeTables](./set_excludetables/)(bool) | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción [ExtractionArea](../). El valor predeterminado es **false**. |
| [set_ExtractionArea](./set_extractionarea/)(const System::SharedPtr\<Rectangle\>\&) | Obtenga y establezca el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
