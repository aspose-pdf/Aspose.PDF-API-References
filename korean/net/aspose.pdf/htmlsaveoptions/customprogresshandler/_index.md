---
title: HtmlSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 필드. 이 핸들러는 변환 진행 이벤트를 처리하는 데 사용할 수 있습니다. 예를 들어 진행률 표시줄이나 현재 처리된 페이지 수에 대한 메시지를 표시하는 데 사용할 수 있습니다. 콘솔에서 진행 상황을 표시하는 핸들러 코드의 예는 다음과 같습니다.
type: docs
weight: 280
url: /ko/net/aspose.pdf/htmlsaveoptions/customprogresshandler/
---
## HtmlSaveOptions.CustomProgressHandler 필드

이 핸들러는 변환 진행 이벤트를 처리하는 데 사용할 수 있습니다. 예를 들어 진행률 표시줄이나 현재 처리된 페이지 수에 대한 메시지를 표시하는 데 사용할 수 있습니다. 콘솔에서 진행 상황을 표시하는 핸들러 코드의 예는 다음과 같습니다:

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## 예제

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

### 참조

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)