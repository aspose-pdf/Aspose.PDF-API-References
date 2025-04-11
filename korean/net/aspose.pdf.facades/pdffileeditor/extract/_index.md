---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 입력 파일에서 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

입력 파일에서 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일 경로. |
| startPage | Int32 | 시작 페이지 번호. |
| endPage | Int32 | 끝 페이지 번호. |
| outputFile | String | 출력 Pdf 파일 경로. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

번호 배열로 지정된 페이지를 추출하여 새로운 PDF 파일로 저장합니다.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 경로. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputFile | String | 출력 파일 경로. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

입력 파일에서 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| startPage | Int32 | 시작 페이지 번호. |
| endPage | Int32 | 끝 페이지 번호. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

번호 배열로 지정된 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)