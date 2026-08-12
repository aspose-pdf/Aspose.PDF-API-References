---
title: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes enum"
linktitle: "FontSavingModes"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes enum. Перечисляет режимы, которые могут использоваться для сохранения шрифтов, указанных в сохранённом PDF, в C++."
type: docs
weight: 5300
url: /ru/cpp/aspose.pdf/htmlsaveoptions/fontsavingmodes/
---
## FontSavingModes enum


Перечисляет режимы, которые могут использоваться для сохранения шрифтов, указанных в сохранённом PDF.

```cpp
enum class FontSavingModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AlwaysSaveAsWOFF | 0 | Все ссылки на шрифты будут сохранены и указаны как WOFF‑шрифты. |
| AlwaysSaveAsTTF | 1 | Все ссылки на шрифты будут сохранены и указаны как TTF‑шрифты. |
| AlwaysSaveAsEOT | 2 | Все ссылки на шрифты будут сохранены и указаны как EOT‑шрифты. |
| SaveInAllFormats | 3 | Все ссылки на шрифты будут сохранены (и указаны в CSS) как 3 независимых файла: EOT, TTH, WOFF. Это увеличивает размер выходных данных, но делает вывод совместимым с подавляющим большинством веб‑браузеров. |
| DontSave | 4 | Ссылки на шрифты не будут сохранены. |

## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
