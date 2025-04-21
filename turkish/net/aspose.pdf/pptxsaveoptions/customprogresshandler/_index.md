---
title: PptxSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: PptxSaveOptions özelliği. Bu işleyici, dönüşüm ilerleme olaylarını yönetmek için kullanılabilir; örneğin, işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir. Konsolda ilerlemeyi gösteren işleyici kodunun örneği şudur
type: docs
weight: 20
url: /tr/net/aspose.pdf/pptxsaveoptions/customprogresshandler/
---
## PptxSaveOptions.CustomProgressHandler özelliği

Bu işleyici, dönüşüm ilerleme olaylarını yönetmek için kullanılabilir; örneğin, işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir. Konsolda ilerlemeyi gösteren işleyici kodunun örneği şudur:

```csharp
public ConversionProgressEventHandler CustomProgressHandler { get; set; }
```

## Örnekler

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

### Ayrıca Bakınız

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [PptxSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)