---
title: "TextAbsorber.Text"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextAbsorber. Получает извлечённый текст, который TextAbsorber извлекает из PDF‑документа или страницы"
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Получает извлечённый текст, который [`TextAbsorber`](../) извлекает из PDF‑документа или страницы.

```csharp
public virtual string Text { get; }
```

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


