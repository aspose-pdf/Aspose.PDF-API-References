---
title: CustomProgressHandler
second_title: Aspose.PDF for .NET API Referansı
description: Bu işleyici dönüşüm ilerleme olaylarını işlemek için kullanılabilir fe ilerleme çubuğunu veya işlenen sayfaların mevcut miktarı hakkındaki mesajları göstermek için kullanılabilir işleyicinin konsoldaki ilerlemeyi gösteren kodunun örneği 
type: docs
weight: 120
url: /tr/net/aspose.pdf/docsaveoptions/customprogresshandler/
---
## DocSaveOptions.CustomProgressHandler field

Bu işleyici dönüşüm ilerleme olaylarını işlemek için kullanılabilir fe ilerleme çubuğunu veya işlenen sayfaların mevcut miktarı hakkındaki mesajları göstermek için kullanılabilir, işleyicinin konsoldaki ilerlemeyi gösteren kodunun örneği :

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

### Örnekler

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

### Ayrıca bakınız

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler)
* class [DocSaveOptions](../../docsaveoptions)
* ad alanı [Aspose.Pdf](../../docsaveoptions)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->