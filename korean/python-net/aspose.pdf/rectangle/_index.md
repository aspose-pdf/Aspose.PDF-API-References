---
title: "Rectangle"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 사각형을 나타냅니다."
type: docs
weight: 1320
url: /ko/python-net/aspose.pdf/rectangle/
---

## Rectangle class

클래스는 사각형을 나타냅니다.

Rectangle 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Rectangle 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| width | 사각형의 너비. |
| 높이 | 사각형의 높이. |
| llx | 좌하단 모서리의 X 좌표. |
| lly | 좌하단 모서리의 Y 좌표. |
| urx | 우상단 모서리의 X 좌표. |
| ury | 우상단 모서리의 Y 좌표. |
| 사소한 | 위치와 크기가 0인 사소한 사각형을 초기화합니다. |
| is_trivial | 사각형이 위치와 크기가 0인 사소한 사각형인지 확인합니다. |
| is_empty | 사각형이 비어 있는지 확인합니다. |
| is_point | 사각형이 점인지 확인합니다. 즉, LLX와 URX가 같고 LLY와 URY가 같은 경우입니다. |
| 비어 있음 | 빈 사각형 |
## 메서드
| 이름 | 설명 |
| :- | :- |
| rotate(angle) | 지정된 각도만큼 사각형을 회전합니다. |
| rotate(angle) | 지정된 각도만큼 사각형을 회전합니다. |
| to_rect() | 사각형을 System.Drawing.Rectangle 인스턴스로 변환합니다. 부동 소수점 위치와 크기는 잘립니다. |
| from_rect(src) | 주어진 System.Drawing.Rectangle 인스턴스로부터 새 사각형을 초기화합니다. |
| parse(value) | 문자열을 구문 분석하여 사각형 구성 요소인 llx, lly, urx, ury를 추출해 보세요. |
| equals(other) | 사각형들이 같은 위치와 크기를 가지고 있는지, 즉 동일한지 확인합니다. |
| near_equals(other, delta) | 사각형이 거의 동일한지, 즉 거의 같은(델타까지 허용) 위치와 크기를 가지고 있는지 확인합니다. |
| intersect(other_rect) | 두 사각형이 교차합니다. |
| join(other_rect) | 사각형을 결합합니다. |
| is_intersect(other_rect) | 이 사각형이 다른 사각형과 교차하는지 여부를 결정합니다. |
| contains(point) | 주어진 점이 사각형 내부에 있는지 여부를 결정합니다. |
| center() | 사각형 중심의 좌표를 반환합니다. |
| clone() | Rectangle 객체를 복제합니다. |
| to_points() | 사각형을 점 배열("QuadPoints")로 변환합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

