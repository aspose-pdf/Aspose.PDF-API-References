---
title: "PdfFileEditor.Concatenate"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 두 파일을 연결합니다"
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

두 파일을 연결합니다.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 연결할 첫 번째 파일. |
| secInputFile | String | 연결할 두 번째 파일. |
| outputFile | String | 출력 파일. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

두 파일을 연결합니다.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 파일의 스트림. |
| secInputStream | Stream | 두 번째 파일의 스트림. |
| outputStream | Stream | 결과 파일이 저장될 스트림. |

### 반환 값

작업이 성공하면 true.

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

문서를 연결합니다.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| src | Document[] | 소스 문서 배열. |
| dest | Document | 대상 문서. |

### 반환 값

연결이 성공하면 true.

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

파일을 하나의 파일로 연결합니다.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 연결할 파일 배열. |
| outputFile | String | 출력 파일 이름. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

파일을 연결합니다

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream[] | 연결될 스트림 배열. |
| outputStream | Stream | 결과 파일이 저장될 스트림. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 파일. |
| secInputFile | String | 두 번째 파일. |
| blankPageFile | String | 빈 페이지가 있는 PDF 파일. |
| outputFile | String | 결과 파일. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 Pdf 스트림. |
| secInputStream | Stream | 두 번째 Pdf 스트림. |
| blankPageStream | Stream | 빈 페이지가 있는 Pdf 스트림. |
| outputStream | Stream | 출력 Pdf 스트림. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


