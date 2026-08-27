---
title: "FormEditor.Facade"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor プロパティ。フィールドの視覚属性を設定します。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

フィールドの視覚属性を設定します。

```csharp
public FormFieldFacade Facade { get; set; }
```

## 例

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

### 関連項目

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


