---
title: "Aspose::Pdf::Text::TableAbsorber::Replace metod"
linktitle: "Ersätt"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TableAbsorber::Replace metod. Ersätter en AbsorbedTable med Table på sidan i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber::Replace method


Ersätter en [AbsorbedTable](../../absorbedtable/) med [Table](../../../aspose.pdf/table/) på sidan.

```cpp
void Aspose::Pdf::Text::TableAbsorber::Replace(const System::SharedPtr<Page> &page, const System::SharedPtr<AbsorbedTable> &oldTable, const System::SharedPtr<Table> &newTable)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | [Pdf](../../../aspose.pdf/) dokument sidobjekt. |
| oldTable | const System::SharedPtr\<AbsorbedTable\>\& | [AbsorbedTable](../../absorbedtable/) att ersättas. |
| newTable | const System::SharedPtr\<Table\>\& | [Table](../../../aspose.pdf/table/) för att ersätta gammal tabell. |
## Anmärkningar



Vänligen ta hänsyn till att det ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [AbsorbedTable](../../absorbedtable/)
* Class [Table](../../../aspose.pdf/table/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
