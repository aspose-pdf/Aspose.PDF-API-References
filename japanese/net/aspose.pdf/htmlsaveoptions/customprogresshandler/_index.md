---
title: HtmlSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions フィールド。このハンドラーは、変換進行状況イベントを処理するために使用できます。例えば、進行状況バーや現在処理されているページの量に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラーのコードの例は次のとおりです。
type: docs
weight: 280
url: /ja/net/aspose.pdf/htmlsaveoptions/customprogresshandler/
---
## HtmlSaveOptions.CustomProgressHandler フィールド

このハンドラーは、変換進行状況イベントを処理するために使用できます。例えば、進行状況バーや現在処理されているページの量に関するメッセージを表示するために使用できます。コンソールに進行状況を表示するハンドラーのコードの例は次のとおりです。

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## 例

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

### 参照

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)