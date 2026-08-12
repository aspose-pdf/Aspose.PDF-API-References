---
title: "Aspose::Pdf::Comparison::SideBySideComparisonOptions class"
linktitle: "SideBySideComparisonOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySideComparisonOptions class. Representa una clase de opciones para comparar documentos con salida lado a lado en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class


Representa una clase de opciones para comparar documentos con salida lado a lado.

```cpp
class SideBySideComparisonOptions : public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AdditionalChangeMarks](./get_additionalchangemarks/)() const | Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero están presentes en otra página. Si el cambio se sitúa entre palabras, la marca puede no estar posicionada exactamente respecto al carácter de espacio. El valor predeterminado es **false**. |
| [get_ComparisonArea1](./get_comparisonarea1/)() const | Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede establecerse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
| [get_ComparisonArea2](./get_comparisonarea2/)() const | Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede establecerse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
| [get_ComparisonMode](./get_comparisonmode/)() const | Obtiene y establece un modo de comparación. El valor predeterminado es [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [get_DeleteColor](./get_deletecolor/)() const | Obtiene el color utilizado para marcar contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede establecerse junto con [ExcludeTables](../). Esta opción no puede establecerse junto con la opción [ComparisonArea1](../). |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede establecerse junto con [ExcludeTables](../). Esta opción no puede establecerse junto con la opción [ComparisonArea2](../). |
| [get_ExcludeTables](./get_excludetables/)() const | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede establecerse junto con [ComparisonArea1](../) y [ComparisonArea2](../). El valor predeterminado es **false**. |
| [get_InsertColor](./get_insertcolor/)() const | Obtiene el color utilizado para marcar contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación. |
| [set_AdditionalChangeMarks](./set_additionalchangemarks/)(bool) | Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero están presentes en otra página. Si el cambio se sitúa entre palabras, la marca puede no estar posicionada exactamente respecto al carácter de espacio. El valor predeterminado es **false**. |
| [set_ComparisonArea1](./set_comparisonarea1/)(const System::SharedPtr\<Rectangle\>\&) | Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede establecerse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
| [set_ComparisonArea2](./set_comparisonarea2/)(const System::SharedPtr\<Rectangle\>\&) | Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede establecerse junto con las opciones [ExcludeTables](../), [ExcludeAreas1](../) y [ExcludeAreas2](../). |
| [set_ComparisonMode](./set_comparisonmode/)(Aspose::Pdf::Comparison::ComparisonMode) | Obtiene y establece un modo de comparación. El valor predeterminado es [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [set_DeleteColor](./set_deletecolor/)(const System::SharedPtr\<Color\>\&) | Establece el color utilizado para marcar contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede establecerse junto con [ExcludeTables](../). Esta opción no puede establecerse junto con la opción [ComparisonArea1](../). |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede establecerse junto con [ExcludeTables](../). Esta opción no puede establecerse junto con la opción [ComparisonArea2](../). |
| [set_ExcludeTables](./set_excludetables/)(bool) | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede establecerse junto con [ComparisonArea1](../) y [ComparisonArea2](../). El valor predeterminado es **false**. |
| [set_InsertColor](./set_insertcolor/)(const System::SharedPtr\<Color\>\&) | Establece el color utilizado para marcar contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación. |
| [SideBySideComparisonOptions](./sidebysidecomparisonoptions/)() | Crea una instancia de la clase [SideBySideComparisonOptions](./). |
## Ver también

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
