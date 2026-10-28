---
title: "행렬"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 변환 행렬을 나타냅니다."
type: docs
weight: 900
url: /ko/python-net/aspose.pdf/matrix/
---

## Matrix class

클래스는 변환 행렬을 나타냅니다.

Matrix 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Matrix() | Constructor<br/>            표준 1 대 1 행렬을 생성합니다:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Matrix 클래스의 새 인스턴스를 초기화합니다 |
| Matrix(matrix_array) | Matrix 클래스의 새 인스턴스를 초기화합니다 |
| Matrix(matrix) | Matrix 클래스의 새 인스턴스를 초기화합니다 |
| Matrix(a, b, c, d, e, f) | Matrix 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| data | Matrix 데이터를 배열로 가져옵니다. |
| a | 변환 행렬의 A 멤버입니다. |
| b | 변환 행렬의 B 멤버입니다. |
| c | 변환 행렬의 C 멤버입니다. |
| d | 변환 행렬의 D 멤버입니다. |
| e | 변환 행렬의 E 멤버입니다. |
| f | 변환 행렬의 F 멤버입니다. |
| 요소들 | 행렬의 요소들. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| rotation(alpha) | 주어진 회전 각도에 대한 행렬을 생성합니다. |
| rotation(rotation) | 주어진 회전 각도에 대한 행렬을 생성합니다. |
| transform(p) | 이 행렬을 사용하여 점을 변환합니다. |
| transform(rect) | 사각형을 변환합니다.<br/>            각도가 90 * N도 가 아니면 경계 사각형이 반환됩니다. |
| skew(alpha, beta) | 주어진 회전 각도에 대한 행렬을 생성합니다. |
| get_angle(rotation) | 회전을 각도(도)로 변환합니다. |
| multiply(other) | 다른 행렬에 행렬을 곱합니다. |
| add(other) | 다른 행렬에 행렬을 추가합니다. |
| reverse() | 역행렬을 계산합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

