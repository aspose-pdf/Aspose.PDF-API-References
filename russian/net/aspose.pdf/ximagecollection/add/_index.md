---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Метод XImageCollection. Добавляет новое изображение в список изображений. Этот метод добавляет изображение как ссылку на тот же PdfObject, что позволяет уменьшить размер файла
type: docs
weight: 70
url: /ru/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Добавляет новое изображение в список изображений. Этот метод добавляет изображение как ссылку на тот же PdfObject (что позволяет уменьшить размер файла)

```csharp
public string Add(XImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | XImage | XImage, который нужно добавить. |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* класс [XImage](../../ximage/)
* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Добавляет сущность в конец коллекции, чтобы к сущности можно было получить доступ по последнему индексу.

```csharp
public string Add(Stream image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения (в формате JPEG). |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Добавляет сущность в конец коллекции, чтобы к сущности можно было получить доступ по последнему индексу.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Объект, содержащий массив пикселей и информацию о битмапе (Ширина, Высота, ФорматПикселей). |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* класс [BitmapInfo](../../bitmapinfo/)
* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Добавляет сущность в конец коллекции, чтобы к сущности можно было получить доступ по последнему индексу.

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

* перечисление [ImageFilterType](../../imagefiltertype/)
* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Добавляет сущность в конец коллекции, чтобы к сущности можно было получить доступ по последнему индексу.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Объект, содержащий массив пикселей и информацию о битмапе (Ширина, Высота, ФорматПикселей). |
| filterType | ImageFilterType | Тип фильтра изображения. |

### Возвращаемое значение

Имя добавленного изображения.

### См. также

* класс [BitmapInfo](../../bitmapinfo/)
* перечисление [ImageFilterType](../../imagefiltertype/)
* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Добавляет сущность в конец коллекции, чтобы к сущности можно было получить доступ по последнему индексу.

```csharp
public void Add(Stream image, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Stream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | Int32 | Качество JPEG. |

### См. также

* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)