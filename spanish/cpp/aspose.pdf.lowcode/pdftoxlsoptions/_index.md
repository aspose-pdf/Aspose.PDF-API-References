---
title: "Clase Aspose::Pdf::LowCode::PdfToXlsOptions"
linktitle: "PdfToXlsOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::PdfToXlsOptions. Representa opciones del convertidor de PDF a XLSX para el complemento XlsConverter en C++."
type: docs
weight: 6600
url: /es/cpp/aspose.pdf.lowcode/pdftoxlsoptions/
---
## PdfToXlsOptions class


Representa opciones del convertidor de PDF a XLSX para el complemento [XlsConverter](../xlsconverter/).

```cpp
class PdfToXlsOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ExcelFormat](./excelformat/) | Permite especificar el formato de archivo .xlsx, .xls/xml o csv. El valor predeterminado es XLSX. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Format](./get_format/)() const | Formato de salida. |
| [get_InsertBlankColumnAtFirst](./get_insertblankcolumnatfirst/)() const | Establezca true si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es false; significa que no se insertará la columna en blanco. |
| [get_MinimizeTheNumberOfWorksheets](./get_minimizethenumberofworksheets/)() const | Establezca true si necesita minimizar el número de hojas de cálculo en el libro resultante. El valor predeterminado es false; significa que cada página PDF se guardará como una hoja separada. |
| [get_OperationName](./get_operationname/)() override | Obtiene el nombre de la operación. |
| [PdfToXlsOptions](./pdftoxlsoptions/)() | Inicializa una nueva instancia del objeto [PdfToXlsOptions](./) con opciones predeterminadas. |
| [set_Format](./set_format/)(PdfToXlsOptions::ExcelFormat) | Formato de salida. |
| [set_InsertBlankColumnAtFirst](./set_insertblankcolumnatfirst/)(bool) | Establezca true si necesita insertar una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es false; significa que no se insertará la columna en blanco. |
| [set_MinimizeTheNumberOfWorksheets](./set_minimizethenumberofworksheets/)(bool) | Establezca true si necesita minimizar el número de hojas de cálculo en el libro resultante. El valor predeterminado es false; significa que cada página PDF se guardará como una hoja separada. |
## Ver también

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
