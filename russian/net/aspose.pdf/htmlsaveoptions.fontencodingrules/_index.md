---
title: HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF для справочника API .NET
description: Это перечисление определяет правила которые настраивают кодирование logic
type: docs
weight: 3490
url: /ru/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Это перечисление определяет правила, которые настраивают кодирование logic

```csharp
public enum FontEncodingRules : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Default | `0` | Оставить логику кодирования "как есть" - в соответствии со спецификацией PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode - это специальный механизм, который помогает декодировать входные коды в символы юникода. Согласно спецификации, он должен использоваться в первую очередь для получения символов юникода для конкретного входного кода. Но некоторые документы имеют нестандартные шрифты, и для корректного преобразования этих документов может потребоваться уменьшить приоритет ToUnicode и использовать другие механизмы для декодирования входных кодов. |

### Смотрите также

* class [HtmlSaveOptions](../htmlsaveoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
