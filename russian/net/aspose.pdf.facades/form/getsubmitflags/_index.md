---
title: "Form.GetSubmitFlags"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Возвращает флаги отправки кнопок."
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Возвращает флаги отправки кнопки submit

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |

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


