---
title: "Form.FlattenField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Делает указанное поле плоским, используя полностью квалифицированное имя поля. Любое другое поле останется неизменяемым. Если fieldName недействительно, все поля останутся неизменяемыми."
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Преобразует указанное поле с полностью квалифицированным именем в плоское. Все остальные поля останутся неизменными. Если fieldName недействителен, все поля останутся неизменными.

```csharp
public void FlattenField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое будет сделано плоским. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


