---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет Pdf файл с первой страницы на указанное место и сохраняет переднюю часть как новый файл
type: docs
weight: 460
url: /ru/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Разделяет Pdf файл с первой страницы на указанное место и сохраняет переднюю часть как новый файл.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf файл. |
| location | Int32 | Точка разделения. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успехе, или false.

## Примечания

Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Разделяет с начала на указанное место и сохраняет переднюю часть в выходной поток.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного Pdf файла. |
| location | Int32 | Точка разделения. |
| outputStream | Stream | Выходной поток файла. |

### Возвращаемое значение

True при успехе, или false.

## Примечания

Потоки НЕ закрываются после этой операции. Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Разделяет документ с первой страницы на место и сохраняет результат в объекты HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| location | Int32 | Точка разделения. |
| response | HttpResponse | Объекты HttpResponse. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Разделяет документ с начала на указанное место и сохраняет результат в объект HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| location | Int32 | Точка разделения. |
| response | HttpResponse | Объект HttpResponse, в котором будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)