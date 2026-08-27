---
title: "XImageCollection.Add"
second_title: "Справочник API Aspose.PDF для .NET"
description: "XImageCollection метод. Добавляет новое изображение в список Image. Этот метод добавляет изображение как ссылку на тот же PdfObject, что позволяет уменьшить размер файла"
type: docs
weight: 70
url: /ru/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Добавляет новое изображение в Image list. Этот метод добавляет изображение как ссылку на тот же PdfObject (что позволяет уменьшить размер файла)

```csharp
public string Add(XImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | XImage | XImage для добавления. |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Добавляет объект в конец коллекции, чтобы объект можно было получить по последнему индексу.

```csharp
public string Add(Stream image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения (в формате JPEG). |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Добавляет объект в конец коллекции, чтобы объект можно было получить по последнему индексу.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Объект, содержащий массив пикселей и информацию о битмапе (Width, Height, PixelFormat). |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Добавляет объект в конец коллекции, чтобы объект можно было получить по последнему индексу.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения. |
| filterType | ImageFilterType | Тип фильтра изображения. |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Добавляет объект в конец коллекции, чтобы объект можно было получить по последнему индексу.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Объект, содержащий массив пикселей и информацию о битмапе (Width, Height, PixelFormat). |
| filterType | ImageFilterType | Тип фильтра изображения. |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Добавляет объект в конец коллекции, чтобы объект можно было получить по последнему индексу.

```csharp
public void Add(Stream image, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | Int32 | Качество JPEG. |

### См. также

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


