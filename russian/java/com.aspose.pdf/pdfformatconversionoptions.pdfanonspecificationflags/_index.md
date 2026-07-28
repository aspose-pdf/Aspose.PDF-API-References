---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Справочник API Aspose.PDF для Java"
description: "Этот класс содержит флаги для управления конвертацией PDF/A в случаях, когда исходный PDF‑документ не соответствует спецификации PDF. Если использовать флаги этого класса, это приводит к снижению."
type: docs
weight: 3740
url: /ru/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Этот класс содержит флаги для управления конвертацией PDF/A в случаях, когда исходный PDF‑документ не соответствует спецификации PDF. Если использовать флаги этого класса, производительность снижается, но это необходимо, когда исходный PDF‑документ нельзя преобразовать в формат PDF/A обычным способом. По умолчанию все флаги установлены в false.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Конструктор |

## Методы

| Метод | Описание |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Некоторые PDF‑документы содержат шрифты, имеющие разные имена во внутренних данных. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Некоторые PDF‑документы содержат шрифты, имеющие разные имена во внутренних данных. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Конструктор

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Некоторые PDF‑документы содержат шрифты, имеющие разные имена во внутренних данных. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются.

**Returns:**
логическое значение

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Некоторые PDF‑документы содержат шрифты, имеющие разные имена во внутренних данных. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |
