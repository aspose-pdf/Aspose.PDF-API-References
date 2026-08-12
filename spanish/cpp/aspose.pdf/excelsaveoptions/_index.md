---
title: "Clase Aspose::Pdf::ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::ExcelSaveOptions. Opciones de guardado para exportar al formato Excel en C++."
type: docs
weight: 4700
url: /es/cpp/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class


Opciones de guardado para exportar al formato Excel.

```cpp
class ExcelSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ExcelFormat](./excelformat/) | Permite especificar el formato de archivo .xlsx, .xls/xml o csv. El valor predeterminado es XLSX;. |
## Métodos

| Método | Descripción |
| --- | --- |
| [ExcelSaveOptions](./excelsaveoptions/)() | Constructor. |
| [get_Format](./get_format/)() const | Formato de salida. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Establezca true si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es false; significa que no se insertará la columna en blanco. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Establezca true si necesita minimizar el número de hojas de cálculo en el libro resultante. El valor predeterminado es false; significa que cada página PDF se guardará como una hoja separada. |
| [get_UniformWorksheets](./get_uniformworksheets/)() const | Establezca true para usar una división uniforme de columnas en todo el documento. El valor predeterminado es false; significa que la división de columnas será independiente para cada página. |
| [set_Format](./set_format/)(ExcelSaveOptions::ExcelFormat) | Formato de salida. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Establezca true si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es false; significa que no se insertará la columna en blanco. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Establezca true si necesita minimizar el número de hojas de cálculo en el libro resultante. El valor predeterminado es false; significa que cada página PDF se guardará como una hoja separada. |
| [set_UniformWorksheets](./set_uniformworksheets/)(bool) | Establezca true para usar una división uniforme de columnas en todo el documento. El valor predeterminado es false; significa que la división de columnas será independiente para cada página. |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
