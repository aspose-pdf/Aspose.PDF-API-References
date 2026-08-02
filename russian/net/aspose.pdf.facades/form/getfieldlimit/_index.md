---
title: "Form.GetFieldLimit"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Получить ограничение текстового поля"
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Получает ограничения текстового поля.

```csharp
public int GetFieldLimit(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |

### Возвращаемое значение

Возвращает ограничение количества символов, которое может быть заполнено в текстовом поле. Если не установлено, возвращает 0.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


