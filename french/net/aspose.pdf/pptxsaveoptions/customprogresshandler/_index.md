---
title: PptxSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: Propriété PptxSaveOptions. Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple, il peut être utilisé pour afficher une barre de progression ou des messages sur le nombre actuel de pages traitées, un exemple de code de gestionnaire qui montre la progression sur la console est
type: docs
weight: 20
url: /fr/net/aspose.pdf/pptxsaveoptions/customprogresshandler/
---
## Propriété PptxSaveOptions.CustomProgressHandler

Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple, il peut être utilisé pour afficher une barre de progression ou des messages sur le nombre actuel de pages traitées, un exemple de code de gestionnaire qui montre la progression sur la console est :

```csharp
public ConversionProgressEventHandler CustomProgressHandler { get; set; }
```

## Exemples

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

### Voir aussi

* délégué [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* classe [PptxSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)