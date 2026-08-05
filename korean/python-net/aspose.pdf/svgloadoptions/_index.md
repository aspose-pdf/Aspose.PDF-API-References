---
title: "SvgLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "SVG 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 1450
url: /ko/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

SVG 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 나타냅니다.

SvgLoadOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| SvgLoadOptions() | SvgLoadOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 모든 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환하면 로드 작업이 중단되어야 합니다. |
| load_format | 파일 형식을 나타내며, [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)에서 설명합니다. |
| page_info | 문서 로드 중에 적용되어야 하는 페이지 정보를 가져오거나 설정합니다.<br/>            NOTE 이 매개변수는 ConversionEngine == ConversionEngines.NewEngine 일 때만 작동합니다. |
| adjust_page_size | PDF 페이지 크기를 SVG 크기에 맞게 조정합니다. |
| conversion_engine | 변환 중에 사용할 변환 엔진을 선택하도록 허용합니다.<br/>            현재 새 엔진은 B-테스트 단계에 있으며, 따라서 이 값은 기본적으로 <br/>            ConversionEngines.LegacyEngine 로 설정됩니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

