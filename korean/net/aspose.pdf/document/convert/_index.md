---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: 문서 메서드. 문서를 변환하고 오류를 지정된 파일에 저장합니다.
type: docs
weight: 580
url: /ko/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

문서를 변환하고 오류를 지정된 파일에 저장합니다.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputLogFileName | 문자열 | 주석이 저장될 파일의 경로입니다. |
| format | PdfFormat | PDF 형식입니다. |
| action | ConvertErrorAction | 변환할 수 없는 객체에 대한 작업입니다. |
| transparencyAction | ConvertTransparencyAction | 이미지 마스킹 객체에 대한 작업입니다. |

### 반환 값

작업 결과

### 참조

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

문서를 변환하고 오류를 지정된 파일에 저장합니다.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputLogStream | 스트림 | 주석이 저장될 스트림입니다. |
| format | PdfFormat | PDF 형식입니다. |
| action | ConvertErrorAction | 변환할 수 없는 객체에 대한 작업입니다. |
| transparencyAction | ConvertTransparencyAction | 이미지 마스킹 객체에 대한 작업입니다. |

### 반환 값

작업 결과

### 참조

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

문서를 변환하고 오류를 지정된 파일에 저장합니다.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputLogFileName | 문자열 | 주석이 저장될 파일의 경로입니다. |
| format | PdfFormat | PDF 형식입니다. |
| action | ConvertErrorAction | 변환할 수 없는 객체에 대한 작업입니다. |

### 반환 값

작업 결과

### 참조

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

지정된 변환 옵션을 사용하여 문서를 변환합니다.

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | PdfFormatConversionOptions | PDF 문서를 변환하기 위한 옵션 세트입니다. |

### 반환 값

작업 결과

### 참조

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

문서 내 이미지를 인식하고 그 위에 hocr 문자열을 추가합니다.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | hocr 인식으로 처리될 이미지에 대한 작업입니다. |
| flattenImages | 불리언 | PDF 이미지의 텍스트는 마스크의 메커니즘을 사용하여 그릴 수 있으며, 이 경우 이미지는 평탄화되어야 합니다. |

### 반환 값

작업 결과. 문서에 이미지가 없으면 !:false를 반환합니다.

### 참조

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

문서 내 이미지를 인식하고 그 위에 hocr 문자열을 추가합니다.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| callback | CallBackGetHocr | hocr 인식으로 처리될 이미지에 대한 작업입니다. |
| flattenImages | 불리언 | PDF 이미지의 텍스트는 마스크의 메커니즘을 사용하여 그릴 수 있으며, 이 경우 이미지는 평탄화되어야 합니다. |

### 반환 값

작업 결과. 문서에 이미지가 없으면 !:false를 반환합니다.

### 참조

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

문서를 변환하고 오류를 지정된 스트림에 저장합니다.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputLogStream | 스트림 | 주석이 저장될 스트림입니다. |
| format | PdfFormat | PDF 형식입니다. |
| action | ConvertErrorAction | 변환할 수 없는 객체에 대한 작업입니다. |

### 반환 값

작업 결과

### 참조

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Fixup을 적용하여 문서를 변환합니다.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixup | Fixup | Fixup 유형입니다. |
| outputLog | 스트림 | 프로세스의 로그입니다. |
| onlyValidation | 불리언 | 문서 유효성 검사만 수행합니다. |
| parameters | Object[] | 설정할 수 없는 Fixup 속성입니다. |

### 반환 값

작업 결과입니다.

### 참조

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Fixup을 적용하여 문서를 변환합니다.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixup | Fixup | Fixup 유형입니다. |
| outputLog | 문자열 | 프로세스의 로그입니다. |
| onlyValidation | 불리언 | 문서 유효성 검사만 수행합니다. |
| parameters | Object[] | 설정할 수 없는 Fixup 속성입니다. |

### 반환 값

작업 결과입니다.

### 참조

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

소스 파일을 소스 형식에서 대상 파일의 대상 형식으로 변환합니다.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | 문자열 | 소스 파일 이름입니다. |
| loadOptions | LoadOptions | 소스 파일 형식입니다. |
| dstFileName | 문자열 | 대상 파일 이름입니다. |
| saveOptions | SaveOptions | 대상 파일 형식입니다. |

### 참조

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

소스 형식의 스트림을 대상 형식의 대상 파일로 변환합니다.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcStream | 스트림 | 소스 스트림입니다. |
| loadOptions | LoadOptions | 소스 스트림 형식입니다. |
| dstFileName | 문자열 | 대상 파일 이름입니다. |
| saveOptions | SaveOptions | 대상 파일 형식입니다. |

### 참조

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

소스 파일을 소스 형식에서 대상 형식의 스트림으로 변환합니다.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | 문자열 | 소스 파일 이름입니다. |
| loadOptions | LoadOptions | 소스 파일 형식입니다. |
| dstStream | 스트림 | 대상 스트림입니다. |
| saveOptions | SaveOptions | 대상 스트림 형식입니다. |

### 참조

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

소스 형식의 스트림을 대상 형식의 스트림으로 변환합니다.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcStream | 스트림 | 소스 스트림입니다. |
| loadOptions | LoadOptions | 소스 스트림 형식입니다. |
| dstStream | 스트림 | 대상 스트림입니다. |
| saveOptions | SaveOptions | 대상 파일 형식입니다. |

### 참조

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)