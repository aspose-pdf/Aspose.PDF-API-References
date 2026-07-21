---
title: "Aspose::Pdf::PageNumber clase"
linktitle: "PageNumber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageNumber clase. Representa un formato de número de página que incluye un índice, el número total de páginas y un delimitador en C++."
type: docs
weight: 14100
url: /es/cpp/aspose.pdf/pagenumber/
---
## PageNumber class


Representa un formato de número de página que incluye un índice, el número total de páginas y un delimitador.

```cpp
class PageNumber : public System::Object
```

## Nested classes

* Class [PageIndex](./pageindex/)
* Class [PageTotalNum](./pagetotalnum/)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Delimiter](./get_delimiter/)() const | Obtiene el delimitador usado en el formato de número de página. La cadena formateada se actualizará según el delimitador especificado. |
| [get_Index](./get_index/)() const | Obtiene el componente de índice de página del formato de número de página. La cadena formateada incluirá un marcador de posición para el índice de página. |
| [get_Offset](./get_offset/)() const | Obtiene el desplazamiento que se añadirá al índice de página. |
| [get_TotalNum](./get_totalnum/)() const | Obtiene el componente del número total de páginas del formato de número de página. La cadena formateada incluirá un marcador de posición para el número total de páginas. |
| [GetPageNumberString](./getpagenumberstring/)(int32_t, int32_t) | Devuelve una cadena formateada que representa el número de página según la configuración actual. |
| [PageNumber](./pagenumber/)() |  |
| [set_Delimiter](./set_delimiter/)(const System::String\&) | Establece el delimitador usado en el formato de número de página. La cadena formateada se actualizará según el delimitador especificado. |
| [set_Index](./set_index/)(const System::SharedPtr\<PageNumber::PageIndex\>\&) | Establece el componente de índice de página del formato de número de página. La cadena formateada incluirá un marcador de posición para el índice de página. |
| [set_Offset](./set_offset/)(int32_t) | Establece el desplazamiento que se añadirá al índice de página. |
| [set_TotalNum](./set_totalnum/)(const System::SharedPtr\<PageNumber::PageTotalNum\>\&) | Establece el componente del número total de páginas del formato de número de página. La cadena formateada incluirá un marcador de posición para el número total de páginas. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
