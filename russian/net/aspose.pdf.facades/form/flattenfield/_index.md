---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Уплощает указанное поле с полным квалифицированным именем поля. Любое другое поле останется неизменным. Если имя поля недействительно, все поля останутся неизменными.
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/form/flattenfield/
---
## Метод Form.FlattenField

Уплощает указанное поле с полным квалифицированным именем поля. Любое другое поле останется неизменным. Если имя поля недействительно, все поля останутся неизменными.

```csharp
public void FlattenField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое нужно уплотнить. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)