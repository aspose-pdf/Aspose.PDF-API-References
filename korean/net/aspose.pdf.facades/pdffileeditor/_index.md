---
title: "클래스 PdfFileEditor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileEditor 클래스. PDF 파일 연결, 분할, 페이지 추출, 소책자 만들기 등 작업을 구현합니다."
type: docs
weight: 4580
url: /ko/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

PDF 파일에 대한 작업을 구현합니다: 병합, 분할, 페이지 추출, 소책자 만들기 등.

```csharp
public sealed class PdfFileEditor
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | true로 설정하면 작업 후 스트림이 닫힙니다. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | UseDiskBuffer가 true로 설정된 경우, 연결 중 새로운 증분 업데이트가 이루어지기 전에 연결된 문서 수. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | 변환 프로세스의 로그를 가져옵니다. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | PDF 파일 형식을 설정합니다. 결과 파일은 지정된 파일 형식으로 저장됩니다. 이 속성이 지정되지 않으면 파일은 변환 없이 기본 PDF 형식으로 저장됩니다. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | true이면 연결 수행 시 파일의 논리 구조가 복사됩니다. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | true이면 개요가 복사됩니다. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | 이 속성은 연결 과정에서 손상된 파일을 만났을 때의 동작을 정의합니다. 가능한 값은: StopWithError 및 ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | 연결이 수행될 때 발생한 문제들의 배열입니다. Concatenate() 함수에 전달된 각 손상된 문서마다 새로운 CorruptedItem 항목이 생성됩니다. 이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted인 경우에만 사용할 수 있습니다. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | true이면 연결 중에 증분 업데이트가 수행됩니다. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | true이면 작업이 원본 문서에서 복사됩니다. 기본값: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | true이면 양식을 연결할 때 필드 이름이 고유하게 만들어집니다. 필드 이름에 접미사가 추가되며, 접미사 템플릿은 UniqueSuffix 속성에서 지정할 수 있습니다. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | 마지막 발생한 예외를 가져옵니다. 실패 원인을 확인하는 데 사용할 수 있습니다. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | 이 속성이 true이면 동일한 이름을 가진 연결된 문서의 선택적 내용이 결과 문서의 하나의 레이어로 병합됩니다. 그렇지 않으면 동일한 이름의 레이어가 결과 문서에서 별개의 레이어로 저장됩니다. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | true이면 중복된 개요가 병합됩니다. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | 최적화 플래그를 가져오거나 설정합니다. 결과 파일에서 동일한 리소스 스트림은 이 플래그가 설정된 경우 하나의 PDF 객체로 병합됩니다. 이는 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 메모리 요구량이 증가할 수 있습니다. 기본값: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | 소스 입력 PDF 파일이 암호화된 경우 소유자 비밀번호를 설정합니다. 이 속성은 아직 구현되지 않았습니다. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | true이면 첫 번째 문서의 사용자 권한이 연결된 문서에 적용됩니다. 다른 모든 문서의 사용자 권한은 무시됩니다. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | true이면 모든 서명이 필드에서 제거됩니다(필드는 남습니다); 그렇지 않으면 잘못된 서명이 발생할 수 있습니다. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | 양식을 연결할 때 필드 이름을 고유하게 만들기 위해 추가되는 접미사의 형식입니다. 이 문자열은 숫자로 대체될 %NUM% 부분을 포함해야 합니다. 예를 들어 UniqueSuffix = "ABC%NUM%"인 경우 필드 "fieldName"의 이름은 fieldNameABC1, fieldNameABC2, fieldNameABC3 등으로 됩니다. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | 이 옵션을 사용하면 대상 문서가 주기적으로 디스크에 저장되고 이후 연결이 증분 업데이트로 적용됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 기본 공간 단위로 지정됩니다. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 기본 공간 단위로 지정됩니다. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 초기 페이지 크기의 퍼센트로 지정됩니다. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 초기 페이지 크기의 퍼센트로 지정됩니다. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | 문서 페이지에 페이지 구분을 추가합니다. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | 문서 페이지에 페이지 구분을 추가합니다. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | 문서 페이지에 페이지 구분을 추가합니다. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | portStream에서 startPage부터 endPage까지의 범위에서 선택된 페이지를 firstInputStream의 끝에 있는 portStream에 추가합니다. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portStreams 문서의 페이지가 포함됩니다. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | portFile에서 startPage부터 endPage까지의 범위에서 선택된 페이지를 firstInputFile의 끝에 있는 portFile에 추가합니다. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | portFiles 문서에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portFiles 문서의 페이지가 포함됩니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | 문서를 연결합니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | 파일을 연결합니다 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | 파일을 하나의 파일로 연결합니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | 두 파일을 연결합니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | 두 파일을 연결합니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | 두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | 두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | 번호 배열로 지정된 페이지를 추출하여 새로운 Pdf 파일로 저장합니다. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | 번호 배열로 지정된 페이지를 추출하여 새로운 PDF 파일로 저장합니다. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | 입력 파일에서 페이지를 추출하고 새로운 Pdf 파일로 저장합니다. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | 입력 파일에서 페이지를 추출하고 새로운 Pdf 파일로 저장합니다. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | 다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | 다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | 다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | 다른 파일에서 페이지를 삽입하여 Pdf 파일의 지정 위치에 넣습니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | InputStream에서 outputStream으로 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | 입력 파일에서 출력 파일로 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | 입력 스트림에서 소책자를 만들고 결과를 output stream에 저장합니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | inputFile에서 outputFile로 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream에서 outputStream으로 맞춤형 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | firstInputFile에서 outputFile로 맞춤형 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream에서 outputStream으로 소책자를 만듭니다. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile에서 outputFile로 맞춤형 소책자를 만듭니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | 두 개의 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | 다중 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. outputStream의 각 페이지는 동일한 페이지 번호를 가진 입력 스트림들의 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | 두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 두 페이지를 포함하며, 하나는 첫 번째 입력 파일에서, 다른 하나는 두 번째 입력 파일에서 가져옵니다. 두 페이지는 가로로 쌓입니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | 다중 입력 PDF 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다. outputFile의 각 페이지는 동일한 페이지 번호의 입력 파일 페이지와 결합된 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | 입력 스트림에서 N-Up 문서를 만들어 결과를 출력 스트림에 저장합니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | firstInputFile에서 N-Up 문서를 만들어 outputFile에 저장합니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | 첫 번째 입력 스트림에서 N-Up 문서를 만들어 출력 스트림에 저장합니다. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | 입력 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | 문서의 페이지 크기를 조정합니다. 축소된 페이지 주변에 빈 여백이 추가됩니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | 문서의 페이지 크기를 조정합니다. 축소된 페이지 주변에 빈 여백이 추가됩니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | 문서 페이지의 내용을 크기 조정합니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | 문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주변에 빈 여백이 추가됩니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 퍼센트로 지정됩니다. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 퍼센트로 지정됩니다. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | 시작 위치에서 지정된 위치까지 분할하고, 앞부분을 출력 Stream에 저장합니다. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | 첫 페이지부터 지정된 위치까지 Pdf 파일을 분할하고, 앞부분을 새 파일로 저장합니다. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | 지정된 위치에서 분할하고, 뒤부분을 새 파일 Stream으로 저장합니다. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | 위치에서 분할하고, 뒤부분을 새 파일로 저장합니다. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Pdf 파일을 단일 페이지 문서로 분할합니다. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | PDF 파일을 단일 페이지 문서로 분할합니다. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Pdf 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 템플릿 필드 이름으로 지정됩니다. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Pdf 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 템플릿 필드 이름으로 지정됩니다. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portStreams 문서의 페이지가 포함됩니다. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | portFiles 문서에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portFiles 문서의 페이지가 포함됩니다. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | 문서를 연결합니다. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | 파일을 연결합니다 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | 파일을 하나의 파일로 연결합니다. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | 두 파일을 연결합니다. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | 두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | 두 개의 Pdf 문서를 페이지를 교대로 배치하고 빈 부분을 빈 페이지로 채워 새로운 Pdf 문서로 병합합니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage 순으로 구성됩니다. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | 번호 배열로 지정된 페이지를 추출하여 새로운 Pdf 파일로 저장합니다. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | 번호 배열로 지정된 페이지를 추출하여 새로운 PDF 파일로 저장합니다. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | 입력 파일에서 페이지를 추출하고 새로운 Pdf 파일로 저장합니다. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | 다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | 다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | InputStream에서 outputStream으로 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | 입력 파일에서 출력 파일로 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | 입력 스트림에서 소책자를 만들고 결과를 output stream에 저장합니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | inputFile에서 outputFile로 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream에서 outputStream으로 맞춤형 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | firstInputFile에서 outputFile로 맞춤형 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream에서 outputStream으로 소책자를 만듭니다. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile에서 outputFile로 맞춤형 소책자를 만듭니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | 두 개의 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | 다중 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. outputStream의 각 페이지는 동일한 페이지 번호를 가진 입력 스트림들의 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | 두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 두 페이지를 포함하며, 하나는 첫 번째 입력 파일에서, 다른 하나는 두 번째 입력 파일에서 가져옵니다. 두 페이지는 가로로 쌓입니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | 다중 입력 PDF 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다. outputFile의 각 페이지는 동일한 페이지 번호의 입력 파일 페이지와 결합된 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | 입력 스트림에서 N-Up 문서를 만들어 결과를 출력 스트림에 저장합니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | firstInputFile에서 N-Up 문서를 만들어 outputFile에 저장합니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | 첫 번째 입력 스트림에서 N-Up 문서를 만들어 출력 스트림에 저장합니다. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | 입력 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | 문서 페이지의 내용을 크기 조정합니다. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | 문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주변에 빈 여백이 추가됩니다. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | 시작 위치에서 지정된 위치까지 분할하고, 앞부분을 출력 Stream에 저장합니다. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | 첫 페이지부터 지정된 위치까지 Pdf 파일을 분할하고, 앞부분을 새 파일로 저장합니다. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | 지정된 위치에서 분할하고, 뒤부분을 새 파일 Stream으로 저장합니다. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | 위치에서 분할하고, 뒤부분을 새 파일로 저장합니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | 병합 과정에서 손상된 파일을 만나면 수행되는 동작. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | 페이지 크기 조정을 지정하기 위한 클래스. 다음 매개변수를 설정할 수 있습니다: 결과 Page의 크기(너비, 높이)를 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정; 왼쪽, 위, 아래 및 오른쪽 여백을 기본 공간 단위 또는 초기 Page 크기의 백분율로 지정; 일부 값은 자동 계산을 위해 null로 둘 수 있습니다. 이러한 값은 명시적으로 지정된 값을 제외한 나머지 Page 크기에서 계산됩니다. 예: Page 너비 = 100이고 새 Page 너비를 60 단위로 지정하면 왼쪽 및 오른쪽 여백이 자동으로 계산됩니다: (100 - 60) / 2 = 15. 이 클래스는 ResizeContents 메서드에서 사용됩니다. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | 기본 공간 단위의 백분율로 지정된 여백 및 콘텐츠 크기 값입니다. 이 클래스는 ContentsResizeParameters에서 사용됩니다. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | 연결 시 손상된 파일에 대한 정보를 제공하는 클래스입니다. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | 페이지 나눔 위치의 데이터입니다. |

### 또 보기

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


