---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。根据其完全限定字段名称，将图像粘贴到现有按钮字段作为其外观
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

根据其完全限定字段名称，将图像粘贴到现有按钮字段作为其外观。

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 图像按钮字段的完全限定字段名称。 |
| imageFileName | 字符串 | 图像文件的路径，相对路径和绝对路径均可。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

FillImageField 的重载函数。输入是一个图像流。

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 完全限定字段名称。 |
| imageStream | 流 | 图像的流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)