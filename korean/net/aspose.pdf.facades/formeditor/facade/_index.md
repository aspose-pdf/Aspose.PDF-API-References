---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 필드의 시각적 속성을 설정합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade 속성

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

### 참조

* 클래스 [FormFieldFacade](../../formfieldfacade/)
* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)