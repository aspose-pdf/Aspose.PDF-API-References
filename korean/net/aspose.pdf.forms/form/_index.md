---
title: "클래스 Form"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Forms.Form 클래스. 폼 객체를 나타내는 클래스입니다."
type: docs
weight: 5190
url: /ko/net/aspose.pdf.forms/form/
---
## Form class

클래스는 폼 객체를 나타냅니다.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | 설정된 경우, 필드가 변경될 때 모든 폼 필드가 다시 계산됩니다. 기본값은 true입니다. 계산된 필드가 많은 폼을 채울 때 성능을 높이려면 false로 설정합니다. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | 설정된 경우, 주석에 존재하면 누락된 폼 필드가 자동으로 생성됩니다. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | 필드 계산 순서를 설정할 수 있습니다. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | 이 양식에 있는 필드 수를 가져옵니다. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | 양식의 기본 외관을 가져오거나 설정합니다(양식의 필드에 대한 기본 글꼴, 텍스트 크기 및 색상을 설명하는 객체). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | 이 양식에 배치된 기본 리소스를 가져옵니다. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | 이 속성이 true이면 필수 Xfa exclGroup 요소 컨테이너에 대해 추가 빨간 경계 사각형이 그려집니다. 이 속성은 exclGroup에 대한 유사 항목이 없어서 Xfa 양식을 표준으로 변환할 때 도입되었습니다. 기본값은 false입니다. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | 계층형 양식의 최하위 수준에 있는 모든 필드 목록을 가져옵니다. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | 문서에 XFA 양식이 포함되어 있는지 여부를 나타내는 값을 가져옵니다. 이 속성은 XFA 양식이 존재하고 [`NeedsRendering`](./needsrendering/)이 false인 경우 XFA 양식을 제거하기 위해 [`IgnoreNeedsRendering`](./ignoreneedsrendering/)을 사용해야 하는지 판단하기 위해 도입되었습니다. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | 이 속성이 true이면 XFA 양식을 표준 양식으로 변환하는 동안 NeedsRendering 키의 값이 무시됩니다. 기본값은 false입니다. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | 객체가 스레드 안전한 경우 true를 반환합니다. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | 필드 이름으로 양식의 필드를 가져옵니다. 필드를 찾을 수 없으면 예외를 발생시킵니다. (2개의 인덱서) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | 문서가 동적 XFA 양식의 제거가 필요한지 여부를 나타내는 값을 가져옵니다. 이 속성은 XFA 양식이 존재하고 [`NeedsRendering`](./needsrendering/)이 false인 경우 XFA 양식을 제거하기 위해 [`IgnoreNeedsRendering`](./ignoreneedsrendering/)을 사용해야 하는지 판단하기 위해 도입되었습니다. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | 이 속성이 true이면 동적 문서를 표준으로 변환한 후 pdf 문서에서 \"Perms\" 사전이 제거됩니다. \"Perms\" 사전에는 Adobe Acrobat Reader에서 필수 필드 선택 표시를 방해하는 규칙이 포함될 수 있습니다. 기본값은 false입니다. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | 설정된 경우, 파일이 이전 내용을 변경하는 방식으로 저장(쓰기)될 때 무효화될 수 있는 서명이 문서에 포함됩니다. 이는 증분 업데이트와는 다릅니다. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | 설정된 경우, 문서에 최소 하나의 서명 필드가 포함됩니다. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | 동기화 객체를 반환합니다. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | 양식 유형을 가져옵니다. 가능한 값은: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | 양식의 XFA 데이터를 가져옵니다(존재하는 경우). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | 양식에 필드를 추가합니다. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | 양식에 필드를 추가합니다. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | 양식에 새 필드를 추가합니다; 이 필드가 다른 양식이나 현재 양식에 이미 배치된 경우 필드 복사본이 생성됩니다. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | 지정된 위치의 문서 지정 페이지에 필드의 추가 외관을 추가합니다. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | 양식의 XFA를 지정된 값으로 설정합니다. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | 양식에 배치된 필드를 배열에 복사합니다. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | 양식에서 필드를 삭제합니다. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | 이름으로 양식에서 필드를 삭제합니다. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | PDF 양식 필드를 JSON 형식으로 내보내고 결과를 제공된 스트림에 씁니다. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | PDF 양식 필드를 JSON 형식으로 내보내고 결과를 지정된 파일에 씁니다. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | 모든 양식 필드를 제거하고 해당 값을 페이지에 직접 배치합니다. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | 양식 필드의 열거형을 가져옵니다. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | 지정된 사각형 내부의 필드를 반환합니다. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | 양식에 지정된 필드가 이미 있는지 확인합니다. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | 지정된 이름을 가진 필드가 이미 양식에 추가되었는지 확인합니다. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | 지정된 이름을 가진 필드가 이미 양식에 추가되었는지, 필드의 자식 계층 구조까지 확인할 수 있는지 판단합니다. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | 스트림에 제공된 JSON 형식에서 PDF 양식 필드를 가져옵니다. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | 지정된 파일에 제공된 JSON 형식에서 PDF 양식 필드를 가져옵니다. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | 양식 필드 주석을 독립적으로 만듭니다. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | 지정된 인덱스에 있는 필드의 외관을 제거합니다. 자식 외관이 하나만 남은 경우, 메서드는 이를 필드에 삽입합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | 양식에는 서명 정보가 포함될 수 있으며, 서명되었거나 서명되지 않을 수 있습니다. 그리고 양식의 뷰는 때때로 양식이 서명되었는지 여부에 따라 달라져야 합니다. 이 속성은 양식 변환기(예: XFA 양식을 표준 양식으로 변환하는 동안)에게 결과 양식을 서명된 형태로 렌더링할지 서명되지 않은 형태로 렌더링할지 알려줍니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | 양식 평탄화 절차에 대한 설정을 설명하는 클래스입니다. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | 양식에는 서명 정보가 포함될 수 있으며 서명되거나 서명되지 않을 수 있습니다. 뷰어에서 양식의 뷰는 때때로 양식이 서명되었는지 여부에 따라 달라져야 합니다. 이 열거형은 서명과 관련된 양식 유형 변환 중 가능한 렌더링 모드를 나열합니다. |

### 또 보기

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


