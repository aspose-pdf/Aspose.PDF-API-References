---
title: "Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth method"
linktitle: "get_SectionsSearchDepth"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth. Получает значение, которое указывает, сколько раз будут выполнены последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска горизонтально разделённых секций (заголовки, абзацы и т.д.) и три поиска вертикально разделённых (колонки) в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.text/paragraphabsorber/get_sectionssearchdepth/
---
## ParagraphAbsorber::get_SectionsSearchDepth method


Получает значение, указывающее, сколько раз будут выполнены последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска горизонтально разделённых разделов (заголовки, абзацы и т.д.) и три поиска вертикально разделённых (колонки).

```cpp
int32_t Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth() const
```

## Примечания


Увеличение этого значения может привести к небольшому снижению производительности без видимых изменений в результатах поиска. Уменьшение этого значения может привести к неправильному определению абзацев в секциях. Мы не рекомендуем устанавливать значение ниже значения по умолчанию, если вы не хотите получать только «грубые» элементы структуры страницы.
## См. также

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
