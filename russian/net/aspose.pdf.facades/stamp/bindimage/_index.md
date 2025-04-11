---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Метод Stamp. Устанавливает изображение в качестве штампа
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Устанавливает изображение в качестве штампа.

```csharp
public void BindImage(string imageFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | String | Имя файла изображения и путь. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Устанавливает изображение, которое будет использоваться в качестве штампа.

```csharp
public void BindImage(Stream image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения. |

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)