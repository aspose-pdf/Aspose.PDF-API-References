---
title: HtmlSaveOptions.CustomProgressHandler
second_title: Aspose.PDF for .NET API Reference
description: حقل HtmlSaveOptions. يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال، يمكن استخدامه لعرض شريط التقدم أو الرسائل حول الكمية الحالية من الصفحات المعالجة. مثال على كود المعالج الذي يظهر التقدم على وحدة التحكم هو
type: docs
weight: 280
url: /ar/net/aspose.pdf/htmlsaveoptions/customprogresshandler/
---
## حقل HtmlSaveOptions.CustomProgressHandler

يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال، يمكن استخدامه لعرض شريط التقدم أو الرسائل حول الكمية الحالية من الصفحات المعالجة. مثال على كود المعالج الذي يظهر التقدم على وحدة التحكم هو :

```csharp
public ConversionProgressEventHandler CustomProgressHandler;
```

## أمثلة

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

### انظر أيضًا

* delegate [ConversionProgressEventHandler](../../unifiedsaveoptions.conversionprogresseventhandler/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)