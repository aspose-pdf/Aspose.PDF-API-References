---
title: "FormEditor.DecorateField"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。更改指定字段的可视属性"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/formeditor/decoratefield/
---
## DecorateField(string) {#decoratefield_2}

更改指定字段的可视属性。

```csharp
public void DecorateField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |

## 示例

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

更改指定字段类型的所有字段的可视属性。

```csharp
public void DecorateField(FieldType fieldType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldType | FieldType | 将被装饰的字段类型。 |

## 示例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//装饰所有文本字段。
fe.DecorateField(FieldType.Text);
```

### 另请参见

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

更改 PDF 文档中所有字段的可视属性。

```csharp
public void DecorateField()
```

## 示例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//装饰所有字段。
fe.DecorateField();
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


