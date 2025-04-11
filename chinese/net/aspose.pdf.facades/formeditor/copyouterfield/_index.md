---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。将现有字段从一个 PDF 文档复制到另一个文档，保留原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

将现有字段从一个 PDF 文档复制到另一个文档，保留原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | 字符串 | 原始完全限定字段名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

将现有字段从一个 PDF 文档复制到另一个文档，指定页码和原始坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | 字符串 | 原始完全限定字段名称。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，新字段将复制到与旧字段相同的页面。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

将现有字段从一个 PDF 文档复制到另一个文档，指定页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | 字符串 | 原始完全限定字段名称。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，新字段将复制到与旧字段相同的页面。 |
| abscissa | 单精度 | 新字段的横坐标。如果为 -1，横坐标将等于原始值。 |
| ordinate | 单精度 | 新字段的纵坐标。如果为 -1，纵坐标将等于原始值。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)