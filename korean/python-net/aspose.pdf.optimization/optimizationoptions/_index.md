---
title: "OptimizationOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "문서 최적화 알고리즘을 설명하는 클래스입니다.<br/>            이 클래스의 인스턴스는 OptimizeResources() 메서드의 매개변수로 사용할 수 있습니다."
type: docs
weight: 20
url: /ko/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

문서 최적화 알고리즘을 설명하는 클래스입니다.<br/>            이 클래스의 인스턴스는 OptimizeResources() 메서드의 매개변수로 사용할 수 있습니다.

OptimizationOptions 유형은 다음 멤버를 제공합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| OptimizationOptions() | OptimizationOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| link_duplcate_streams | 이 플래그가 true로 설정되면 리소스 스트림이 분석됩니다. 중복 스트림이 발견되면(예: 스트림 내용이 동일한 경우) 해당 스트림은 하나의 객체로 저장됩니다. <br/>            이는 문서 크기를 감소시킬 수 있습니다(예: 동일한 문서가 여러 번 연결된 경우). |
| allow_reuse_page_content | true인 경우 페이지 내용이 동일한 페이지에 대해 문서가 최적화될 때 재사용됩니다. |
| remove_unused_streams | 이 플래그가 true로 설정되면 모든 리소스가 사용 여부에 대해 검사됩니다. 리소스가 사용되지 않으면 해당 리소스가 제거됩니다.<br/>            이는 예를 들어 페이지가 문서에서 추출된 경우 문서 크기를 감소시킬 수 있습니다. |
| remove_unused_objects | 이 플래그가 true로 설정되면 모든 문서 객체가 검사되고, 사용되지 않는 객체(예: 참조가 없는 객체)는 문서에서 제거됩니다. |
| image_compression_options | 문서의 이미지가 압축되는 방식과 압축 매개변수를 설명하는 옵션 집합입니다. |
| compress_images | 이 플래그가 true로 설정되면 문서의 이미지가 압축됩니다. 압축 수준은 ImageQuality 속성으로 지정됩니다. |
| resize_images | 이 플래그가 true이고 CompressImages가 true인 경우, 이미지 해상도가 지정된 MaxResolution 매개변수보다 크면 이미지가 크기 조정됩니다. |
| image_quality | CompressIamges 플래그가 사용될 때 이미지 압축 수준을 지정합니다. |
| max_resoultion | 이미지의 최대 해상도를 지정합니다. 이미지 해상도가 더 높으면 축소됩니다. |
| unembed_fonts | true로 설정하면 글꼴을 포함하지 않게 합니다. |
| subset_fonts | true로 설정하면 글꼴이 부분 집합으로 변환됩니다. |
| remove_private_info | 개인 정보를 제거합니다 (페이지 조각 정보). |
| image_encoding | 사용될 이미지 인코딩입니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| all() | 모든 옵션이 활성화된 최적화 전략을 생성합니다.<br/>            활성화되는 옵션은 문서의 기능을 변경하지 않는 옵션에 한합니다.<br/>            즉, 이미지 압축 및 글꼴 포함 해제는 활성화되지 않으며(수동으로 포함시킬 수 있습니다). |

### 또 보기

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

