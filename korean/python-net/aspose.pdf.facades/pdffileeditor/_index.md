---
title: "PdfFileEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 파일 연결, 분할, 페이지 추출, 소책자 만들기 등 작업을 구현합니다."
type: docs
weight: 220
url: /ko/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

PDF 파일에 대한 작업을 구현합니다: 병합, 분할, 페이지 추출, 소책자 만들기 등.

PdfFileEditor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileEditor() | PdfFileEditor 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| conversion_log | 변환 프로세스의 로그를 가져옵니다. |
| merge_duplicate_layers | 이 속성이 true인 경우, 동일한 이름을 가진 연결된 문서의 선택적 내용이 결과 문서의 하나의 레이어로 병합됩니다. <br/>            그렇지 않으면, 동일한 이름을 가진 레이어가 서로 다른 레이어로 저장됩니다. |
| copy_outlines | true이면 개요가 복사됩니다. |
| copy_logical_structure | true이면 연결을 수행할 때 파일의 논리 구조가 복사됩니다. |
| merge_duplicate_outlines | true이면 중복 개요가 병합됩니다. |
| preserve_user_rights | true이면 첫 번째 문서의 사용자 권한이 연결된 문서에 적용됩니다. 다른 모든 문서의 사용자 권한은 무시됩니다. |
| incremental_updates | true이면 연결 중에 증분 업데이트가 수행됩니다. |
| optimize_size | 최적화 플래그를 가져오거나 설정합니다. 결과 파일의 동일한 리소스 스트림은 이 플래그가 설정된 경우 하나의 PDF 객체로 병합됩니다. <br/>            이를 통해 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 메모리 요구량이 증가할 수 있습니다.<br/>            기본값: false. |
| corrupted_items | 연결이 수행될 때 발생한 문제들의 배열입니다. Concatenate()에 전달된 각 손상된 문서마다 <br/>            새로운 CorruptedItem 항목이 생성됩니다.<br/>            이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted인 경우에만 사용할 수 있습니다. |
| corrupted_file_action | 이 속성은 연결 과정에서 손상된 파일을 만나게 될 때의 동작을 정의합니다.<br/>            가능한 값은: StopWithError와 ConcatenateIgnoringCorrupted입니다. |
| owner_password | 소스 입력 PDF 파일이 암호화된 경우 소유자 비밀번호를 설정합니다.<br/>            이 속성은 아직 구현되지 않았습니다. |
| allow_concatenate_exceptions | true로 설정하면 오류가 발생했을 때 예외가 발생합니다. 그렇지 않으면 예외가 발생하지 않으며, 메서드는 실패 시 false를 반환합니다. |
| close_concatenated_streams | true로 설정하면 작업 후 스트림이 닫힙니다. |
| unique_suffix | 폼을 연결할 때 필드 이름을 고유하게 만들기 위해 추가되는 접미사의 형식입니다.<br/>            이 문자열은 숫자로 대체될 %NUM% 부분 문자열을 포함해야 합니다.<br/>            예를 들어 UniqueSuffix = \"ABC%NUM%\"인 경우, 필드 \"fieldName\"의 이름은 다음과 같이 됩니다:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 등. |
| keep_actions | true이면 작업이 소스 문서에서 복사됩니다. 기본값: true. |
| keep_fields_unique | true이면 양식이 연결될 때 필드 이름이 고유하게 만들어집니다.<br/>            접미사가 필드 이름에 추가되며, 접미사 템플릿은 UniqueSuffix 속성에서 지정할 수 있습니다. |
| remove_signatures | true이면 모든 서명이 필드에서 제거됩니다(필드는 남습니다); 그렇지 않으면 잘못된 서명이 발생할 수 있습니다. |
| use_disk_buffer | 이 옵션을 사용하면 대상 문서가 주기적으로 디스크에 저장되고, 이후 연결은 증분 업데이트 형태로 적용됩니다. |
| concatenation_packet_size | UseDiskBuffer가 true로 설정된 경우, 연결 중 새로운 증분 업데이트가 이루어지기 전에 연결된 문서 수를 나타냅니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | 두 파일을 연결합니다. |
| try_concatenate(src, dest) | 문서를 연결합니다. |
| try_concatenate(input_files, output_file) | 파일들을 하나의 파일로 연결합니다. |
| try_concatenate(input_stream, output_stream) | 파일을 연결합니다. |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | 두 파일을 연결합니다. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | 파일을 연결합니다. |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | portStreams 배열에 있는 문서에서 선택된 페이지를 추가합니다.<br/>            결과 문서에는 firstInputFile과 portStreams 문서들의 페이지가 startPage에서 endPage 범위에 포함됩니다. |
| try_append(input_file, port_files, start_page, end_page, output_file) | portFiles 문서에서 선택된 페이지를 추가합니다. <br/>            결과 문서에는 firstInputFile과 portFiles 문서들의 페이지가 startPage에서 endPage 범위에 포함됩니다. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | 다른 파일의 페이지를 입력 PDF 파일에 삽입합니다. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | 다른 파일의 페이지를 입력 PDF 파일에 삽입합니다. |
| try_delete(input_file, page_number, output_file) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고, 새 Pdf 파일로 저장합니다. |
| try_delete(input_stream, page_number, output_stream) | 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고, 새 Pdf 파일로 저장합니다. |
| try_extract(input_file, start_page, end_page, output_file) | 입력 파일에서 페이지를 추출하고, 새 Pdf 파일로 저장합니다. |
| try_extract(input_file, page_number, output_file) | 번호 배열로 지정된 페이지를 추출하고, 새 PDF 파일로 저장합니다. |
| try_extract(input_stream, page_number, output_stream) | 번호 배열로 지정된 페이지를 추출하고, 새 Pdf 파일로 저장합니다. |
| try_split_from_first(input_file, location, output_file) | Pdf 파일을 첫 페이지부터 지정된 위치까지 분할하고, 앞부분을 새 파일로 저장합니다. |
| try_split_from_first(input_stream, location, output_stream) | 시작부터 지정된 위치까지 분할하고, 앞부분을 output Stream에 저장합니다. |
| try_split_to_end(input_file, location, output_file) | 지정된 위치부터 분할하고, 뒷부분을 새 파일로 저장합니다. |
| try_split_to_end(input_stream, location, output_stream) | 지정된 위치부터 분할하고, 뒷부분을 새 file Stream으로 저장합니다. |
| try_make_booklet(input_file, output_file) | 입력 파일에서 출력 파일로 소책자를 만듭니다. |
| try_make_booklet(input_stream, output_stream) | InputStream에서 outputStream으로 소책자를 만듭니다. |
| try_make_booklet(input_file, output_file, page_size) | inputFile에서 outputFile로 소책자를 만듭니다. |
| try_make_booklet(input_stream, output_stream, page_size) | 입력 스트림에서 소책자를 만들고 결과를 출력 스트림에 저장합니다. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | 첫 번째 입력 파일(firstInputFile)에서 outputFile로 맞춤형 소책자를 만듭니다. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | 첫 번째 입력 스트림(firstInputStream)에서 outputStream으로 맞춤형 소책자를 만듭니다. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | 첫 번째 입력 파일(firstInputFile)에서 outputFile로 맞춤형 소책자를 만듭니다. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | 첫 번째 입력 스트림(firstInputStream)에서 outputStream으로 소책자를 만듭니다. |
| try_make_n_up(input_file, output_file, x, y) | 첫 번째 입력 파일(firstInputFile)에서 outputFile로 N-Up 문서를 만듭니다. |
| try_make_n_up(input_stream, output_stream, x, y) | 입력 스트림에서 N-Up 문서를 만들고 결과를 output stream에 저장합니다. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | 첫 번째 입력 스트림에서 output stream으로 N-Up 문서를 만듭니다. |
| try_make_n_up(first_input_file, second_input_file, output_file) | 첫 번째 입력 파일(firstInputFile)에서 outputFile로 N-Up 문서를 만듭니다. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | 입력 스트림에서 N-Up 문서를 만들고 결과를 output stream에 저장합니다. |
| try_make_n_up(input_files, output_file, is_sidewise) | 다중 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. <br/>            outputFile의 각 페이지에는 동일한 페이지 번호를 가진 입력 파일들의 페이지와 결합된 여러 페이지가 포함됩니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | 다중 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다.<br/>            outputStream의 각 페이지에는 동일한 페이지 번호를 가진 입력 스트림들의 페이지와 결합된 여러 페이지가 포함됩니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓습니다. |
| try_make_n_up(input_file, output_file, x, y, page_size) | 입력 파일에서 outputFile로 N-Up 문서를 만듭니다. |
| try_resize_contents(source, destination, pages, parameters) | 문서 페이지의 내용을 크기 조정합니다. |
| try_resize_contents(source, destination, pages, new_width, new_height) | 문서 페이지의 내용을 크기 조정합니다. <br/>            페이지 내용을 축소하고 여백을 추가합니다.<br/>            내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| try_resize_contents(source, destination, pages, parameters) | 문서의 페이지 내용 크기를 조정합니다. 페이지가 축소된 경우 페이지 주변에 빈 여백이 추가됩니다. |
| concatenate(first_input_file, sec_input_file, output_file) | 파일을 연결하고 결과를 HttpResposnse 객체에 저장합니다. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | 파일을 연결하고 결과를 HttpResponse 객체에 저장합니다. |
| concatenate(src, dest) | 문서를 연결합니다. |
| concatenate(input_files, output_file) | 파일을 연결하고 결과를 HttpResposnse 객체에 저장합니다. |
| concatenate(input_stream, output_stream) | 파일을 연결하고 결과를 HttpResponse 객체에 저장합니다. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | 파일을 연결하고 결과를 HttpResposnse 객체에 저장합니다. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | 파일을 연결하고 결과를 HttpResponse 객체에 저장합니다. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | 문서들을 원본 문서에 추가하고 결과를 response 객체에 저장합니다. |
| append(input_file, port_files, start_page, end_page, output_file) | 문서들을 원본 문서에 추가하고 결과를 HttpResponse 객체에 저장합니다. |
| append(input_file, port_file, start_page, end_page, output_file) | 문서들을 원본 문서에 추가하고 결과를 HttpResponse 객체에 저장합니다. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | 문서들을 원본 문서에 추가하고 결과를 response 객체에 저장합니다. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | 파일의 내용을 원본 파일에 삽입하고 결과를 HttpResponse 객체에 저장합니다. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | 문서를 다른 문서에 삽입하고 결과를 response 객체에 저장합니다. |
| insert(input_file, insert_location, port_file, page_number, output_file) | 파일의 내용을 원본 파일에 삽입하고 결과를 HttpResponse 객체에 저장합니다. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | 문서를 다른 문서에 삽입하고 결과를 response 객체에 저장합니다. |
| delete(input_file, page_number, output_file) | 문서에서 지정된 페이지를 삭제하고 결과를 HttpResponse 객체에 저장합니다. |
| delete(input_stream, page_number, output_stream) | 문서에서 지정된 페이지를 삭제하고 결과를 HttpResponse 객체에 저장합니다. |
| extract(input_file, start_page, end_page, output_file) | 소스 파일에서 지정된 페이지를 추출하고 결과를 HttpResponse 객체에 저장합니다. |
| extract(input_file, page_number, output_file) | 소스 파일에서 지정된 페이지를 추출하고 결과를 HttpResponse 객체에 저장합니다. |
| extract(input_stream, start_page, end_page, output_stream) | 소스 파일에서 지정된 페이지를 추출하고 결과를  HttpResponse 객체에 저장합니다. |
| extract(input_stream, page_number, output_stream) | 소스 파일에서 지정된 페이지를 추출하고 결과를  HttpResponse 객체에 저장합니다. |
| split_from_first(input_file, location, output_file) | 문서를 첫 페이지부터 지정 위치까지 분할하고 결과를 HttpResponse 객체에 저장합니다. |
| split_from_first(input_stream, location, output_stream) | 문서를 시작부터 지정된 위치까지 분할하고 결과를 HttpResponse 객체에 저장합니다. |
| split_to_end(input_file, location, output_file) | 지정된 위치부터 분할하고 뒤쪽 부분을 HttpResponse 객체에 저장합니다. |
| split_to_end(input_stream, location, output_stream) | 지정된 위치부터 분할하고 뒤쪽 부분을 HttpResponse 객체에 저장합니다. |
| make_booklet(input_file, output_file) | 소스 파일에서 소책자를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_booklet(input_stream, output_stream) | PDF 파일에서 소책자를 만들고 이를 HttpResponse에 저장합니다. |
| make_booklet(input_file, output_file, page_size) | 소스 파일에서 소책자를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_booklet(input_stream, output_stream, page_size) | PDF 파일에서 소책자를 만들고 이를 HttpResponse에 저장합니다. |
| make_booklet(input_file, output_file, left_pages, right_pages) | 소스 파일에서 소책자를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | PDF 파일에서 소책자를 만들고 이를 HttpResponse에 저장합니다. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | 소스 파일에서 소책자를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | PDF 파일에서 소책자를 만들고 이를 HttpResponse에 저장합니다. |
| make_n_up(input_file, output_file, x, y) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_n_up(input_stream, output_stream, x, y) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_n_up(input_stream, output_stream, x, y, page_size) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_n_up(first_input_file, second_input_file, output_file) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| make_n_up(input_files, output_file, is_sidewise) | 다중 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. <br/>            outputFile의 각 페이지에는 동일한 페이지 번호를 가진 입력 파일들의 페이지와 결합된 여러 페이지가 포함됩니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다. |
| make_n_up(input_streams, output_stream, is_sidewise) | 다중 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다.<br/>            outputStream의 각 페이지에는 동일한 페이지 번호를 가진 입력 스트림들의 페이지와 결합된 여러 페이지가 포함됩니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓습니다. |
| make_n_up(input_file, output_file, x, y, page_size) | N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다. |
| split_to_pages(input_file, file_name_template) | PDF 파일을 단일 페이지 문서로 분할합니다. |
| split_to_pages(input_stream, file_name_template) | PDF 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 필드 이름 템플릿으로 지정됩니다. |
| resize_contents(source, destination, pages, parameters) | 문서 페이지의 내용을 크기 조정합니다. 페이지가 축소된 경우 페이지 주변에 빈 여백이 추가됩니다. 결과는 HttpResponse 객체에 저장됩니다. |
| resize_contents(source, destination, pages, new_width, new_height) | 문서 페이지의 내용을 크기 조정합니다. <br/>            페이지 내용을 축소하고 여백을 추가합니다.<br/>            내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| resize_contents(source, destination, pages, new_width, new_height) | 문서 페이지의 내용을 크기 조정합니다. <br/>            페이지 내용을 축소하고 여백을 추가합니다.<br/>            내용의 새로운 크기는 기본 공간 단위로 지정됩니다. |
| resize_contents(source, destination, pages, parameters) | 문서 페이지의 내용을 크기 조정합니다. 페이지가 축소된 경우 페이지 주변에 빈 여백이 추가됩니다. 결과는 HttpResponse 객체에 저장됩니다. |
| resize_contents(source, pages, parameters) | 문서 페이지를 크기 조정합니다. 축소된 페이지 주변에 빈 여백이 추가됩니다. |
| resize_contents(source, parameters) | 문서 페이지를 크기 조정합니다. 축소된 페이지 주변에 빈 여백이 추가됩니다. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | 문서 페이지의 내용을 크기 조정합니다.<br/>            페이지 내용을 축소하고 여백을 추가합니다.<br/>            새로운 내용 크기는 퍼센트로 지정됩니다. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | 문서 페이지의 내용을 크기 조정합니다.<br/>            페이지 내용을 축소하고 여백을 추가합니다.<br/>            새로운 내용 크기는 퍼센트로 지정됩니다. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. <br/>            여백은 기본 공간 단위로 지정됩니다. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. <br/>            여백은 기본 공간 단위로 지정됩니다. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다.<br/>            여백은 초기 페이지 크기의 퍼센트로 지정됩니다. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다.<br/>            여백은 초기 페이지 크기의 퍼센트로 지정됩니다. |
| add_page_break(src, dest, page_breaks) | 문서 페이지에 페이지 나누기를 추가합니다. |
| add_page_break(src, dest, page_breaks) | 문서 페이지에 페이지 나누기를 추가합니다. |
| add_page_break(src, dest, page_breaks) | 문서 페이지에 페이지 나누기를 추가합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

