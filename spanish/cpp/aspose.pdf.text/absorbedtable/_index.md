---
title: "Aspose::Pdf::Text::AbsorbedTable class"
linktitle: "AbsorbedTable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::AbsorbedTable class. Representa una tabla que existe en la página en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.text/absorbedtable/
---
## AbsorbedTable class


Representa una tabla que existe en la página.

```cpp
class AbsorbedTable : public Aspose::Pdf::Text::ITableElement,
                      public System::IComparable<System::SharedPtr<AbsorbedTable>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedTable\>) override | Compara el objeto [AbsorbedTable](./) actual con otro objeto [AbsorbedTable](./) y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [get_PageNum](./get_pagenum/)() const | Obtiene el número de la página que contiene esta tabla. |
| [get_Rectangle](./get_rectangle/)() override | Obtiene el rectángulo que describe la posición de la tabla en la página. |
| [get_RowList](./get_rowlist/)() | Obtiene IList de solo lectura que contiene las filas de la tabla. |
## Ver también

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
