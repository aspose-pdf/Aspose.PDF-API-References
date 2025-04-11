---
title: PptxSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: Propiedad PptxSaveOptions. Este controlador se puede utilizar para manejar eventos de progreso de conversión, por ejemplo, se puede utilizar para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas. Un ejemplo de código de controladores que muestra el progreso en la consola es
type: docs
weight: 20
url: /es/net/aspose.pdf/pptxsaveoptions/customprogresshandler/
---
## Propiedad PptxSaveOptions.CustomProgressHandler

Este controlador se puede utilizar para manejar eventos de progreso de conversión, por ejemplo, se puede utilizar para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas. Un ejemplo de código de controlador que muestra el progreso en la consola es :

```csharp
public ConversionProgressEventHandler CustomProgressHandler { get; set; }
```

## Ejemplos

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

### Ver También

* delegado [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* clase [PptxSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)