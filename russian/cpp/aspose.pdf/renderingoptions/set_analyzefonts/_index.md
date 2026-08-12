---
title: "метод Aspose::Pdf::RenderingOptions::set_AnalyzeFonts"
linktitle: "set_AnalyzeFonts"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::RenderingOptions::set_AnalyzeFonts. Заменяет шрифты при необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам: в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf/renderingoptions/set_analyzefonts/
---
## RenderingOptions::set_AnalyzeFonts method


Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам:

```cpp
void Aspose::Pdf::RenderingOptions::set_AnalyzeFonts(bool value)
```

## Примечания


1. Если пользователь явно задаёт свойство DefaultFontName, проверьте, может ли указанный шрифт отображать требуемые символы.
1. Если пользовательский шрифт не установлен, выполните поиск шрифтов, добавленных через [FontRepository::Sources](../).
1. Проанализируйте текст, чтобы определить его алфавит или письменность, и предложите соответствующие названия шрифтов. Попробуйте найти и использовать эти шрифты в системе.
1. В качестве резервного варианта выполните поиск в системе любого шрифта, способного отображать требуемые символы.


## См. также

* Class [RenderingOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
