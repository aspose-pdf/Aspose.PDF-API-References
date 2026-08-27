---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 메서드. PDF 문서에서 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

PDF 문서에서 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool GetNextImage(string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지가 저장될 파일 |

### 반환 값

이미지가 성공적으로 추출된 경우 true

## 예제

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

PDF 문서에서 지정된 이미지 형식으로 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 이미지가 저장될 파일 |
| 포맷 | ImageFormat | 이미지의 형식. |

### 반환 값

이미지가 성공적으로 추출된 경우 true

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

PDF 파일에서 다음 이미지를 가져와 지정된 이미지 형식으로 스트림에 저장합니다.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지 데이터가 저장될 스트림 |
| 포맷 | ImageFormat | 이미지의 형식. |

### 반환 값

이미지가 성공적으로 추출된 경우 true.

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

PDF 파일에서 다음 이미지를 가져와 스트림에 저장합니다.

```csharp
public bool GetNextImage(Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 이미지 데이터가 저장될 스트림 |

### 반환 값

이미지가 성공적으로 추출된 경우 true.

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


