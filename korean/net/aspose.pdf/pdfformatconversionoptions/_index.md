---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptions 클래스. PDF 문서를 변환하기 위한 옵션 집합을 나타냅니다.
type: docs
weight: 8380
url: /ko/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions 클래스

PDF 문서를 변환하기 위한 옵션 집합을 나타냅니다.

```csharp
public class PdfFormatConversionOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | 생성자 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | 생성자 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | 생성자 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | 생성자 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | 생성자 |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | 기본 매개변수를 가진 PdfFormatConversionOptions 객체를 가져옵니다. |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | 이 플래그는 변환된 문서에서 텍스트 정렬을 제어합니다. 기본적으로 문서 변환은 텍스트 정렬에 영향을 미치지 않으며 텍스트를 그대로 둡니다. 그러나 경우에 따라 글꼴 대체로 인해 변환된 문서에서 텍스트가 겹치거나 여분의 공백이 발생할 수 있습니다. 이 플래그가 설정되면 특별한 정렬 작업이 수행됩니다. 이 플래그는 겹친 텍스트나 여분의 텍스트 공백 문제가 있는 문서에 대해서만 설정해야 하며, 이 플래그를 사용하면 성능이 저하되고 경우에 따라 텍스트 내용이 손상될 수 있습니다. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | 소프트 마스크가 있는 이미지에 대한 작업입니다. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 변환할 수 없는 객체에 대한 작업입니다. |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 불필요한 글꼴을 제외하고 문서 파일 크기를 줄이기 위한 전략입니다. 이 매개변수는 [`OptimizeFileSize`](./optimizefilesize/) 플래그가 true로 설정된 경우에만 의미가 있습니다. 기본적으로 SubsetFonts와 RemoveDuplicatedFonts 전략의 조합이 사용됩니다. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | PDF 문서에 일부 글꼴을 포함할 수 없는 경우의 옵션입니다. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 형식입니다. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | ICC 프로필 이름의 파일 이름을 가져오거나 설정합니다. null인 경우 기본 ICC 프로필이 사용됩니다. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 이미지 스트림을 비동기 모드로 실행할지 여부를 가져오거나 설정합니다. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 저메모리 변환 모드가 활성화되어 있는지 여부입니다. |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | PDF 2.0으로 변환할 때 Info에서 Metadata로 데이터를 전달할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | 주석이 저장될 파일의 경로입니다. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | 주석이 저장될 스트림입니다. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | 원본 문서가 PDF/A 사양에 부합하지 않는 경우 PDF/A 변환 프로세스를 제어하는 플래그를 보유합니다. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | 이 속성은 외부 속성입니다. 마지막 PDF/A 변환에서 컴퓨터에서 발견되지 않은 모든 글꼴(글꼴 이름)을 보유합니다. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | PDF/A 문서를 파일 크기를 줄이기 위해 특별한 변환 모드를 활성화/비활성화하는 플래그를 가져오거나 설정합니다. 현재 이 플래그는 PDF 문서에서 사용되는 글꼴의 최적화에 영향을 미치며, 향후 이 플래그는 그래픽과 같은 다른 데이터 구조의 최적화를 전환하는 데에도 사용될 수 있습니다. 이 플래그와 모드를 설정하면 파일 크기를 크게 줄일 수 있지만 동시에 변환 성능이 크게 저하될 수 있습니다. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | PDF 형식 변환을 위한 [`OutputIntent`](../outputintent/)을 가져오거나 설정합니다. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | 유니코드 개인 사용 영역(PUA)에서 기호를 처리하기 위한 전략입니다. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | 상징적 TrueType 글꼴에 여러 인코딩 서브테이블이 있는 경우 상징적 글꼴에 대한 인코딩 데이터를 복사하기 위한 전략입니다. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | 이미지 마스킹 객체에 대한 작업입니다. |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | 유니코드 매핑 문제를 해결하기 위한 규칙입니다. null일 수 있습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | 텍스트를 정렬하기 위한 전략입니다. 이 매개변수는 [`AlignText`](./aligntext/) 플래그가 true로 설정된 경우에만 의미가 있습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)