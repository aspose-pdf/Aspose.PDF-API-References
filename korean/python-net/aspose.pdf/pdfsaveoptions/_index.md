---
title: "PdfSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 1240
url: /ko/python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

PDF 형식으로 내보내기 위한 저장 옵션

PdfSaveOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfSaveOptions() | PdfSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| temp_path | 임시 파일의 경로입니다. |
| default_font_name | 컴퓨터에 없는 폰트에 대해 기본적으로 사용되는 폰트 이름입니다.<br/>            PDF로 저장되는 문서에 문서 자체와 장치에 존재하지 않는 폰트가 포함된 경우, API는 이러한 폰트를 <br/>            기본 폰트(장치에서 [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) 폰트를 찾을 수 있는 경우)로 교체합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

