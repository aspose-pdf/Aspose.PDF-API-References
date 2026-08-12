---
title: "Aspose::Pdf::Text::TableAbsorber klass"
linktitle: "TableAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TableAbsorber klass. Representerar ett absorberande objekt för tabell‑element. Utför sökning och ger åtkomst till sökresultat via TableAbsorber::TableList‑samlingen i C++."
type: docs
weight: 3300
url: /sv/cpp/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class


Representerar ett absorberingsobjekt för tabell-element. Utför sökning och ger åtkomst till sökresultat via samlingen [TableAbsorber::TableList](../).

```cpp
class TableAbsorber : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_TableList](./get_tablelist/)() | Returnerar en skrivskyddad IList som innehåller tabeller som hittades. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Hämtar alternativ för textsökning. |
| [get_UseFlowEngine](./get_useflowengine/)() const |  |
| [Remove](./remove/)(const System::SharedPtr\<AbsorbedTable\>\&) | Tar bort en [AbsorbedTable](../absorbedtable/) från sidan. |
| [Replace](./replace/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<AbsorbedTable\>\&, const System::SharedPtr\<Table\>\&) | Ersätter en [AbsorbedTable](../absorbedtable/) med [Table](../../aspose.pdf/table/) på sidan. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Ställer in alternativ för textsökning. |
| [set_UseFlowEngine](./set_useflowengine/)(bool) |  |
| [TableAbsorber](./tableabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TableAbsorber](./) med alternativ för textsökning. |
| [TableAbsorber](./tableabsorber/)() | Initierar en ny instans av [TableAbsorber](./). |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extraherar tabeller på den angivna sidan. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Extraherar tabeller i det angivna dokumentet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
