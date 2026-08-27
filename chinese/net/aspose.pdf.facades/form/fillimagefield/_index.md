---
title: "Form.FillImageField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据其完全限定字段名，将图像粘贴到现有按钮字段上作为其外观。"
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

根据完全限定字段名将图像粘贴到现有按钮字段上作为其外观。

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 图像按钮字段的完全限定字段名。 |
| imageFileName | String | 图像文件的路径，支持相对路径和绝对路径。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

重载 FillImageField 函数。输入为图像流。

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |
| imageStream | Stream | 图像的流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


