---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Метод TextAbsorber. Извлекает текст на указанной странице
type: docs
weight: 70
url: /ru/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Извлекает текст на указанной странице

```csharp
public virtual void Visit(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Объект страницы PDF документа. |

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Извлекает текст на указанном XForm.

```csharp
public virtual void Visit(XForm form)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | XForm | Объект формы PDF. |

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### См. также

* класс [XForm](../../../aspose.pdf/xform/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Извлекает текст на указанном документе

```csharp
public virtual void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект документа PDF. |

## Примеры

Пример демонстрирует, как извлечь текст из PDF документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)