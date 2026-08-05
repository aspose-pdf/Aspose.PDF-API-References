---
title: "AppearanceDictionary"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "주석이 페이지에 시각적으로 표시되는 방식을 지정하는 주석 외관 사전입니다."
type: docs
weight: 60
url: /ko/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

주석이 페이지에 시각적으로 표시되는 방식을 지정하는 주석 외관 사전입니다.

AppearanceDictionary 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| is_fixed_size | 사전이 고정 크기를 갖는지 여부를 나타내는 값을 가져옵니다. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state 값,<br/>            여기서 N - 일반 외관, R - 롤오버 외관, D - 눌림 외관이며 state는 상태 이름을 나타냅니다<br/>            (예: 체크박스의 On, Off). |
| values | 사전 값 목록을 가져옵니다. <br/>            결과 컬렉션에는 XForm 객체 목록이 포함됩니다. |
| is_synchronized | 사전 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 가져옵니다. |
| sync_root | 사전 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| add(key, value) | 제공된 키와 값으로 요소를 추가합니다. |
| add(key, value) | 지정된 키에 대한 X 양식을 추가합니다. |
| copy_to(array, index) | 사전의 요소를 배열에 복사하며, 특정 배열 인덱스부터 시작합니다. |
| contains_key(key) | 이 사전이 지정된 키를 포함하고 있는지 확인합니다. |
| remove(key) | 딕셔너리에서 키를 제거합니다. |
| try_get_value(key, value) | 사전에서 키를 찾아서, 찾으면 값을 반환합니다. |

### 또 보기

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

