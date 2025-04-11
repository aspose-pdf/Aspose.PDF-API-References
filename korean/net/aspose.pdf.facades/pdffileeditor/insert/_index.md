---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 다른 파일에서 Pdf 파일의 특정 위치에 페이지를 삽입합니다.
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

다른 파일에서 Pdf 파일의 특정 위치에 페이지를 삽입합니다.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| insertLocation | Int32 | 입력 파일의 위치. |
| portFile | String | 포팅할 Pdf 파일. |
| startPage | Int32 | portFile의 시작 위치. |
| endPage | Int32 | portFile의 끝 위치. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

다른 파일에서 입력 Pdf 파일로 페이지를 삽입합니다.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | Pdf 파일의 입력 스트림. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portStream | Stream | 페이지를 위한 Pdf 파일의 스트림. |
| startPage | Int32 | 시작할 페이지. |
| endPage | Int32 | 끝낼 페이지. |
| outputStream | Stream | 출력 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

다른 파일에서 입력 Pdf 파일로 페이지를 삽입합니다.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portFile | String | Pdf 파일의 페이지. |
| pageNumber | Int32[] | portFile에서 포팅된 페이지 번호. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

다른 파일에서 입력 Pdf 파일로 페이지를 삽입합니다.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | Pdf 파일의 입력 스트림. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portStream | Stream | 페이지를 위한 Pdf 파일의 스트림. |
| pageNumber | Int32[] | portFile에서 포팅된 페이지 번호. |
| outputStream | Stream | 출력 스트림. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)