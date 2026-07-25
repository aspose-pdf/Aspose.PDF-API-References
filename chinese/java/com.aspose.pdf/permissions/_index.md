---
title: "权限"
linktitle: "权限"
second_title: "Aspose.PDF for Java API 参考"
description: "二进制标志 此枚举表示用户对 PDF 的权限。"
type: docs
weight: 3830
url: /zh/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

二进制标志 此枚举表示用户对 PDF 的权限。

## 字段

| 字段 | 描述 |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | （修订版 3 或更高的安全处理程序）组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 {@code ModifyContent} 已清除。 |
| [ExtractContent](#ExtractContent) | (Security handlers of revision 2) 复制或以其他方式从文档中提取文本和图形，包括提取文本和图形（以支持残障用户的可访问性或出于其他目的）。(Security handlers of revision 3 or greater) 通过非 {@code ExtractContentWithDisabilities} 控制的操作复制或以其他方式从文档中提取文本和图形。 |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Security handlers of revision 3 or greater) 提取文本和图形（以支持残障用户的可访问性或出于其他目的）。 |
| [FillForm](#FillForm) | (Security handlers of revision 3 or greater) 填写现有的交互式表单字段（包括签名字段），即使 {@code ModifyTextAnnotations} 已被清除。 |
| [ModifyContent](#ModifyContent) | 通过非 {@code ModifyTextAnnotations}、{@code FillForm} 和 11 控制的操作修改文档内容。 |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | 添加或修改文本注释，填写交互式表单字段，如果同时设置了 {@code ModifyContent}，则创建或修改交互式表单字段（包括签名字段）。 |
| [PrintDocument](#PrintDocument) | (Security handlers of revision 2) 打印文档。(Security handlers of revision 3 or greater) 打印文档（可能未达到最高质量水平，取决于是否也设置了 {@code PrintingQuality}）。 |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) 将文档打印为一种可以生成 PDF 内容忠实数字副本的表示形式。当此位被清除（且第 3 位被设置）时，打印仅限于外观的低层次表示，可能质量下降。 |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

（修订版 3 或更高的安全处理程序）组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 {@code ModifyContent} 已清除。

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Security handlers of revision 2) 复制或以其他方式从文档中提取文本和图形，包括提取文本和图形（以支持残障用户的可访问性或出于其他目的）。(Security handlers of revision 3 or greater) 通过非 {@code ExtractContentWithDisabilities} 控制的操作复制或以其他方式从文档中提取文本和图形。

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Security handlers of revision 3 or greater) 提取文本和图形（以支持残障用户的可访问性或出于其他目的）。

### FillForm {#FillForm}
```
public static final int FillForm
```

(Security handlers of revision 3 or greater) 填写现有的交互式表单字段（包括签名字段），即使 {@code ModifyTextAnnotations} 已被清除。

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

通过非 {@code ModifyTextAnnotations}、{@code FillForm} 和 11 控制的操作修改文档内容。

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

添加或修改文本注释，填写交互式表单字段，如果同时设置了 {@code ModifyContent}，则创建或修改交互式表单字段（包括签名字段）。

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Security handlers of revision 2) 打印文档。(Security handlers of revision 3 or greater) 打印文档（可能未达到最高质量水平，取决于是否也设置了 {@code PrintingQuality}）。

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Security handlers of revision 3 or greater) 将文档打印为一种可以生成 PDF 内容忠实数字副本的表示形式。当此位被清除（且第 3 位被设置）时，打印仅限于外观的低层次表示，可能质量下降。
