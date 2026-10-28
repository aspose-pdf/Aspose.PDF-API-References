---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "창의 왼쪽 상단 모서리에 좌표 (left, top)를 배치하고 페이지 내용을 zoom 비율로 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. left, top 또는 zoom 매개변수 중 하나가 null 값이면 해당 매개변수의 현재 값이 그대로 유지됩니다. zoom 값이 0인 경우는 null 값과 동일한 의미입니다."
type: docs
weight: 880
url: /ko/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

창의 왼쪽 상단 모서리에 좌표 (left, top)를 배치하고 페이지 내용을 zoom 비율로 확대하여 페이지를 표시하는 명시적 목적지를 나타냅니다. left, top 또는 zoom 매개변수 중 하나가 null 값이면 해당 매개변수의 현재 값이 그대로 유지됩니다. zoom 값이 0인 경우는 null 값과 동일한 의미입니다.

XYZExplicitDestination 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | XYZExplicitDestination 클래스의 새 인스턴스를 초기화합니다. |
| XYZExplicitDestination(document, page_number, left, top, zoom) | XYZExplicitDestination 클래스의 새 인스턴스를 초기화합니다. |
| XYZExplicitDestination(page_number, left, top, zoom) | XYZExplicitDestination 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| page | 대상 페이지 객체를 가져옵니다 |
| page_number | 대상 페이지 번호를 가져옵니다 |
| left | 창의 왼쪽 상단 모서리의 왼쪽 수평 좌표를 가져옵니다. |
| top | 창의 왼쪽 상단 모서리의 위쪽 수직 좌표를 가져옵니다. |
| zoom | 줌 계수를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | 필요한 경우 페이지 회전을 고려하여 페이지의 지정된 위치에 목적지를 생성합니다. |
| create_destination(page, type, values) | ExplicitDestination 파생 클래스의 인스턴스를 생성합니다. |
| create_destination(doc, page_number, type, values) | ExplicitDestination 파생 클래스의 인스턴스를 생성합니다. |
| create_destination(page_number, type, values) | ExplicitDestination 파생 클래스의 인스턴스를 생성합니다. |
| create_destination_to_upper_left_corner(page, zoom) | 지정된 페이지의 왼쪽 상단 모서리에 목적지를 생성합니다. |
| create_destination_to_upper_left_corner(page) | 지정된 페이지의 왼쪽 상단 모서리에 목적지를 생성합니다. |
| to_string() | 객체 상태를 문자열 값으로 변환합니다. 예: "1 XYZ 100 200 3". |

### 또 보기

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

