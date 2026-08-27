---
title: "Aspose.Pdf.Forms"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Forms 네임스페이스에는 텍스트 박스, 리스트 박스, 라디오 버튼 등과 같은 다양한 유형의 필드와 표준 정적·동적 양식을 설명하는 클래스가 포함되어 있습니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.forms/
---
**Aspose.Pdf.Forms** 네임스페이스에는 표준, 정적, 동적 형태의 양식과 텍스트 박스, 리스트 박스, 라디오 버튼 등 다양한 유형의 필드를 설명하는 클래스가 포함됩니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [BarcodeField](./barcodefield/) | 클래스는 바코드 필드를 나타냅니다. |
| [ButtonField](./buttonfield/) | 클래스는 푸시 버튼 필드를 나타냅니다. |
| [CheckboxField](./checkboxfield/) | 클래스는 체크박스 필드를 나타냅니다. |
| [ChoiceField](./choicefield/) | 선택 필드의 기본 클래스를 나타냅니다. |
| [ComboBoxField](./comboboxfield/) | 클래스는 폼의 콤보박스 필드를 나타냅니다. |
| [DateField](./datefield/) | 캘린더 보기가 포함된 날짜 필드. |
| [DocMDPSignature](./docmdpsignature/) | 문서 MDP(수정 감지 및 방지) 서명 유형의 클래스를 나타냅니다. |
| [ExternalSignature](./externalsignature/) | X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 이는 내보낼 수 없는 개인 키가 있는 USB 스마트 카드와 토큰을 지원합니다. |
| [Field](./field/) | Acro 양식 필드의 기본 클래스. |
| [FileSelectBoxField](./fileselectboxfield/) | 파일 선택 박스 요소용 필드. |
| [Form](./form/) | 클래스는 폼 객체를 나타냅니다. |
| [IconFit](./iconfit/) | 위젯 주석 아이콘이 주석 사각형 내에서 어떻게 표시되는지 설명합니다. |
| [ListBoxField](./listboxfield/) | 클래스는 리스트박스 필드를 나타냅니다. |
| [NumberField](./numberfield/) | 지정된 유효 문자와 함께하는 텍스트 필드 |
| [Option](./option/) | 클래스는 선택 필드 옵션을 나타냅니다. |
| [OptionCollection](./optioncollection/) | 클래스는 선택 필드 옵션 컬렉션을 나타냅니다. |
| [PasswordBoxField](./passwordboxfield/) | 클래스는 비밀번호 입력용 텍스트 필드를 설명합니다. |
| [PKCS1](./pkcs1/) | PKCS#1 표준에 관한 서명 객체를 나타냅니다. 서명에는 RSA 암호화 알고리즘과 SHA-1 다이제스트 방법이 사용됩니다. |
| [PKCS7](./pkcs7/) | Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5에 정의된 PKCS#7 사양을 따르는 PKCS#7 객체를 나타냅니다. 문서 바이트 범위의 `SHA1 digest`가 PKCS#7 SignedData 필드에 캡슐화됩니다. |
| [PKCS7Detached](./pkcs7detached/) | Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5에 정의된 PKCS#7 사양을 따르는 PKCS#7 객체를 나타냅니다. 문서 바이트 범위에 대한 원본 서명 메시지 다이제스트가 일반 PKCS#7 SignedData 필드에 포함됩니다. PKCS#7 SignedData 필드에는 데이터가 캡슐화되지 않습니다. |
| [RadioButtonField](./radiobuttonfield/) | 라디오 버튼 필드를 나타내는 클래스. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | RadioButton 필드의 항목을 나타내는 클래스. |
| [RichTextBoxField](./richtextboxfield/) | 리치 텍스트 편집기 구성 요소를 설명하는 클래스. |
| [Signature](./signature/) | pdf 문서에서 서명 객체를 나타내는 추상 클래스입니다. 서명은 서명 객체 값을 가진 필드이며, 해당 필드에는 문서 유효성을 검증하는 데 사용되는 데이터가 포함됩니다. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | 서명 맞춤 외관 객체를 나타내는 추상 클래스. |
| [SignatureField](./signaturefield/) | 서명 양식 필드를 나타냅니다. |
| [SignHash](./signhash/) | 문서 해시를 사용자 지정 서명하기 위한 대리자. |
| [TextBoxField](./textboxfield/) | 텍스트 박스 필드를 나타내는 클래스. |
| [XFA](./xfa/) | XML Forms Architecture (XFA)와 관련된 XML 양식을 나타냅니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [BoxStyle](./boxstyle/) | 체크 박스에 체크를 그리기 위한 스타일을 나타냅니다. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | 이 문서에 부여된 접근 권한입니다. 유효한 값은 다음과 같습니다: 1 - 문서에 대한 어떠한 변경도 허용되지 않으며, 문서가 변경되면 서명이 무효화됩니다. 2 - 허용되는 변경은 양식 입력, 페이지 템플릿 인스턴스화 및 서명이며, 다른 변경은 서명을 무효화합니다. 3 - 2와 동일한 허용 변경에 추가로 주석 생성, 삭제 및 수정이 허용되며, 다른 변경은 서명을 무효화합니다. |
| [FormType](./formtype/) | Acro Form 가능한 유형의 열거형. |
| [IconCaptionPosition](./iconcaptionposition/) | 아이콘의 위치를 설명합니다. |
| [ScalingMode](./scalingmode/) | 사용될 스케일링 유형입니다. |
| [ScalingReason](./scalingreason/) | 아이콘이 주석 사각형 내부에서 스케일링되는 상황을 나타냅니다. |
| [SubjectNameElements](./subjectnameelements/) | 서명 주제 문자열의 요소를 설명하는 열거형. |
| [Symbology](./symbology/) | (바코드) 심볼로지는 특정 유형의 바코드에 대한 기술적 세부 사항을 정의합니다: 막대의 너비, 문자 집합, 인코딩 방법, 체크섬 사양 등. |


