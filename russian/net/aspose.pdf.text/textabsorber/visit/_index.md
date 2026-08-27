---
title: "TextAbsorber.Visit"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextAbsorber. Извлекает текст на указанной странице"
type: docs
weight: 70
url: /ru/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Извлекает текст из указанной страницы

```csharp
public virtual void Visit(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Страница | Объект страницы Pdf документа. |

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создайте объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принять поглотитель для всех страниц документа
absorber.Visit(doc.Pages[1]);

// получить извлечённый текст
string extractedText = absorber.Text;
```

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Извлекает текст из указанного XForm.

```csharp
public virtual void Visit(XForm form)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| форма | XForm | Объект формы Pdf. |

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создайте объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принять поглотитель для всех страниц документа
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// получить извлечённый текст
string extractedText = absorber.Text;
```

### См. также

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Извлекает текст из указанного документа

```csharp
public virtual void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект Pdf документа. |

## Примеры

Пример демонстрирует, как извлечь текст из PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создайте объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принять поглотитель для всех страниц документа
absorber.Visit(doc);

// получить извлечённый текст
string extractedText = absorber.Text;
```

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


