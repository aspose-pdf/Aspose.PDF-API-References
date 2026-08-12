---
title: "Aspose::Pdf::PageNumberStamp class"
linktitle: "PageNumberStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageNumberStamp class. Representa el sello de número de página y se usa para numerar páginas en C++."
type: docs
weight: 14200
url: /es/cpp/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class


Representa el sello de número de página y se usa para numerar las páginas.

```cpp
class PageNumberStamp : public Aspose::Pdf::TextStamp
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Format](./get_format/)() const | Valor de cadena para estampar números de página. El valor debe incluir el carácter '#' que se reemplaza por el número de página durante el proceso de estampado. |
| [get_NumberingStyle](./get_numberingstyle/)() const | Estilo de numeración que usa este sello. |
| [get_StartingNumber](./get_startingnumber/)() const | Obtiene el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor. |
| [PageNumberStamp](./pagenumberstamp/)(const System::String\&) | Inicializa una nueva instancia de la clase [PageNumberStamp](./). |
| [PageNumberStamp](./pagenumberstamp/)() | Inicializa una nueva instancia de la clase [PageNumberStamp](./). El formato se establece en "#". |
| [PageNumberStamp](./pagenumberstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Crea [PageNumberStamp](./) mediante texto formateado. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Agrega número de página. |
| [set_Format](./set_format/)(const System::String\&) | Valor de cadena para estampar números de página. El valor debe incluir el carácter '#' que se reemplaza por el número de página durante el proceso de estampado. |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Estilo de numeración que usa este sello. |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Establece el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor. |
## Ver también

* Class [TextStamp](../textstamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
