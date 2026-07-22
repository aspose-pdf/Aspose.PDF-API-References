---
title: "Aspose::Pdf::Text::TableAbsorber::Remove metod"
linktitle: "Ta bort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TableAbsorber::Remove metod. Tar bort en AbsorbedTable från sidan i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.text/tableabsorber/remove/
---
## TableAbsorber::Remove method


Tar bort en [AbsorbedTable](../../absorbedtable/) från sidan.

```cpp
void Aspose::Pdf::Text::TableAbsorber::Remove(const System::SharedPtr<AbsorbedTable> &table)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| table | const System::SharedPtr\<AbsorbedTable\>\& | [AbsorbedTable](../../absorbedtable/) att ta bort. |
## Anmärkningar



Vänligen ta hänsyn till att det ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AbsorbedTable](../../absorbedtable/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
