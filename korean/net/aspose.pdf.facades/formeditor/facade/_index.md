---
title: "FormEditor.Facade"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor property. 필드의 시각적 속성을 설정합니다."
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

필드의 시각적 속성을 설정합니다.

```csharp
public FormFieldFacade Facade { get; set; }
```

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
fe.Save();
```

### 또 보기

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


