---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer 메서드. 지정된 가져오기 형식을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 스트림을 생성하는 방법을 보여줍니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

지정된 가져오기 형식을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 스트림을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| format | ImportFormat | 가져오기 형식. |
| outputStream | Stream | 출력 PDF 스트림. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 입력 또는 출력 스트림이 null입니다. |

### 참조

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

지정된 가져오기 형식을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 파일에서 PDF 스트림을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileName | String | 입력 파일 이름. |
| format | ImportFormat | 가져오기 형식. |
| outputStream | Stream | 출력 PDF 스트림. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 출력 스트림이 null입니다. |
| ArgumentException | 입력 파일 이름이 빈 문자열입니다. |

### 참조

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

지정된 가져오기 형식을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 파일을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| format | ImportFormat | 가져오기 형식. |
| outputFileName | String | 출력 PDF 파일. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 입력 스트림이 null입니다. |
| ArgumentException | 출력 파일 이름이 빈 문자열입니다. |

### 참조

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

지정된 가져오기 형식을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileName | String | 입력 파일 이름. |
| format | ImportFormat | 가져오기 형식. |
| outputFileName | String | 출력 PDF 파일. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentException | 입력 또는 출력 파일 이름이 빈 문자열입니다. |

### 참조

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

지정된 가져오기 옵션을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 파일에서 PDF 스트림을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, importOptions, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileName | String | 입력 파일 이름. |
| options | ImportOptions | 가져오기 옵션. |
| outputStream | Stream | 출력 PDF 스트림. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 출력 스트림이 null입니다. |
| ArgumentException | 입력 파일 이름이 빈 문자열입니다. |

### 참조

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 파일을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputFile);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| options | ImportOptions | 가져오기 옵션. |
| outputFileName | String | 출력 PDF 파일. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 입력 스트림이 null입니다. |
| ArgumentException | 출력 파일 이름이 빈 문자열입니다. |

### 참조

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileName | String | 입력 파일 이름. |
| options | ImportOptions | 가져오기 옵션. |
| outputFileName | String | 출력 PDF 스트림. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentException | 입력 또는 출력 파일 이름이 빈 문자열입니다. |

### 참조

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 스트림을 생성하는 방법을 보여줍니다.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| options | ImportOptions | 가져오기 옵션. |
| outputStream | Stream | 출력 PDF 스트림. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | 파일이 유효하지 않을 때 예외가 발생합니다. |
| ArgumentNullException | 입력 또는 출력 스트림이 null입니다. |

### 참조

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)