---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Справочник API Aspose.PDF для Java"
description: "Это перечисление описывает возможные меры сглаживания при конвертации"
type: docs
weight: 2000
url: /ru/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Это перечисление описывает возможные меры сглаживания при конвертации

## Поля

| Поле | Описание |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Не используется специальное сглаживание. Это оптимальный вариант для подавляющего большинства документов и не требует дополнительного времени при конвертации |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | В таком случае конвертер пытается обнаружить места с соседними графическими элементами фона и корректно сформировать результирующий HTML. Эта опция позволяет улучшить результат экспорта для документов, содержащих фоны, построенные из нескольких соседних графических элементов (для таких документов PDF‑рендереры, например Acrobat Reader, обычно пытаются сгладить границы элементов при рендеринге). С этой опцией конвертер имитирует поведение PDF‑рендереров. Эта опция позволяет улучшить макет результата экспорта для некоторых специфических документов (использующих такие составные фоны), но требует дополнительного времени для обработки (обычно около 10‑15 % дополнительного времени). Поэтому использование этого режима в общем случае не рекомендуется. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Не используется специальное сглаживание. Это оптимальный вариант для подавляющего большинства документов и не требует дополнительного времени при конвертации

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

В таком случае конвертер пытается обнаружить места с соседними графическими элементами фона и корректно сформировать результирующий HTML. Эта опция позволяет улучшить результат экспорта для документов, содержащих фоны, построенные из нескольких соседних графических элементов (для таких документов PDF‑рендереры, например Acrobat Reader, обычно пытаются сгладить границы элементов при рендеринге). С этой опцией конвертер имитирует поведение PDF‑рендереров. Эта опция позволяет улучшить макет результата экспорта для некоторых специфических документов (использующих такие составные фоны), но требует дополнительного времени для обработки (обычно около 10‑15 % дополнительного времени). Поэтому использование этого режима в общем случае не рекомендуется.
