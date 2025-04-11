---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Permissions 열거형. 이 열거형은 PDF에 대한 사용자 권한을 나타냅니다.
type: docs
weight: 8480
url: /ko/net/aspose.pdf/permissions/
---
## 권한 열거형

이 열거형은 PDF에 대한 사용자의 권한을 나타냅니다.

```csharp
[Flags]
public enum Permissions
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PrintDocument | `4` | (보안 핸들러 버전 2) 문서를 인쇄합니다. (보안 핸들러 버전 3 이상) 문서를 인쇄합니다(인쇄 품질이 설정된 경우에 따라 최고 품질 수준이 아닐 수 있음). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm 및 11로 제어되지 않는 작업을 통해 문서의 내용을 수정합니다. |
| ExtractContent | `10` | (보안 핸들러 버전 2) 문서에서 텍스트 및 그래픽을 복사하거나 기타 방법으로 추출합니다. (장애인을 위한 접근성을 지원하거나 기타 목적을 위해 텍스트 및 그래픽을 추출합니다). (보안 핸들러 버전 3 이상) ExtractContentWithDisabilities로 제어되지 않는 작업을 통해 문서에서 텍스트 및 그래픽을 복사하거나 기타 방법으로 추출합니다. |
| ModifyTextAnnotations | `20` | 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 작성하며, ModifyContent가 설정된 경우 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정합니다. |
| FillForm | `100` | (보안 핸들러 버전 3 이상) ModifyTextAnnotations가 해제된 경우에도 기존 대화형 양식 필드(서명 필드 포함)를 작성합니다. |
| ExtractContentWithDisabilities | `200` | (보안 핸들러 버전 3 이상) 텍스트 및 그래픽을 추출합니다(장애인을 위한 접근성을 지원하거나 기타 목적을 위해). |
| AssembleDocument | `400` | (보안 핸들러 버전 3 이상) 문서를 조립합니다(페이지 삽입, 회전 또는 삭제 및 북마크 또는 썸네일 이미지 생성), ModifyContent가 해제된 경우에도 가능합니다. |
| PrintingQuality | `800` | (보안 핸들러 버전 3 이상) PDF 콘텐츠의 신뢰할 수 있는 디지털 복사본을 생성할 수 있는 표현으로 문서를 인쇄합니다. 이 비트가 해제되면(비트 3이 설정된 경우) 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)