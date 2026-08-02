---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Разделяет PDF‑файл от первой страницы до указанного места и сохраняет переднюю часть как новый файл"
type: docs
weight: 460
url: /ru/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Разделяет Pdf файл с первой страницы до указанного места и сохраняет переднюю часть как новый файл.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf‑файл. |
| место | Int32 | Точка разделения. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TrySplitFromFirst аналогичен методу SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Разделяет от начала до указанного места и сохраняет переднюю часть в выходной поток.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного Pdf‑файла. |
| место | Int32 | Точка разделения. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Потоки НЕ закрываются после этой операции. Метод TrySplitFromFirst аналогичен методу SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


