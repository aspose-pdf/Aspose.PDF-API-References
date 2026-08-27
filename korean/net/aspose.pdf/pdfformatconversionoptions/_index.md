---
title: "PdfFormatConversionOptions 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfFormatConversionOptions 클래스. PDF 문서를 변환하기 위한 옵션 집합을 나타냅니다."
type: docs
weight: 8520
url: /ko/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

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
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | 기본 매개변수를 사용하여 PdfFormatConversionOptions 객체를 가져옵니다 |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | 이 플래그는 변환된 문서의 텍스트 정렬을 제어합니다. 기본적으로 문서 변환은 텍스트 정렬에 영향을 주지 않으며 텍스트를 그대로 유지합니다. 그러나 경우에 따라 글꼴 대체로 인해 변환된 문서에서 텍스트가 겹치거나 여분의 공백이 발생할 수 있습니다. 이 플래그가 설정되면 특수 정렬 작업이 수행됩니다. 이 플래그는 텍스트 겹침이나 여분의 공백 문제가 있는 문서에만 설정해야 하며, 플래그 사용은 성능을 저하시키고 경우에 따라 텍스트 내용이 손상될 수 있습니다. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | PDF 형식 변환 중 자동 태깅 설정을 가져오거나 설정합니다. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | 소프트 마스크가 있는 이미지에 대한 동작. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 변환할 수 없는 객체에 대한 동작 |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 불필요한 글꼴을 제외하고 문서 파일 크기를 줄이기 위한 전략(들). 이 매개변수는 플래그 [`OptimizeFileSize`](./optimizefilesize/)가 true로 설정된 경우에만 의미가 있습니다. 기본적으로 SubsetFonts와 RemoveDuplicatedFonts 전략의 조합이 사용됩니다. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | 일부 글꼴을 PDF 문서에 포함할 수 없는 경우에 대한 옵션. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 형식. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | icc 프로파일 이름의 파일명을 가져오거나 설정합니다. null인 경우 기본 icc 프로파일이 사용됩니다. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 비동기 모드에서 이미지 스트림 실행을 가져오거나 설정합니다. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 저 메모리 변환 모드가 활성화되어 있습니까 |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | PDF 2.0으로 변환할 때 Info에서 Metadata로 데이터를 전달할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | 댓글이 저장될 파일 경로. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | 댓글이 저장될 스트림. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | 원본 문서가 PDF/A 사양에 부합하지 않는 경우에 PDF/A 변환 프로세스를 제어하는 플래그를 보유합니다. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | 이 속성은 외부 속성입니다. 마지막 PDF/A 변환 시 컴퓨터에서 찾을 수 없었던 모든 글꼴(글꼴 이름)을 보유합니다. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | PDF/A 문서의 파일 크기를 줄이기 위한 특수 변환 모드를 활성화/비활성화하는 플래그를 가져오거나 설정합니다. 현재 이 플래그는 PDF 문서에 사용된 글꼴 최적화에 영향을 주며, 향후에는 그래픽과 같은 다른 데이터 구조에 대한 최적화를 켜는 데에도 사용될 수 있습니다. 이 플래그와 모드의 조합은 파일 크기를 크게 줄일 수 있지만 동시에 변환 성능을 크게 저하시킬 수 있습니다. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | PDF 형식 변환을 위한 [`OutputIntent`](../outputintent/)을 가져오거나 설정합니다. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | 유니코드 Private Use Area(PUA)에서 기호를 처리하기 위한 전략. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | 상징 TrueType 글꼴에 인코딩 서브테이블이 둘 이상 있는 경우, 상징 글꼴의 인코딩 데이터를 복사하는 전략. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | 이미지 마스크 객체에 대한 동작 |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | 유니코드 매핑 문제를 해결하기 위한 규칙. null일 수 있습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | 텍스트 정렬을 위한 전략. 이 매개변수는 플래그 [`AlignText`](./aligntext/)가 true로 설정된 경우에만 의미가 있습니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


