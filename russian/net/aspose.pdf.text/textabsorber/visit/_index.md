---
title: Visit
second_title: Aspose.PDF для справочника API .NET
description: Извлекает текст на указанной странице
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
| page | Page | Объект страницы документа Pdf. |

### Примеры

В примере показано, как извлечь текст на первой странице документа PDF.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принимаем поглотитель для всех страниц документа
absorber.Visit(doc.Pages[1]);

// получаем извлеченный текст
string extractedText = absorber.Text;
```

### Смотрите также

* class [Page](../../../aspose.pdf/page)
* class [TextAbsorber](../../textabsorber)
* пространство имен [Aspose.Pdf.Text](../../textabsorber)
* сборка [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Извлекает текст из указанной формы XForm.

```csharp
public virtual void Visit(XForm form)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | XForm | Объект формы PDF. |

### Примеры

В примере показано, как извлечь текст на первой странице документа PDF.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принимаем поглотитель для всех страниц документа
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// получаем извлеченный текст
string extractedText = absorber.Text;
```

### Смотрите также

* class [XForm](../../../aspose.pdf/xform)
* class [TextAbsorber](../../textabsorber)
* пространство имен [Aspose.Pdf.Text](../../textabsorber)
* сборка [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Извлекает текст из указанного документа

```csharp
public virtual void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Pdf объект документа. |

### Примеры

Пример демонстрирует, как извлечь текст из документа PDF.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принимаем поглотитель для всех страниц документа
absorber.Visit(doc);

// получаем извлеченный текст
string extractedText = absorber.Text;
```

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [TextAbsorber](../../textabsorber)
* пространство имен [Aspose.Pdf.Text](../../textabsorber)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
