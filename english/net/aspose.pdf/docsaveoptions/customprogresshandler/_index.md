---
title: DocSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: DocSaveOptions field. This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages example of handlers code that shows progress on console is 
type: docs
weight: 140
url: /net/aspose.pdf/docsaveoptions/customprogresshandler/
---
## DocSaveOptions.CustomProgressHandler field

This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## Examples

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

### See Also

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


