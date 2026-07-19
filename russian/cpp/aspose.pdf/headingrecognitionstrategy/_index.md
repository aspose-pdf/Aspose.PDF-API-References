---
title: "Aspose::Pdf::HeadingRecognitionStrategy перечисление"
linktitle: "HeadingRecognitionStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HeadingRecognitionStrategy перечисление. Представляет типы стратегий распознавания заголовков на C++."
type: docs
weight: 23900
url: /ru/cpp/aspose.pdf/headingrecognitionstrategy/
---
## HeadingRecognitionStrategy enum


Представляет типы стратегий распознавания заголовков.

```cpp
enum class HeadingRecognitionStrategy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Outlines | 0 | Представляет стратегию распознавания заголовков с помощью Outlines. |
| Heuristic | 1 | Представляет стратегию распознавания заголовков с помощью эвристических правил и статистики размеров шрифтов. |
| Auto | 2 | Обеспечивает автоматический выбор стратегии распознавания заголовков. Это вариант по умолчанию. Если документ содержит закладки, будет выбрана стратегия [Outlines](../outlines/), в противном случае — [Heuristic](./). |
| None | 3 | Не распознавать заголовки. Эта опция может быть полезна в сложных форматированных документах. |

## См. также

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
