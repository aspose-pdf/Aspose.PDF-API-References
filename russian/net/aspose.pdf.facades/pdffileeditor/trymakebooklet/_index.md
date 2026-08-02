---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Создаёт буклет из входного файла в выходной файл."
type: docs
weight: 430
url: /ru/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Создает буклет из входного файла в выходной файл.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf‑файла. |
| outputFile | String | Путь и имя выходного pdf‑файла. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Создает буклет из InputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf‑поток. |
| outputStream | Stream | Выходной pdf‑поток. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Создает буклет из inputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf‑файла. |
| outputFile | String | Путь и имя выходного pdf‑файла. |
| pageSize | PageSize | Размер страницы выходного pdf‑файла. |

### Возвращаемое значение

True, если операция завершилась успешно.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Создает буклет из входного потока и сохраняет результат в выходной поток.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | Выходной pdf‑поток. |
| pageSize | PageSize | Размер страницы выходного pdf‑файла. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Создает пользовательский буклет из firstInputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf‑файла. |
| leftPages | Int32[] | Левые страницы буклета. |
| rightPages | Int32[] | Правые страницы буклета. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Создает пользовательский буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | Выходной pdf‑поток. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Создает пользовательский буклет из firstInputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf‑файла. |
| pageSize | PageSize | Размер страницы выходного pdf‑файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Создает буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | Выходной pdf‑поток. |
| pageSize | PageSize | Размер страницы выходного pdf‑файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


