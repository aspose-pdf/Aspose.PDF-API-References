---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfViewer. Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем медленнее скорость. Значение по умолчанию - 150
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfviewer/resolution/
---
## Свойство PdfViewer.Resolution

Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем медленнее скорость. Значение по умолчанию - 150.

```csharp
public int Resolution { get; set; }
```

## Примечания

Это свойство изменяет разрешение изображения в потоках преобразования страницы в изображение: когда [`PrintAsImage`](../printasimage/) установлено в `true`, или когда вызывается метод [`DecodePage`](../decodepage/) или [`DecodeAllPages`](../decodeallpages/). Чтобы установить разрешение принтера для прямой печати на принтер, используйте свойство [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) в классе [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### См. также

* класс [PdfViewer](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)