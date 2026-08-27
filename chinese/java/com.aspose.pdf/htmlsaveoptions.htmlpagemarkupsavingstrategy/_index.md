---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "转换的结果可以包含一个或多个 HTML 页面（这些页面也可以引用图像或字体等外部文件），您可以将此属性分配为从创建的委托。"
type: docs
weight: 2110
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

转换结果可能包含一个或多个 HTML 页面（这些页面也可能引用图像或字体等外部文件）。您可以将由自定义方法创建的委托分配给此属性，该方法实现对在转换期间生成的 HTML 页面（HTML 本身）的处理。在这种情况下，处理（例如保存到流或磁盘）可以在该自定义代码中完成。此时，保存 HTML 页面标记的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存将不再使用。如果由于某种原因必须由转换器自身的代码而非自定义代码进行处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：它向转换器指示，所有对该资源的必要处理步骤应由转换器本身完成，就像没有任何外部自定义保存代码一样。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | 内部 beginInvoke 方法 |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | 内部 endInvoke 方法 |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | 调用的方法 |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
内部 beginInvoke 方法

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
内部 endInvoke 方法

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
调用的方法
