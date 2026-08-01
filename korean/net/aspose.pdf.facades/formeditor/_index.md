---
title: "클래스 FormEditor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.FormEditor 클래스. 양식을 편집하고 필드를 추가/삭제하는 클래스 등"
type: docs
weight: 4450
url: /ko/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

양식을 편집하는 클래스(필드 추가/삭제 등).

```csharp
public sealed class FormEditor : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | FormEditor의 생성자. |
| [FormEditor](formeditor/#constructor_1)(Document) | 새로운 `FormEditor` 객체를 *document*를 기반으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | PDF 파일 형식을 설정합니다. 결과 파일은 지정된 파일 형식으로 저장됩니다. 이 속성이 지정되지 않으면 파일은 변환 없이 기본 PDF 형식으로 저장됩니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | 내보내기 값을 가진 콤보 박스 옵션을 설정합니다. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | 필드의 시각적 속성을 설정합니다. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | 새로 생성된 리스트 박스 또는 콤보 박스에 추가될 항목을 설정합니다. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | 새 라디오 버튼 필드가 추가될 때 라디오 버튼 항목 크기를 가져오거나 설정합니다. |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | 두 개의 인접한 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버이며, 기본값은 50입니다. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | 라디오 버튼이 가로로 배열되는지 세로로 배열되는지를 나타내는 플래그이며, 기본값은 true입니다. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | 제출 버튼의 제출 플래그를 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | 지정된 유형의 필드를 양식에 추가합니다. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | 지정된 유형의 필드를 양식에 추가합니다. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | PushButton 필드에 대한 JavaScript를 추가합니다. 기존 이벤트가 있으면 새 이벤트가 그 뒤에 추가됩니다. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | 목록 상자에 새 항목을 추가합니다. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Export 값을 가진 새 항목을 기존 목록 상자 필드에 추가합니다. 이는 AcroForm 콤보 박스 필드에만 적용됩니다. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | 양식에 제출 버튼을 추가합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Facade를 초기화합니다. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Facade를 닫습니다. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | 기존 필드를 지정된 페이지 번호의 동일한 위치로 복사합니다. 새 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드는 제외됩니다. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | 기존 필드를 페이지 번호와 좌표 모두로 지정된 새로운 위치로 복사합니다. 새 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드는 제외됩니다. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | 기존 필드를 원본 페이지 번호와 좌표를 유지한 채 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | 기존 필드를 지정된 페이지 번호와 원본 좌표를 유지한 채 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | 기존 필드를 지정된 페이지 번호와 좌표를 사용하여 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | PDF 문서의 모든 필드에 대한 시각적 속성을 변경합니다. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | 지정된 필드 유형을 가진 모든 필드의 시각적 속성을 변경합니다. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | 지정된 필드의 시각적 속성을 변경합니다. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | 목록 필드에서 항목을 삭제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | 필드 플래그를 가져옵니다. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | 필드의 새 위치를 설정합니다. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | 양식에서 필드를 제거합니다. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | 필드의 제출 동작을 제거합니다. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | 필드의 이름을 변경합니다. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | 모든 시각 속성을 빈 값으로 재설정합니다. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | 내부 파사드의 모든 시각 속성을 빈 값으로 재설정합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | 텍스트 필드의 정렬 스타일을 설정합니다. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | 텍스트 필드의 수직 정렬 스타일을 설정합니다. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | 필드 플래그를 설정합니다. |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | 필드의 속성을 설정합니다. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | 일반 단일 행 텍스트 필드의 콤 수를 설정합니다(필드는 combNumber 매개변수 값만큼 동일한 간격의 위치, 즉 콤으로 자동 분할됩니다). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | 텍스트 필드의 최대 문자 수를 설정합니다. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | PushButton 필드에 대한 JavaScript를 설정합니다. 기존 JavaScript가 있으면 새 것으로 교체됩니다. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | 제출 버튼의 submit 플래그를 설정합니다. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | 버튼의 URL을 설정합니다. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | 단일 행 텍스트 필드를 다중 행으로 변경합니다. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


