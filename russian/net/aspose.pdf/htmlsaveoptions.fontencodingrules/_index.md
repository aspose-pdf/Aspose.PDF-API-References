---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsFontEncodingRules Aspose.Pdf. Эта перечисление определяет правила, которые настраивают логику кодирования
type: docs
weight: 5620
url: /ru/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Перечисление HtmlSaveOptions.FontEncodingRules

Это перечисление определяет правила, которые настраивают логику кодирования

```csharp
public enum FontEncodingRules : byte
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | `0` | Оставить логику кодирования "как есть" - в соответствии со спецификацией PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode - это специальный механизм, который помогает декодировать входные коды в символы unicode. Согласно спецификации, он должен использоваться прежде всего для получения символов unicode для конкретного входного кода. Но некоторые документы имеют нестандартные шрифты, и для правильного преобразования этих документов может потребоваться уменьшить приоритет ToUnicode и использовать другие механизмы для декодирования входных кодов. |

### См. также

* класс [HtmlSaveOptions](../htmlsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)