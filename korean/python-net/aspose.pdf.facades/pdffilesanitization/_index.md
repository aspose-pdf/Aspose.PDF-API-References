---
title: "PdfFileSanitization"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "정화 및 복구 API를 나타냅니다.<br/>            다른 방법으로 문서를 생성/열 수 없을 때 사용하십시오."
type: docs
weight: 290
url: /ko/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

정화 및 복구 API를 나타냅니다.<br/>            다른 방법으로 문서를 생성/열 수 없을 때 사용하십시오.

PdfFileSanitization 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileSanitization() | PdfFileSanitization 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| 로그 | 파일이 저장된 후 파일에 대해 수행된 작업을 확인할 수 있습니다. |
| use_trim_top | pdf 데이터 이전의 데이터를 제거할 수 있습니다. |
| use_trim_bottom | pdf 데이터 이후의 데이터를 제거할 수 있습니다. |
| use_rebuild_xref_and_trailer | 문서에 대한 새로운 xref 및 트레일러를 생성할 수 있습니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(input_file) | Sanitize를 위해 Pdf 파일을 바인딩합니다. |
| bind_pdf(input_stream) | Sanitize를 위해 Pdf 스트림을 바인딩합니다. |
| bind_pdf(src_doc) | 파사드를 초기화합니다. |
| save(output_file) | 결과 PDF를 파일에 저장합니다. |
| save(output_stream) | 결과 PDF를 스트림에 저장합니다. |
| close() | Facade를 닫습니다. |
| recover() | 문서를 복구합니다.<br/>            속성을 사용하여 사용자 지정합니다. |
| trim_top() | %PDF 이전의 데이터를 제거합니다. |
| trim_bottom() | 마지막 %%EOF 이후의 데이터를 제거합니다. |
| rebuild_xref_and_trailer() | 기존 xref와 트레일러를 제거하고 새로운 xref와 트레일러를 생성합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

