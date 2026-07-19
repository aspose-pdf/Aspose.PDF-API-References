---
title: "Aspose::Pdf::Text::FontRepository класс"
linktitle: "FontRepository"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::FontRepository класс. Выполняет поиск шрифтов. Ищет среди системно установленных шрифтов и стандартных шрифтов Pdf. Также предоставляет возможность открывать пользовательские шрифты в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.pdf.text/fontrepository/
---
## FontRepository class


Выполняет поиск шрифтов. Ищет среди системно установленных шрифтов и стандартных шрифтов [Pdf](../../aspose.pdf/). Также предоставляет возможность открывать пользовательские шрифты.

```cpp
class FontRepository : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [FindFont](./findfont/)(const System::String\&) | Ищет и возвращает шрифт с указанным именем шрифта. |
| static [FindFont](./findfont/)(const System::String\&, bool) | Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая регистр. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles, bool) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая регистр. |
| static [get_Sources](./get_sources/)() | Получает коллекцию источников шрифтов. |
| static [get_Substitutions](./get_substitutions/)() | Получает коллекцию стратегий замены шрифтов. |
| static [LoadFonts](./loadfonts/)() | Загружает системно установленные шрифты и стандартные шрифты [Pdf](../../aspose.pdf/). Этот метод был разработан для ускорения процесса загрузки шрифтов. По умолчанию шрифты загружаются при первом запросе любого шрифта. Использование этого метода загружает системные и стандартные шрифты [Pdf](../../aspose.pdf/) сразу перед открытием любого документа [Pdf](../../aspose.pdf/). |
| static [OpenFont](./openfont/)(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) | Открывает шрифт с указанным потоком шрифта. |
| static [OpenFont](./openfont/)(const System::String\&) | Открывает шрифт с указанным путем к файлу шрифта. |
| static [OpenFont](./openfont/)(const System::String\&, const System::String\&) | Открывает шрифт с указанным путем к файлу шрифта и путем к файлу метрик. |
| static [ReloadFonts](./reloadfonts/)() | Перезагружает все шрифты, указанные свойством [Sources](../) |


## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
