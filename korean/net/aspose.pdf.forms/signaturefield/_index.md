---
title: Class SignatureField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.SignatureField 클래스. 서명 양식 필드를 나타냅니다.
type: docs
weight: 5290
url: /ko/net/aspose.pdf.forms/signaturefield/
---
## SignatureField 클래스

서명 양식 필드를 나타냅니다.

```csharp
public sealed class SignatureField : Field
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SignatureField](signaturefield/#constructor)(Document, Rectangle) | `SignatureField` 클래스의 새 인스턴스를 초기화합니다. |
| [SignatureField](signaturefield/#constructor_1)(Page, Rectangle) | `SignatureField` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | 주석 작업을 가져옵니다. (2 속성) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석의 외관 상태를 가져오거나 설정합니다. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | 필드의 대체 이름을 가져오거나 설정합니다 (사용자 인터페이스에서 필드를 식별할 때 실제 필드 이름 대신 사용할 대체 필드 이름). 대체 이름은 Adobe Acrobat에서 필드 툴팁으로 사용됩니다. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | 페이지에서 이 주석의 인덱스를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | 주석의 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | 이 필드의 하위 필드 수를 가져옵니다. (예: 라디오 버튼 필드의 항목 수). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | 필드의 기본 외관을 가져오거나 설정합니다. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | 필드의 내보낼 수 있는 플래그를 가져오거나 설정합니다. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그입니다. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | 주석 강조 모드입니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | 이 필드가 비종료 필드(즉, 필드 그룹)인지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | 생성기 지원을 위한 속성입니다. 필드가 머리글 또는 바닥글에 추가될 때 사용됩니다. true인 경우 이 필드는 한 번 생성되며 모든 문서 페이지에서 그 외관이 표시됩니다. false인 경우 문서의 각 페이지에 대해 별도의 필드가 생성됩니다. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | 사전이 동기화된 경우 true를 반환합니다. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | 하위 필드의 이름으로 이 필드에 포함된 하위 필드를 가져옵니다. (2 인덱서) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | 문서에서 대화형 양식 필드 데이터를 내보낼 때 사용할 필드의 매핑 이름을 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다 (PDF 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 주석이 최근에 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 페이지에서 주석 이름을 가져오거나 설정합니다. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | 주석이 활성화될 때 수행될 작업입니다. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | 이 필드를 포함하는 페이지의 인덱스를 가져옵니다. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | 주석 부모를 가져옵니다. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | 필드의 부분 이름을 가져오거나 설정합니다. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | 필드의 읽기 전용 상태를 가져오거나 설정합니다. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | 필드 사각형을 가져오거나 설정합니다. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | 필드의 필수 상태를 가져오거나 설정합니다. |
| [Signature](../../aspose.pdf.forms/signaturefield/signature/) { get; } | 서명 객체를 가져옵니다. 이 객체는 공개 키 암호화 표준에 대한 서명 데이터를 포함합니다. 클래스 [`PKCS1`](../pkcs1/), [`PKCS7`](../pkcs7/) 및 [`PKCS7Detached`](../pkcs7detached/)는 지원되는 모든 유형의 서명 객체를 나타냅니다. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 동기화 객체입니다. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | 필드의 탭 순서를 가져오거나 설정합니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 주석의 텍스트 정렬을 가져오거나 설정합니다. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | 필드의 값을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | 방문자를 수락합니다. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 매트릭스 변환에 따라 매개변수와 외관을 업데이트합니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드입니다. 항상 null을 반환합니다. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | 지정된 인덱스에서 시작하여 이 필드의 하위 필드를 배열에 복사합니다. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | 필드에 대해 지정된 JavaScript 작업을 실행합니다. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 지정된 PDF 양식 필드를 JSON 형식으로 내보내고 결과를 지정된 파일에 씁니다. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 지정된 필드의 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지지 않습니다. |
| [ExtractCertificate](../../aspose.pdf.forms/signaturefield/extractcertificate/)() | DER 형식의 단일 X.509 인증서를 스트림으로 추출합니다. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage)() | 서명의 이미지를 JPEG 인코딩된 스트림으로 추출합니다. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage_1)(ImageFormat) | 서명의 이미지를 인코딩된 스트림으로 추출합니다. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | 이 필드를 제거하고 그 값을 페이지에 직접 배치합니다. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 기존 상태 이름에 따라 "체크됨" 상태의 이름을 반환합니다. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 포함된 필드의 열거자를 반환합니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | 필드의 전체 이름과 정확히 일치하는 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 'fieldFullNameInJSON' 변수에 지정된 전체 이름을 사용하여 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | 양식의 모든 계산된 필드를 재계산합니다. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | 필드의 위치를 설정합니다. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign)(Signature) | 이 서명 필드를 사용하여 문서에 서명합니다. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign_1)(Signature, Stream, string) | 이 서명 필드를 사용하여 문서에 서명합니다. |

### 참조

* 클래스 [Field](../field/)
* 네임스페이스 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../)