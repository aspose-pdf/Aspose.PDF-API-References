---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Document 클래스. PDF 문서를 나타내는 클래스
type: docs
weight: 3780
url: /ko/net/aspose.pdf/document/
---
## Document 클래스

PDF 문서를 나타내는 클래스.

```csharp
public sealed class Document : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Document](document/#constructor)() | 빈 문서를 초기화합니다. |
| [Document](document/#constructor_1)(PdfVersion) | 버전에 따라 빈 문서를 초기화합니다. |
| [Document](document/#constructor_2)(Stream) | *입력* 스트림에서 새 Document 인스턴스를 초기화합니다. |
| [Document](document/#constructor_7)(string) | *파일 이름*을 사용하여 Document를 초기화합니다. [`Document`](./document/)와 동일합니다. |
| [Document](document/#constructor_4)(Stream, bool) | *입력* 스트림에서 새 Document 인스턴스를 초기화합니다. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | PDF 문서를 얻기 위해 필요한 변환을 제공하는 스트림에서 기존 문서를 엽니다. |
| [Document](document/#constructor_5)(Stream, string) | *입력* 스트림에서 새 Document 인스턴스를 초기화합니다. |
| [Document](document/#constructor_9)(string, bool) | *파일 이름*을 사용하여 Document를 초기화합니다. [`Document`](./document/)와 동일합니다. |
| [Document](document/#constructor_8)(string, LoadOptions) | PDF 문서를 얻기 위해 필요한 변환 옵션을 제공하는 파일에서 기존 문서를 엽니다. |
| [Document](document/#constructor_10)(string, string) | 암호화된 문서와 작업하기 위해 `Document` 클래스의 새 인스턴스를 초기화합니다. |
| [Document](document/#constructor_6)(Stream, string, bool) | *입력* 스트림에서 새 Document 인스턴스를 초기화합니다. |
| [Document](document/#constructor_11)(string, string, bool) | 암호화된 문서와 작업하기 위해 `Document` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | 문서 작업을 가져옵니다. 이 속성은 BeforClosing, BeforSaving 등의 작업을 가져오거나 설정할 수 있는 DocumentActions 클래스의 인스턴스입니다. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | 문서 크기를 최적화하기 위해 페이지 내용을 병합할 수 있습니다. 사용 시 서로 다른 페이지가 동일한 콘텐츠 객체를 참조할 수 있습니다. 이 모드는 다른 페이지가 변경될 때 페이지 내용이 변경되는 등의 부작용을 일으킬 수 있습니다. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | 문서의 배경 색상을 가져오거나 설정합니다. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | 문서의 창 위치가 화면 중앙에 배치될지를 지정하는 플래그를 가져오거나 설정합니다. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | 문서의 컬렉션을 가져옵니다. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | 문서가 암호화된 경우 보안 설정을 가져옵니다. 문서가 암호화되지 않은 경우 .net 1.1에서는 해당 예외가 발생하거나 다른 .net 버전에서는 CryptoAlgorithm이 null이 됩니다. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | 목적지 컬렉션을 가져옵니다. 더 이상 사용되지 않습니다. NamedDestinations를 사용하십시오. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | 텍스트의 읽기 순서를 가져오거나 설정합니다: L2R (왼쪽에서 오른쪽) 또는 R2L (오른쪽에서 왼쪽). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | 이 글꼴의 라이선스에 의해 금지된 경우 글꼴과 관련된 많은 작업을 실행할 수 없습니다. 예를 들어, 라이선스 규칙이 이 글꼴에 대한 포함을 비활성화하면 일부 글꼴은 PDF 문서에 포함될 수 없습니다. 이 플래그는 현재 PDF 문서의 모든 글꼴에 대한 라이선스 제한을 비활성화하는 데 사용됩니다. 이 플래그를 사용할 때는 주의하십시오. 이 플래그가 설정되면 이 플래그를 설정한 사람이 가능한 라이선스/법 위반에 대한 모든 책임을 지게 됩니다. 따라서 그는 자신의 위험을 감수합니다. 저작권법을 위반하지 않는다고 확신할 때만 이 플래그를 사용하는 것이 강력히 권장됩니다. 기본값은 false입니다. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | 문서의 창 제목 표시줄에 문서 제목을 표시할지를 지정하는 플래그를 가져오거나 설정합니다. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | 인쇄 대화 상자에서 파일을 인쇄할 때 사용할 인쇄 양면 모드 처리 옵션을 가져오거나 설정합니다. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | 문서에 포함된 파일의 컬렉션을 가져옵니다. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | 문서가 IsEmbedded 플래그가 true로 설정된 모든 표준 Type1 글꼴을 포함해야 함을 선언하는 속성입니다. 모든 PDF 글꼴은 IsEmbedded 플래그를 true로 설정하여 문서에 포함될 수 있지만, PDF 표준 Type1 글꼴은 이 규칙의 예외입니다. 표준 Type1 글꼴 포함은 많은 시간이 소요되므로 이러한 글꼴을 포함하려면 지정된 글꼴에 대해 IsEmbedded 플래그를 true로 설정하는 것뿐만 아니라 문서 수준에서 추가 플래그인 EmbedStandardFonts = true를 설정해야 합니다. 이 속성은 모든 글꼴에 대해 한 번만 설정할 수 있습니다. 기본값은 false입니다. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | 문서가 메모리에서 부분적으로 언로드될 수 있도록 하는 플래그를 가져오거나 설정합니다. 이는 메모리 사용량을 줄일 수 있지만 성능에 부정적인 영향을 미칠 수 있습니다. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | 서명 필드의 위생 관리를 위한 플래그를 가져오거나 설정합니다. 기본적으로 활성화되어 있습니다. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | 이 문서를 유발한 PDF 파일의 이름 |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | 문서 창이 첫 번째 표시된 페이지에 맞게 크기를 조정해야 하는지를 지정하는 플래그를 가져오거나 설정합니다. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities 인스턴스 |
| [Form](../../aspose.pdf/document/form/) { get; } | 문서의 Acro Form을 가져옵니다. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | 문서가 변경 사항과 함께 저장될 경우 예외를 발생시킵니다. |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | 문서가 활성화될 때 메뉴 바를 숨길지를 지정하는 플래그를 가져오거나 설정합니다. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | 문서가 활성화될 때 도구 모음을 숨길지를 지정하는 플래그를 가져오거나 설정합니다. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | 문서가 활성화될 때 사용자 인터페이스 요소를 숨길지를 지정하는 플래그를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf/document/id/) { get; } | ID를 가져옵니다. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | 소스 파일의 오류를 무시하는 플래그를 가져오거나 설정합니다. 소스 문서의 페이지가 대상 문서로 복사될 때, 이 플래그가 false인 경우 소스 파일의 일부 객체가 손상된 경우 복사 프로세스가 예외로 중단됩니다. 예: dest.Pages.Add(src.Pages); 이 플래그가 true로 설정되면 손상된 객체는 빈 값으로 대체됩니다. 기본값: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | 문서 정보를 가져옵니다. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | 문서의 암호화 상태를 가져옵니다. 문서가 암호화된 경우 true입니다. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | 문서가 선형화되었는지를 나타내는 값을 가져오거나 설정합니다. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | 문서가 pdfa 준수인지 여부를 가져옵니다. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | 문서가 pdfua 준수인지 여부를 가져옵니다. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | 문서가 pdfa 준수인지 여부를 가져오거나 설정합니다. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | 문서 수준의 JavaScript 컬렉션입니다. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | 문서의 논리적 구조를 가져옵니다. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | 문서 메타데이터입니다. (PDF 문서는 문서의 제목, 저자, 생성 및 수정 날짜와 같은 일반 정보를 포함할 수 있습니다. 문서에 대한 이러한 전반적인 정보(내용이나 구조와는 반대)는 메타데이터라고 하며 외부 데이터베이스에서 문서를 분류하고 검색하는 데 도움이 됩니다.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | 문서의 명명된 목적지 컬렉션입니다. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | 전체 화면 모드를 종료할 때 문서를 표시하는 방법을 지정하는 페이지 모드를 가져오거나 설정합니다. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | 문서 열기 시 수행되는 작업을 가져오거나 설정합니다. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | 최적화 플래그를 가져오거나 설정합니다. 페이지가 문서에 추가될 때, 이 플래그가 설정되면 결과 파일의 동일한 리소스 스트림이 하나의 PDF 객체로 병합됩니다. 이는 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 더 많은 메모리 요구 사항을 초래할 수 있습니다. 기본값: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | 문서의 개요를 가져옵니다. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | 문서의 출력 의도 컬렉션을 가져옵니다. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | 페이지 정보를 가져오거나 설정합니다.(생성자 전용, 문서를 읽을 때는 채워지지 않음) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | 문서의 페이지 레이블을 가져옵니다. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | 문서를 열 때 사용할 페이지 레이아웃을 가져오거나 설정합니다. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | 문서를 열 때 표시되는 방법을 지정하는 페이지 모드를 가져오거나 설정합니다. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | 문서 페이지의 컬렉션을 가져오거나 설정합니다. 페이지는 컬렉션에서 1부터 번호가 매겨집니다. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | PDF 형식을 가져옵니다. |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | 문서의 권한을 가져옵니다. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | PDF 페이지 크기를 사용하여 입력 용지 트레이를 선택할지를 지정하는 플래그를 가져오거나 설정합니다. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | 인쇄 대화 상자가 표시될 때 선택될 페이지 축척 옵션을 가져오거나 설정합니다. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | TaggedPdf 콘텐츠에 대한 액세스를 가져옵니다. |
| [Version](../../aspose.pdf/document/version/) { get; } | PDF 파일 헤더에서 PDF의 버전을 가져옵니다. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | 전체 파일을 메모리에 로드하기 위한 파일 크기 제한을 가져오고 설정합니다. 값은 메가바이트로 설정됩니다. 기본값은 210 Mb입니다. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | 시스템의 라이선스 상태를 가져옵니다. 시스템이 라이선스 모드에서 작동하면 true를 반환하고 그렇지 않으면 false를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | 문서를 병합합니다. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | PDF 파일을 병합합니다. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | 문서를 병합합니다. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | 문서를 병합합니다. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | XML을 문서에 바인딩합니다. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | XML을 문서에 바인딩합니다. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | XML/XSL을 문서에 바인딩합니다. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | XML/XSL을 문서에 바인딩합니다. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | XML/XSL을 문서에 바인딩합니다. |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | 문서 비밀번호를 변경합니다. 이 작업은 소유자 비밀번호를 사용하여만 수행할 수 있습니다. |
| [Check](../../aspose.pdf/document/check/)(bool) | 문서를 검증합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | 지정된 변환 옵션을 사용하여 문서를 변환합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | 문서 내 이미지를 인식하고 그 위에 hocr 문자열을 추가합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | 문서 내 이미지를 인식하고 그 위에 hocr 문자열을 추가합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | 문서를 변환하고 오류를 지정된 스트림에 저장합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Fixup을 적용하여 문서를 변환합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Fixup을 적용하여 문서를 변환합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | 페이지를 PNG로 변환하여 DSR, OMR, OCR 이미지 스트림을 생성합니다. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | 문서의 암호를 해제합니다. 그런 다음 저장하여 해제된 버전을 얻습니다. |
| [Dispose](../../aspose.pdf/document/dispose/)() | 이 문서에서 사용된 모든 리소스를 닫습니다. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | 문서를 암호화합니다. 그런 다음 저장하여 암호화된 버전을 얻습니다. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | 문서를 암호화합니다. 그런 다음 저장하여 암호화된 버전을 얻습니다. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | 문서를 암호화합니다. 그런 다음 저장하여 암호화된 버전을 얻습니다. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | 모든 문서 주석을 스트림으로 내보냅니다. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | 모든 문서 주석을 XFDF 파일로 내보냅니다. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | 문서에서 모든 필드를 제거하고 그 값을 대신 배치합니다. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | 문서에서 모든 필드(및 주석)를 제거하고 그 값을 대신 배치합니다. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | 투명한 콘텐츠를 비투명한 래스터 및 벡터 그래픽으로 대체합니다. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | 메모리를 정리합니다. |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | 카탈로그 사전에서 항목 값을 반환합니다. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | 문서에서 지정된 ID를 가진 객체를 가져옵니다. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | 문서에서 XMP 메타데이터를 가져옵니다. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | 현재 PDF 문서가 증분 업데이트로 저장되었는지를 확인합니다. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | 스트림에서 문서로 주석을 가져옵니다. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF 파일에서 문서로 주석을 가져옵니다. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | 문서가 Repair 메서드 호출이 필요한지를 확인합니다. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | 파일을 로드하고 PDF로 변환합니다. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | 문서를 병합합니다. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | PDF 파일을 병합합니다. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | 문서를 병합합니다. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | 문서를 병합합니다. |
| [Optimize](../../aspose.pdf/document/optimize/)() | 문서를 선형화하여 - 첫 페이지를 가능한 한 빨리 열 수 있도록; - 다음 페이지를 가능한 한 빨리 표시하거나 다음 페이지로의 링크를 따를 수 있도록; - 느린 채널을 통해 페이지 데이터가 제공될 때 페이지를 점진적으로 표시할 수 있도록(가장 유용한 데이터를 먼저 표시); - 전체 페이지가 수신되고 표시되기 전에 링크를 따르는 것과 같은 사용자 상호작용을 수행할 수 있도록 합니다. 이 메서드를 호출해도 문서가 실제로 저장되지는 않습니다. 오히려 문서는 최적화된 구조를 갖도록 준비되며, 그런 다음 저장하여 최적화된 문서를 얻습니다. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | 문서의 리소스를 최적화합니다: 1. 문서 페이지에서 사용되지 않는 리소스가 제거됩니다; 2. 동일한 리소스가 하나의 객체로 결합됩니다; 3. 사용되지 않는 객체가 삭제됩니다. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | 정의된 최적화 전략에 따라 문서의 리소스를 최적화합니다. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | 문서의 페이지 트리 노드를 균형 잡힌 트리로 구성합니다. 문서에 nodesNumInSubtrees 페이지 객체가 초과하는 경우에만 작동하며, 그렇지 않으면 아무 작업도 수행하지 않습니다. Pages 요소를 반복하는 동안 이 메서드를 호출하지 마십시오. 예측할 수 없는 결과를 초래할 수 있습니다. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | 생성기를 위한 단락을 처리합니다. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | 문서에서 메타데이터를 제거합니다. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | 문서에서 pdfa 준수를 제거합니다. |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/) | 문서에서 pdfUa 준수를 제거합니다. |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | 손상된 문서를 복구합니다. |
| [Save](../../aspose.pdf/document/save/#save)() | 문서를 증분적으로 저장합니다(즉, 증분 업데이트 기술을 사용하여). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | 저장 옵션으로 문서를 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | 문서를 스트림에 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | 지정된 파일에 문서를 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | 새 이름과 함께 파일 형식으로 문서를 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | 저장 옵션으로 스트림에 문서를 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | 새 이름과 함께 파일 형식으로 문서를 저장합니다. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | 새 이름과 함께 저장 옵션을 설정하여 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | 문서를 증분적으로 저장합니다(즉, 증분 업데이트 기술을 사용하여). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | 저장 옵션으로 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | 문서를 스트림에 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | 지정된 파일에 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | 새 이름과 함께 파일 형식으로 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | 저장 옵션으로 스트림에 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | 새 이름과 함께 파일 형식으로 문서를 저장합니다. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | 새 이름과 함께 저장 옵션을 설정하여 문서를 저장합니다. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | 문서를 XML로 저장합니다. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | 전체 문서를 문서 장치로 전송하여 처리합니다. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | 전체 문서를 문서 장치로 전송하여 처리합니다. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | 문서의 특정 페이지를 문서 장치로 전송하여 처리합니다. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | 전체 문서를 문서 장치로 전송하여 처리합니다. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | PDF 문서의 제목을 설정합니다. |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | 문서의 XMP 메타데이터를 설정합니다. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | 지정된 파일로 문서를 검증합니다. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | 지정된 파일로 문서를 검증합니다. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | 지정된 파일로 문서를 검증합니다. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | 소스 형식의 스트림을 대상 형식의 스트림으로 변환합니다. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | 소스 형식의 스트림을 대상 형식의 대상 파일로 변환합니다. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | 소스 형식의 소스 파일을 대상 형식의 스트림으로 변환합니다. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | 소스 형식의 소스 파일을 대상 형식의 대상 파일로 변환합니다. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | 전체 파일을 메모리에 로드하기 위한 파일 크기 제한을 기본값인 210 Mb로 설정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | 문서에서 글꼴이 다른 글꼴로 대체될 때 발생합니다. |

## 기타 구성원

| 이름 | 설명 |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | FontSubstitution 이벤트를 처리할 메서드를 나타냅니다. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | 글꼴 조정 기능을 보유합니다. |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | 병합 메서드의 옵션을 나타냅니다. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | PDF 문서를 복구하기 위한 옵션을 나타냅니다. |

### 참조

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)