---
title: "Form.FormSubmitButtonNames"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Form. Получает все имена кнопок отправки формы."
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

Получает имена всех кнопок отправки формы.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


