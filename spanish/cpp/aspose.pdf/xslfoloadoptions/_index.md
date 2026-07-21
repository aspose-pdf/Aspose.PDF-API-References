---
title: "Clase Aspose::Pdf::XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XslFoLoadOptions. Representa opciones para cargar/importar un archivo XSL-FO en un documento pdf en C++."
type: docs
weight: 21200
url: /es/cpp/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class


Representa opciones para cargar/importar un archivo XSL-FO en un documento pdf.

```cpp
class XslFoLoadOptions : public Aspose::Pdf::XmlLoadOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ParsingErrorsHandlingTypes](./parsingerrorshandlingtypes/) | El documento XSLFO fuente puede contener errores de formato. Este enum enumera las posibles estrategias para manejar dichos errores de formato. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | La ruta/base URL desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado. |
| [get_XsltArgumentList](./get_xsltargumentlist/)() const | XsltArgumentList para insertar valores en los parámetros xls existentes. |
| [set_BasePath](./set_basepath/)(const System::String\&) | La ruta/base URL desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado. |
| [set_XsltArgumentList](./set_xsltargumentlist/)(const System::SharedPtr\<System::Xml::Xsl::XsltArgumentList\>\&) | XsltArgumentList para insertar valores en los parámetros xls existentes. |
| [XslFoLoadOptions](./xslfoloadoptions/)() | Crea un objeto [XslFoLoadOptions](./) sin datos xsl. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::String\&) | Crea un objeto [XslFoLoadOptions](./) con datos xsl. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::SharedPtr\<System::IO::Stream\>\&) | Crea un objeto [XslFoLoadOptions](./) con datos xsl. |
## Ver también

* Class [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
