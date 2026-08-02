---
title: "PdfViewer.Resolution"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfViewer. Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем ниже скорость. Значение по умолчанию — 150"
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем медленнее скорость. Значение по умолчанию — 150.

```csharp
public int Resolution { get; set; }
```

## Примечания

Это свойство изменяет разрешение изображения в процессах преобразования страницы в изображение: когда параметр [`PrintAsImage`](../printasimage/) установлен в `true`, или когда вызывается метод [`DecodePage`](../decodepage/) или [`DecodeAllPages`](../decodeallpages/). Чтобы задать разрешение принтера для прямой печати, используйте свойство [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) в классе [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### См. также

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


