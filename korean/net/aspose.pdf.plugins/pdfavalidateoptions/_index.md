---
title: Class PdfAValidateOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAValidateOptions 클래스. PDF 문서의 PDF/A 준수를 검증하기 위한 옵션을 나타냅니다.
type: docs
weight: 9030
url: /ko/net/aspose.pdf.plugins/pdfavalidateoptions/
---
## PdfAValidateOptions 클래스

[`PdfAConverter`](../pdfaconverter/) 플러그인을 사용하여 PDF 문서의 PDF/A 준수를 검증하기 위한 옵션을 나타냅니다.

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | PDF/A 변환 과정에서 텍스트 정렬을 유지하기 위해 추가 수단이 필요한지를 나타내는 값을 가져오거나 설정합니다. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 변환할 수 없는 객체에 대해 수행할 작업을 가져오거나 설정합니다. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | PDF/A 변환 과정에서 출력 파일 크기를 최소화하기 위해 글꼴을 제거하는 전략을 가져오거나 설정합니다. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | 문서에 포함될 수 없는 글꼴을 처리하기 위한 옵션을 가져옵니다. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | 기본 프로필 대신 PDF/A 변환에 사용할 ICC(International Color Consortium) 프로필의 파일 이름을 가져오거나 설정합니다. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | 데이터 소스의 컬렉션을 가져옵니다. |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | PDF/A 변환 과정에서 저메모리 모드가 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | 로그 출력을 위한 데이터 소스를 가져오거나 설정합니다. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | 원본 PDF 문서가 PDF 사양에 해당하지 않는 경우 PDF/A 변환을 제어하는 플래그를 가져옵니다. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | PDF/A 변환 과정에서 파일 크기를 줄이려고 시도할지를 나타내는 값을 가져오거나 설정합니다. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 검증 또는 변환에 사용할 PDF/A 표준의 버전을 가져오거나 설정합니다. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | PDF 문서에서 개인 사용 영역(PUA) 기호를 처리하기 위한 전략을 가져오거나 설정합니다. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | 소프트 마스크가 있는 이미지 변환 중 수행할 작업을 가져오거나 설정합니다. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | PDF/A 형식으로 변환할 때 상징적 글꼴을 인코딩하기 위한 전략을 가져오거나 설정합니다. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | PDF/A 변환 과정에서 유니코드 기호와 연결되지 않은 ToUnicode CMap 테이블을 처리하기 위한 규칙을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | 컬렉션에 새로운 데이터 소스를 추가합니다. |

### 참조

* 클래스 [PdfAOptionsBase](../pdfaoptionsbase/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)