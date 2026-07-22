---
title: "Aspose::Pdf::Facades::ReplaceTextStrategy klass"
linktitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::ReplaceTextStrategy klass. Denna klass innehåller parametrar som definierar PdfContentEditor-beteende när ReplaceText‑operationen utförs i C++."
type: docs
weight: 3200
url: /sv/cpp/aspose.pdf.facades/replacetextstrategy/
---
## ReplaceTextStrategy class


Denna klass innehåller parametrar som definierar [PdfContentEditor](../pdfcontenteditor/)‑beteende när ReplaceText‑operationen utförs.

```cpp
class ReplaceTextStrategy : public System::Object
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet. |
| [Scope](./scope/) | [Omfång](./scope/) där ersättningsoperationen för text tillämpas REPLACE_FIRST som standard. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Om falskt är strängen att söka en enkel text. Om sant är strängen att söka ett reguljärt uttryck. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Åtgärd som utförs när inget lämpligt teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå). |
| [get_ReplaceScope](./get_replacescope/)() const | [Omfång](./scope/) för ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster). |
| [ReplaceTextStrategy](./replacetextstrategy/)() |  |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Om falskt är strängen att söka en enkel text. Om sant är strängen att söka ett reguljärt uttryck. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(ReplaceTextStrategy::NoCharacterAction) | Åtgärd som utförs när inget lämpligt teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå). |
| [set_ReplaceScope](./set_replacescope/)(ReplaceTextStrategy::Scope) | [Omfång](./scope/) för ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
