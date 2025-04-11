---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Добавить кнопку отправки на форму
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## Метод FormEditor.AddSubmitBtn

Добавить кнопку отправки на форму.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя новой кнопки. |
| page | Int32 | Страница, на которой будет размещена кнопка. |
| label | String | Надпись на кнопке. |
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

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)