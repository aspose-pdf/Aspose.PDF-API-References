---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이 클래스는 Adobe Preflight 오류 <br/>            \"Text cannot be mapped to Unicode\"를 해결하는 데 사용할 수 있는 규칙을 설명합니다."
type: docs
weight: 20
url: /ko/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

이 클래스는 Adobe Preflight 오류 <br/>            "Text cannot be mapped to Unicode"를 해결하는 데 사용할 수 있는 규칙을 설명합니다.

ToUnicodeProcessingRules 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| ToUnicodeProcessingRules() | 생성자 |
| ToUnicodeProcessingRules(remove_spaces) | ToUnicodeProcessingRules 클래스의 새 인스턴스를 초기화합니다 |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | ToUnicodeProcessingRules 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| remove_spaces_from_c_map_names | 일부 글꼴은 이름에 공백이 포함된 ToUnicode 문자 코드 맵을 가지고 있습니다. 이러한 공백은 유니코드 텍스트 매핑에서 오류를 일으킬 수 있습니다<br/>            이 플래그는 ToUnicode 문자 코드 맵 이름에서 공백을 제거하도록 지정합니다.<br/>            기본값은 false입니다. |
| map_non_linked_symbols_on_space | 일부 글꼴은 일부 텍스트 기호에 대한 유니코드 정보를 제공하지 않습니다. <br/>            이 정보 부족으로 인해 "Text cannot be mapped to Unicode" 오류가 발생합니다.<br/>            이 플래그를 사용하여 연결되지 않은 기호를 유니코드 "space"(코드 32)로 매핑합니다. |

### 또 보기

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

