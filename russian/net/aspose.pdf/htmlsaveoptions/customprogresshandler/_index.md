---
title: HtmlSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: Поле HtmlSaveOptions. Этот обработчик может быть использован для обработки событий прогресса конверсии, например, его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает прогресс в консоли:
type: docs
weight: 280
url: /ru/net/aspose.pdf/htmlsaveoptions/customprogresshandler/
---
## Поле HtmlSaveOptions.CustomProgressHandler

Этот обработчик может быть использован для обработки событий прогресса конверсии, например, его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает прогресс в консоли:

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## Примеры

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

### См. также

* делегат [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* класс [HtmlSaveOptions](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)