---
title: FillImageField
second_title: Aspose.PDF for .NET API 参考
description: 根据 其完全限定的字段名称将图像粘贴到现有按钮字段上作为其外观
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

根据 其完全限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 图像按钮字段的完全限定字段名称。 |
| imageFileName | String | 图片文件的路径，相对路径和绝对路径都可以。 |

### 例子

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### 也可以看看

* class [Form](../../form)
* 命名空间 [Aspose.Pdf.Facades](../../form)
* 部件 [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

重载FillImageField的函数 输入的是图像流

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |
| imageStream | Stream | 图像的流。 |

### 例子

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### 也可以看看

* class [Form](../../form)
* 命名空间 [Aspose.Pdf.Facades](../../form)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->