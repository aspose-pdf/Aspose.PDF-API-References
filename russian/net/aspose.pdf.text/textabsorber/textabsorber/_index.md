---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Конструктор TextAbsorber. Инициализирует новый экземпляр TextAbsorber
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Инициализирует новый экземпляр [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Remarks

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект [`Text`](../text/).

## Examples

Пример демонстрирует, как извлечь текст со всех страниц PDF-документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Инициализирует новый экземпляр [`TextAbsorber`](../) с параметрами извлечения.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Параметры извлечения текста |

## Remarks

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект [`Text`](../text/).

## Examples

Пример демонстрирует, как извлечь текст со всех страниц PDF-документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* класс [TextExtractionOptions](../../textextractionoptions/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Инициализирует новый экземпляр [`TextAbsorber`](../) с параметрами извлечения и поиска текста.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Параметры извлечения текста |
| textSearchOptions | TextSearchOptions | Параметры поиска текста |

## Remarks

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект [`Text`](../text/).

### See Also

* класс [TextExtractionOptions](../../textextractionoptions/)
* класс [TextSearchOptions](../../textsearchoptions/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Инициализирует новый экземпляр [`TextAbsorber`](../) с параметрами поиска текста.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Параметры поиска текста |

## Remarks

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект [`Text`](../text/).

### See Also

* класс [TextSearchOptions](../../textsearchoptions/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)