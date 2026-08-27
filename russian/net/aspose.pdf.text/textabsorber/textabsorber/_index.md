---
title: "TextAbsorber.TextAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор TextAbsorber. Инициализирует новый экземпляр TextAbsorber"
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Инициализирует новый экземпляр [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Примечания

Выполняет извлечение текста и предоставляет доступ к извлечённому тексту через объект [`Text`](../text/).

## Примеры

Пример демонстрирует, как извлечь текст со всех страниц PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создайте объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принять поглотитель для всех страниц документа
doc.Pages.Accept(absorber);

// получить извлечённый текст
string extractedText = absorber.Text;

```

### См. также

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Инициализирует новый экземпляр [`TextAbsorber`](../) с параметрами извлечения.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Параметры извлечения текста |

## Примечания

Выполняет извлечение текста и предоставляет доступ к извлечённому тексту через объект [`Text`](../text/).

## Примеры

Пример демонстрирует, как извлечь текст со всех страниц PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создать объект TextAbsorber для извлечения текста с форматированием
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// принять поглотитель для всех страниц документа
doc.Pages.Accept(absorber);

// получить извлечённый текст
string extractedText = absorber.Text;

```

### См. также

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

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

## Примечания

Выполняет извлечение текста и предоставляет доступ к извлечённому тексту через объект [`Text`](../text/).

### См. также

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Инициализирует новый экземпляр [`TextAbsorber`](../) с параметрами поиска текста.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Параметры поиска текста |

## Примечания

Выполняет извлечение текста и предоставляет доступ к извлечённому тексту через объект [`Text`](../text/).

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


