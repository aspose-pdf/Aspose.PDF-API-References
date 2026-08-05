---
title: "권한"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이 열거형은 PDF에 대한 사용자의 권한을 나타냅니다."
type: docs
weight: 6560
url: /ko/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

이 열거형은 PDF에 대한 사용자의 권한을 나타냅니다.

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| PRINT_DOCUMENT | (리비전 2의 보안 핸들러) 문서를 인쇄합니다.<br/>            (리비전 3 이상인 보안 핸들러) 문서를 인쇄합니다 <br/>            (가능한 최고 품질 수준이 아닐 수 있으며, <br/>            [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/)가 설정되어 있는지에 따라 달라집니다). |
| MODIFY_CONTENT | 다른 작업으로 문서의 내용을 수정합니다 <br/>            이는 [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/)에 의해 제어되는 작업을 제외하고, <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/) 및 11을 포함합니다. |
| EXTRACT_CONTENT | (리비전 2의 보안 핸들러) 문서에서 텍스트와 그래픽을 복사하거나 다른 방식으로 추출합니다, 여기에는 텍스트와 그래픽을 추출하는 것이 포함됩니다 (장애가 있는 사용자의 접근성을 지원하거나 기타 목적을 위해).<br/>            (리비전 3 이상인 보안 핸들러) 문서에서 텍스트와 그래픽을 복사하거나 다른 방식으로 추출합니다, 이는 [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/)에 의해 제어되는 작업을 제외한 작업에 의해 수행됩니다. |
| MODIFY_TEXT_ANNOTATIONS | 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 채웁니다, <br/>            그리고 [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/)가 설정된 경우, 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정합니다. |
| FILL_FORM | (리비전 3 이상인 보안 핸들러) 기존 대화형 양식 필드(서명 필드 포함)를 채웁니다, <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/)가 해제된 경우에도. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (리비전 3 이상인 보안 핸들러) 텍스트와 그래픽을 추출합니다 <br/>            (장애가 있는 사용자의 접근성을 지원하거나 기타 목적을 위해). |
| ASSEMBLE_DOCUMENT | (리비전 3 이상인 보안 핸들러) 문서를 조립합니다 <br/>            (페이지를 삽입, 회전, 삭제하고 북마크 또는 썸네일 이미지를 생성), [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/)가 해제된 경우에도. |
| PRINTING_QUALITY | (리비전 3 이상인 보안 핸들러) 문서를 <br/>            PDF 내용의 정확한 디지털 복사본을 생성할 수 있는 표현으로 <br/>            인쇄합니다. 이 비트가 해제되고 (비트 3이 설정된 경우), <br/>            인쇄는 외관의 저수준 표현으로 제한되며, <br/>            품질이 저하될 수 있습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

