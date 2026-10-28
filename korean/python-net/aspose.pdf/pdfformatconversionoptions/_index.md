---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서를 변환하기 위한 옵션 집합을 나타냅니다."
type: docs
weight: 1220
url: /ko/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

PDF 문서를 변환하기 위한 옵션 집합을 나타냅니다.

PdfFormatConversionOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
| PdfFormatConversionOptions(output_log_file_name, format) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
| PdfFormatConversionOptions(format) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
| PdfFormatConversionOptions(format, action) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
| PdfFormatConversionOptions(output_log_stream, format, action) | PdfFormatConversionOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| is_async_image_streams_conversion_mode | 비동기 모드에서 이미지 스트림 실행을 가져오거나 설정합니다. |
| is_low_memory_mode | 저 메모리 변환 모드가 활성화되어 있는지 여부 |
| format | PDF 형식. |
| log_file_name | 주석이 저장될 파일 경로. |
| log_stream | 주석이 저장될 스트림. |
| error_action | 변환할 수 없는 객체에 대한 동작 |
| transparency_action | 이미지 마스크된 객체에 대한 동작 |
| convert_soft_mask_action | 소프트 마스크가 있는 이미지에 대한 동작. |
| 기본값 | 기본 매개변수를 가진 PdfFormatConversionOptions 객체를 가져옵니다 |
| non_specification_cases | 소스 문서가 PDF/A 사양에 부합하지 않는 경우에 대한 PDF/A 변환 프로세스를 제어하는 플래그를 보유합니다.<br/>             |
| symbolic_font_encoding_strategy | 심볼릭 TrueType 폰트가 하나 이상의 인코딩 서브테이블을 가지고 있는 경우, 심볼릭 폰트의 인코딩 데이터를 복사하는 전략입니다.<br/>             |
| align_text | 이 플래그는 변환된 문서의 텍스트 정렬을 제어합니다. 기본적으로 문서 변환은 <br/> 텍스트 정렬에 영향을 주지 않으며 텍스트를 그대로 유지합니다. 그러나 경우에 따라 글꼴 대체로 인해 <br/> 변환된 문서에서 텍스트가 겹치거나 여분의 공백이 발생할 수 있습니다. 이 플래그가 설정되면 <br/> 특수 정렬 작업이 수행됩니다. 이 플래그는 텍스트 겹침이나 여분의 공백 문제가 있는 문서에만 설정해야 하며, 플래그 사용으로 인해 <br/> 성능이 감소하고 경우에 따라 텍스트 내용이 손상될 수 있습니다. |
| pua_text_processing_strategy | Unicode 개인 사용 영역(PUA)에서 기호를 처리하는 전략. |
| optimize_file_size | PDF/A 문서의 파일 크기를 줄이기 위한 특수 변환 모드를 활성화/비활성화하는 플래그를 가져오거나 설정합니다.<br/> 이 플래그는 현재 PDF 문서에 사용된 글꼴 최적화에 영향을 미치며, 향후에는 <br/> 그래픽과 같은 다른 데이터 구조에 대한 최적화를 켜는 데에도 사용될 수 있습니다.  <br/> 이 플래그와 모드를 설정하면 파일 크기를 크게 줄일 수 있지만 동시에 변환 성능이 크게 감소할 수 있습니다. |
| exclude_fonts_strategy | 불필요한 글꼴을 제외하고 문서 파일 크기를 줄이는 전략(들). <br/> 이 매개변수는 플래그 [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)가 true로 설정된 경우에만 의미가 있습니다.<br/> 기본적으로 전략 [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)와 <br/> [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)의 조합이 사용됩니다. |
| font_embedding_options | 일부 글꼴을 PDF 문서에 포함시킬 수 없는 경우에 대한 옵션. |
| unicode_processing_rules | Unicode 매핑 문제를 해결하기 위한 규칙입니다. null일 수 있습니다. |
| icc_profile_file_name | ICC 프로파일 이름의 파일명을 가져오거나 설정합니다. null인 경우 기본 ICC 프로파일이 사용됩니다. |
| not_accessible_fonts | 이 속성은 외부 속성입니다. 컴퓨터에서 찾을 수 없었던 모든 글꼴(글꼴 이름)을 보유합니다 <br/> 마지막 PDF/A 변환 시. |
| is_transfer_info | PDF 2.0으로 변환할 때 Info에서 Metadata로 데이터를 전달할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. |
| align_strategy | 텍스트 정렬 전략입니다. 이 매개변수는 플래그 [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)가 true로 설정된 경우에만 의미가 있습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

