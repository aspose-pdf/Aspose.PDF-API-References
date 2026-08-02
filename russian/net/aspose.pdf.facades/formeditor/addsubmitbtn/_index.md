---
title: "FormEditor.AddSubmitBtn"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Добавить кнопку отправки в форму"
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Добавить кнопку отправки в форму.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя новой кнопки. |
| страница | Int32 | Страница, на которой будет размещена кнопка. |
| метка | String | Подпись кнопки. |
| url | String | URL кнопки отправки. |
| llx | Single | Абсцисса нижнего левого угла. |
| lly | Single | Ордината нижнего левого угла. |
| urx | Single | Абсцисса верхнего правого угла. |
| ury | Single | Ордината верхнего правого угла. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


