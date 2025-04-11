---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Возвращает флаги отправки кнопок отправки
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/form/getsubmitflags/
---
## Метод Form.GetSubmitFlags

Возвращает флаги отправки кнопки отправки

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |

### Возвращаемое значение

Флаги отправки кнопки.

## Примеры

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### См. также

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)