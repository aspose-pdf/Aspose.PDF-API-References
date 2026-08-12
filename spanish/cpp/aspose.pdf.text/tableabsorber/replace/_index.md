---
title: "Aspose::Pdf::Text::TableAbsorber::Replace método"
linktitle: "Reemplazar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TableAbsorber::Replace método. Reemplaza una AbsorbedTable con Table en la página en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber::Replace method


Reemplaza una [AbsorbedTable](../../absorbedtable/) con [Table](../../../aspose.pdf/table/) en la página.

```cpp
void Aspose::Pdf::Text::TableAbsorber::Replace(const System::SharedPtr<Page> &page, const System::SharedPtr<AbsorbedTable> &oldTable, const System::SharedPtr<Table> &newTable)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | [Pdf](../../../aspose.pdf/) objeto de página de documento. |
| oldTable | const System::SharedPtr\<AbsorbedTable\>\& | [AbsorbedTable](../../absorbedtable/) para ser reemplazada. |
| newTable | const System::SharedPtr\<Table\>\& | [Table](../../../aspose.pdf/table/) para reemplazar la tabla antigua. |
## Observaciones



Tenga en cuenta que modifica la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, utilice una copia de la colección TableList.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [AbsorbedTable](../../absorbedtable/)
* Class [Table](../../../aspose.pdf/table/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
