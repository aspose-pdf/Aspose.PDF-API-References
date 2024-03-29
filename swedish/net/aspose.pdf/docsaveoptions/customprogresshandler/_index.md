---
title: CustomProgressHandler
second_title: Aspose.PDF för .NET API Referens
description: Denna hanterare kan användas för att hantera konverteringsförloppshändelser fe den kan användas för att visa förloppsindikator eller meddelanden om aktuell mängd av bearbetade sidor exempel på hanterarens kod som visar framsteg på konsolen är
type: docs
weight: 120
url: /sv/net/aspose.pdf/docsaveoptions/customprogresshandler/
---
## DocSaveOptions.CustomProgressHandler field

Denna hanterare kan användas för att hantera konverteringsförloppshändelser fe den kan användas för att visa förloppsindikator eller meddelanden om aktuell mängd av bearbetade sidor, exempel på hanterarens kod som visar framsteg på konsolen är:

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

### Exempel

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

### Se även

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler)
* class [DocSaveOptions](../../docsaveoptions)
* namnutrymme [Aspose.Pdf](../../docsaveoptions)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
