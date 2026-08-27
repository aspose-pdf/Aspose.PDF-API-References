---
title: "클래스 Form"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.Form 클래스. Acro 양식 객체를 나타내는 클래스."
type: docs
weight: 4410
url: /ko/net/aspose.pdf.facades/form/
---
## Form class

Acro 양식 객체를 나타내는 클래스.

```csharp
public sealed class Form : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Form](form/#constructor)() | 매개변수 없이 Form의 생성자입니다. |
| [Form](form/#constructor_1)(Document) | *document* 기반의 새로운 `Form` 객체를 초기화합니다. |
| [Form](form/#constructor_4)(Stream) | 양식에 대한 생성자입니다. |
| [Form](form/#constructor_7)(string) | Form의 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | PDF 파일 형식을 설정합니다. 결과 파일은 지정된 파일 형식으로 저장됩니다. 이 속성이 지정되지 않으면 파일은 변환 없이 기본 PDF 형식으로 저장됩니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | 양식에 있는 필드 이름 목록을 가져옵니다. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | 모든 양식 제출 버튼 이름을 가져옵니다. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | 마지막 가져오기 작업의 결과입니다. 각 필드에 대한 가져오기 결과를 설명하는 객체 배열입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Facade를 초기화합니다. |
| override [Close](../../aspose.pdf.facades/form/close/)() | 열린 파일을 변경 없이 닫습니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | pdf 필드의 내용을 fdf 스트림으로 내보냅니다. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | 문서의 모든 필드 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | pdf 필드의 내용을 xml 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | pdf 필드의 내용을 xml 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | XFA 데이터 패킷을 추출합니다. |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | 전체 한정 필드 이름에 따라 바코드 필드를 채웁니다. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | 체크 박스 필드를 불리언 값으로 채웁니다. 참고: 체크 박스에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.CheckBoxField"인 경우 전체 이름을 지정해야 하며 "CheckBoxField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | 전체 한정 필드 이름에 따라 라디오 박스 필드를 유효한 인덱스 값으로 채웁니다. 필드를 채우기 전에 필드 이름만 알아야 합니다. 값은 인덱스로 지정할 수 있습니다. 참고: 라디오 박스, 콤보 박스 및 리스트 박스 필드에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.ListBoxField"인 경우 전체 이름을 지정해야 하며 "ListBoxField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | 전체 한정 필드 이름에 따라 필드를 유효한 값으로 채웁니다. 필드를 채우기 전에 모든 필드 이름과 해당 유효 값들을 알아야 합니다. 필드 이름과 값은 대소문자를 구분합니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.TextField"인 경우 전체 이름을 지정해야 하며 "TextField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | 다중 선택으로 필드를 채웁니다. 참고: AcroForm 리스트 박스 필드에만 적용됩니다. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | 지정된 값으로 필드를 채웁니다. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | 텍스트 박스 필드를 텍스트 값으로 채우고 문서를 저장합니다. 서명된 문서에 해당됩니다. 참고: 텍스트 박스에만 적용됩니다. 필드 이름과 값은 대소문자를 구분합니다. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | FillImageField 함수의 오버로드입니다. 입력은 이미지 스트림입니다. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | 전체 한정 필드 이름에 따라 기존 버튼 필드에 이미지를 외관으로 붙여넣습니다. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | 모든 필드를 플랫하게 만듭니다. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | 전체 한정 필드 이름으로 지정된 필드를 플랫하게 만듭니다. 다른 필드는 변경되지 않습니다. fieldName이 유효하지 않으면 모든 필드가 변경되지 않은 상태로 유지됩니다. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | 라디오 버튼 옵션 필드의 현재 값을 반환합니다. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | 필드 이름을 기준으로 라디오 버튼 옵션 필드와 관련 값을 가져옵니다. 이 메서드는 라디오 버튼 그룹에 의미가 있습니다. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | 필드 이름에 따라 필드 값을 가져옵니다. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | 모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | 필드의 플래그를 반환합니다. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | 텍스트 필드의 제한을 가져옵니다. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | 필드 유형을 반환합니다. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | 짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | 리치 텍스트 필드의 값을 가져오며, 각 문자에 대한 서식 정보를 포함합니다. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | 제출 버튼의 제출 플래그를 반환합니다. |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | fdf 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | JSON 스트림에서 모든 필드 데이터를 문서 필드에 가져오며, 전체 이름으로 필드를 매칭합니다. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | xfdf(xml) 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | xml 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | xml 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | 필드가 필수인지 여부를 결정합니다. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | 필드 이름을 변경합니다. AcroForm 필드든 XFA 필드든 상관없습니다. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | 문서를 지정된 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | 문서를 지정된 파일에 저장합니다. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | XFA 데이터를 지정된 데이터 패킷으로 교체합니다. 데이터 패킷은 ExtractXfaData를 사용하여 추출할 수 있습니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | 필드 가져오기 결과를 설명하는 클래스입니다. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | 가져온 필드의 상태 |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


