---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Получить значение поля Rich Text, включая информацию о форматировании каждого символа
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/form/getrichtext/
---
## Метод Form.GetRichText

Получить значение поля Rich Text, включая информацию о форматировании каждого символа.

```csharp
public string GetRichText(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля Rich Text. |

### Возвращаемое значение

Возвращает строку, содержащую информацию о форматировании поля Rich Text.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)