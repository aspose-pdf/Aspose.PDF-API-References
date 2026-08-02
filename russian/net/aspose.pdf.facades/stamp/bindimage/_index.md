---
title: "Stamp.BindImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Stamp. Устанавливает изображение в качестве штампа"
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Устанавливает изображение как штамп.

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


