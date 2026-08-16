---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Справочник API Aspose.PDF для Java"
description: "ВНИМАНИЕ! Функция реализована, но ещё не добавлена в публичный API из‑за блокирующей проблемы в слое OSHARED, обнаруженной в образце документа. Представляет режим использования размера страницы."
type: docs
weight: 2810
url: /ru/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ВНИМАНИЕ! Функция реализована, но ещё не добавлена в публичный API из‑за блокирующей проблемы в слое OSHARED, обнаруженной в образце документа. Представляет режим использования размера страницы при конвертации. Форматы (например HTML, EPUB и т.п.) обычно имеют плавающий дизайн, поэтому позволяют подогнать требуемый размер страницы. Но иногда содержимое задаёт горизонтальные позиции или размер, которые не позволяют разместить его в требуемом размере страницы. В таком случае можно определить, что следует делать (например, когда размер содержимого не вписывается в требуемый начальный размер страницы результирующего PDF‑документа).

## Поля

| Поле | Описание |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Этот режим определяет такое поведение: после получения результата конвертации и обнаружения факта, что часть содержимого была усечена, ширина области просмотра увеличивается, чтобы вместить содержимое, и конвертация повторяется. Этот режим позволяет получить меньше страниц в результате в таком случае, но требует повторного рендеринга (а значит, больше времени обработки). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | В этом режиме страницы результата будут иметь требуемый размер страницы, определённый в LoadOptions, независимо от того, выходит ли содержимое после конвертации за пределы границ страницы или нет. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Этот режим определяет такое поведение: после получения результата конвертации и обнаружения факта, что часть содержимого была усечена, ширина области просмотра увеличивается, чтобы вместить содержимое, и конвертация повторяется. Этот режим позволяет получить меньше страниц в результате в таком случае, но требует повторного рендеринга (а значит, больше времени обработки).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

В этом режиме страницы результата будут иметь требуемый размер страницы, определённый в LoadOptions, независимо от того, выходит ли содержимое после конвертации за пределы границ страницы или нет.
