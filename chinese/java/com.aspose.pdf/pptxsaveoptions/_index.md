---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 SVG 格式的保存选项"
type: docs
weight: 3950
url: /zh/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

导出为 SVG 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或有关当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | 获取或设置图像分辨率（dpi）。默认值为 192 dpi。 |
| [getSeparateImages](#getSeparateImages--) | 如果设置为 true，则图像会与所有其他图形分离 |
| [getSlidesAsImages](#getSlidesAsImages--) | 如果设置为 true，则所有内容都被识别为图像（每页一个） |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | 切换文本列识别 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件，例如。 |
| [setImageResolution](#setImageResolution-int-) | 获取或设置图像分辨率（dpi）。默认值为 192 dpi。 |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | 切换文本列识别 |
| [setSeparateImages](#setSeparateImages-boolean-) | 如果设置为 true，则图像会与所有其他图形分离 |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | 如果设置为 true，则所有内容都被识别为图像（每页一个） |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

构造函数

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或有关当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"input.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save(\"output.html\", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format(\"{0} - Conversion progress : {1}% .\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format(\"{0} - Source page {1} of {2} analyzed.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format(\"{0} - Result page's {1} of {2} layout created.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format(\"{0} - Result page {1} of {2} exported.\", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler 实例

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

获取或设置图像分辨率（dpi）。默认值为 192 dpi。

**Returns:**
int 值

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

如果设置为 true，则图像会与所有其他图形分离

**Returns:**
布尔值

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

如果设置为 true，则所有内容都被识别为图像（每页一个）

**Returns:**
布尔值

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

切换文本列识别

**Returns:**
布尔值

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
此处理程序可用于处理转换进度事件，例如。

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

获取或设置图像分辨率（dpi）。默认值为 192 dpi。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

切换文本列识别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

如果设置为 true，则图像会与所有其他图形分离

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

如果设置为 true，则所有内容都被识别为图像（每页一个）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
