---
title: "XImage"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이미지 X-Object를 나타내는 클래스입니다."
type: docs
weight: 1680
url: /ko/python-net/aspose.pdf/ximage/
---

## XImage class

이미지 X-Object를 나타내는 클래스입니다.

XImage 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| contains_transparency | 이미지에 투명성이 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| grayscaled | 이미지의 그레이스케일 버전을 가져옵니다. |
| filter_type | 이미지 필터 유형을 가져옵니다. |
| width | 이미지의 너비를 가져옵니다. |
| 높이 | 이미지의 높이를 가져옵니다. |
| 이름 | 이미지 이름을 가져오거나 설정합니다. 페이지 내용에 참조가 있는 이미지의 이름을 변경하면 문서가 올바르지 않을 수 있다는 점에 유의하십시오. 이 경우 XImage.Rename 메서드를 사용하십시오. |
| 메타데이터 | 이미지의 메타데이터. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| save(stream) | 이미지 데이터를 스트림에 JPEG 이미지로 저장합니다. |
| save(stream, format) | 이미지를 요청된 형식으로 스트림에 저장합니다. |
| save(stream, resolution) | 지정된 해상도로 이미지 데이터를 스트림에 JPEG 이미지로 저장합니다. |
| save(stream, format, resolution) | 요청된 형식과 지정된 해상도로 이미지를 스트림에 저장합니다. |
| rename(name) | 이미지의 이름을 바꾸고 이미지에 대한 모든 참조를 새 이름으로 교체합니다. |
| get_color_type() | 이미지의 색상 유형을 반환합니다. |
| detect_color_type(bmp) | 이미지의 색상 유형을 반환합니다. |
| is_the_same_object(image) | 두 이미지가 동일한 객체를 참조하면 true를 반환합니다. |
| get_name_in_collection() | ints 컬렉션에 있는 이미지의 이름을 반환합니다. |
| to_stream() | 원본 이미지 스트림을 반환합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

