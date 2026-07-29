---
title: "HtmlSaveOptions.CustomProgressHandler"
second_title: "Aspose.PDF for .NET API 参考"
description: "HtmlSaveOptions 字段。此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理 Page 数量的消息。以下是显示控制台进度的处理程序代码示例："
type: docs
weight: 280
url: /zh/net/aspose.pdf/htmlsaveoptions/customprogresshandler/
---
## HtmlSaveOptions.CustomProgressHandler field

此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例：

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## 示例

```csharp
public static void ConvertWithShowingProgress()

  (new Aspose.Pdf.License()).SetLicense(@"F:\_Sources\Aspose_5\trunk\testdata\License\Aspose.Total.lic");
  Document doc = new Document(@"F:\ExternalTestsData\Booklet.pdf");
  HtmlSaveOptions saveOptions = new HtmlSaveOptions();
  saveOptions.CustomProgressHandler = new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole);
  doc.Save(@"F:\ExternalTestsData\Booklet.doc", saveOptions);
  Console.ReadLine();

blic static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)

  switch (eventInfo.EventType)
  {
      case HtmlSaveOptions.ProgressEventType.TotalProgress:
          Console.WriteLine(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
          break;
      case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
          Console.WriteLine(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
          break;
      case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
          Console.WriteLine(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
          break;
      case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
          Console.WriteLine(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
          break;
      default:
          break;
  }

```

### 另请参见

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


