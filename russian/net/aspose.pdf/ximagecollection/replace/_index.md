---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: Метод XImageCollection. Заменить изображение в коллекции на другое изображение
type: docs
weight: 150
url: /ru/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Заменить изображение в коллекции на другое изображение.

```csharp
public void Replace(int index, Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс элемента коллекции, который будет заменен в диапазоне [1..количество изображений]. |
| stream | Stream | Поток, содержащий данные изображения (в формате JPEG). |

### См. также

* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Заменить изображение в коллекции на другое изображение.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс элемента коллекции, который будет заменен в диапазоне [1..количество изображений]. |
| stream | Stream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | Int32 | Качество сжатия JPEG, в процентах (допустимые значения от 0 до 100). |
| isBlackAndWhite | Boolean | Если true, изображение сжимается с помощью метода сжатия CCITT, который обеспечивает лучшее сжатие для черно-белых изображений. Может использоваться только для черно-белых изображений. |

### См. также

* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Заменить изображение в коллекции на другое изображение.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс элемента коллекции, который будет заменен в диапазоне [1..количество изображений]. |
| stream | Stream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | Int32 | Качество JPEG. |

### См. также

* класс [XImageCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)