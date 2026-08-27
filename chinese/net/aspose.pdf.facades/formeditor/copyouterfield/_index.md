---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。将现有字段从一个 PDF 文档复制到另一个文档，保留原始页码和坐标。注意：仅适用于 AcroForm 字段，不包括单选框。"
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

将现有字段从一个 PDF 文档复制到另一个文档，保持原始页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | String | 原始完整限定字段名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//将文本字段从 source.pdf 复制到 PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和原始坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | String | 原始完整限定字段名称。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，则新字段将复制到与旧字段相同的页面。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

将现有字段从一个 PDF 文档复制到另一个文档，使用指定的页码和坐标。注意：仅适用于 AcroForm 字段（不包括单选框）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 包含要复制字段的 PDF 文档的名称。 |
| fieldName | String | 原始完整限定字段名称。 |
| pageNum | Int32 | 用于容纳新字段的页码。如果为 -1，则新字段将复制到与旧字段相同的页面。 |
| 横坐标 | Single | 新字段的横坐标。如果为 -1，横坐标将等于原始值。 |
| 纵坐标 | Single | 新字段的纵坐标。如果为 -1，则纵坐标将等于原始值。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


