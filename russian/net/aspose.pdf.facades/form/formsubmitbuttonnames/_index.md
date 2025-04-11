---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Свойство формы. Получает все имена кнопок отправки формы
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Свойство Form.FormSubmitButtonNames

Получает все имена кнопок отправки формы.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)