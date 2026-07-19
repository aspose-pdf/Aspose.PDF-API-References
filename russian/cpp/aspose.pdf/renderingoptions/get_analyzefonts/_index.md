---
title: "Метод Aspose::Pdf::RenderingOptions::get_AnalyzeFonts"
linktitle: "get_AnalyzeFonts"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::RenderingOptions::get_AnalyzeFonts метод. Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам: в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/renderingoptions/get_analyzefonts/
---
## RenderingOptions::get_AnalyzeFonts method


Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам:

```cpp
bool Aspose::Pdf::RenderingOptions::get_AnalyzeFonts() const
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
