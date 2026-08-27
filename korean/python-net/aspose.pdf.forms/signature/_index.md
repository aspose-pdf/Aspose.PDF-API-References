---
title: "Signature"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서에서 서명 객체를 나타내는 추상 클래스입니다. <br/>            서명은 서명 객체 값을 가진 필드이며, 이 값은 문서 유효성을 검증하는 데 사용되는 데이터를 포함합니다."
type: docs
weight: 250
url: /ko/python-net/aspose.pdf.forms/signature/
---

## Signature class

PDF 문서에서 서명 객체를 나타내는 추상 클래스입니다. <br/>            서명은 서명 객체 값을 가진 필드이며, 이 값은 문서 유효성을 검증하는 데 사용되는 데이터를 포함합니다.

Signature 형식은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| custom_appearance | 사용자 지정 모양을 가져오거나 설정합니다. |
| authority | 문서에 서명하는 사람 또는 기관의 이름입니다. |
| date | 서명 시간입니다. |
| location | 서명자의 CPU 호스트 이름 또는 물리적 위치입니다. |
| reason | 서명의 이유, 예: (I agreeРІР‚В¦). |
| contact_info | 서명자가 수신자가 서명자에게 연락할 수 있도록 제공하는 정보 <br/>            서명을 확인하기 위해, 예: 전화번호. |
| byte_range | 정수 쌍(시작 바이트 오프셋, 바이트 길이)의 배열 <br/>             다이제스트 계산을 위한 정확한 바이트 범위를 설명합니다. |
| timestamp_settings | 타임스탬프 설정을 가져오거나 설정합니다. |
| ocsp_settings | OCSP 설정을 가져오거나 설정합니다. |
| use_ltv | ltv 검증 플래그를 가져오거나 설정합니다. |
| show_properties | 서명 속성을 표시/숨기도록 강제합니다.<br/>            ShowProperties가 true인 경우 서명 필드에는 미리 정의된 표시 형식(표시할 문자열)이 있습니다:<br/>            -------------------------------------------<br/>            디지털 서명자: {certificate subject}<br/>            날짜: {signature.Date}<br/>            이유: {signature.Reason}<br/>            위치: {signature.Location}<br/>            -------------------------------------------<br/>            여기서 {X}는 X 값에 대한 자리표시자입니다. 또한 서명에 이미지가 있을 수 있으며, 이 경우 나열된 문자열이 이미지 위에 배치됩니다.<br/>            ShowProperties는 기본값으로 true입니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| verify() | 이 서명에 대해 문서를 검증하고 문서가 유효하면 true를, 그렇지 않으면 false를 반환합니다.<br/>             |

### 또 보기

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

