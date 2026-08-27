---
title: "Перечисление HtmlSaveOptions.FontEncodingRules"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.HtmlSaveOptionsFontEncodingRules. Это перечисление определяет правила, которые настраивают логику кодирования"
type: docs
weight: 5750
url: /ru/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Это перечисление определяет правила, которые настраивают логику кодирования

```csharp
public enum FontEncodingRules : byte
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | `0` | Оставить логику кодирования «как есть» — в соответствии со спецификацией PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode — это специальный механизм, который помогает декодировать входные коды в символы Unicode. Согласно спецификации, он должен использоваться в качестве первого механизма для получения символов Unicode для конкретного входного кода. Однако в некоторых документах используются нестандартные шрифты, и для корректного преобразования этих документов может потребоваться уменьшить приоритет ToUnicode и использовать другие механизмы декодирования входных кодов. |

### См. также

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


