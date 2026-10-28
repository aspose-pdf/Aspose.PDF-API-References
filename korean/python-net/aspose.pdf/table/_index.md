---
title: "Table"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "페이지에 추가할 수 있는 테이블을 나타냅니다."
type: docs
weight: 1480
url: /ko/python-net/aspose.pdf/table/
---

## Table class

페이지에 추가할 수 있는 테이블을 나타냅니다.

Table 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Table() | Table 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| vertical_alignment | 단락의 수직 정렬을 가져오거나 설정합니다 |
| horizontal_alignment | 단락의 수평 정렬을 가져오거나 설정합니다 |
| margin | 단락의 외부 여백을 가져오거나 설정합니다 (PDF 생성용) |
| is_first_paragraph_in_column | 다음 열에 이 단락이 배치될지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_kept_with_next | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_new_page | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_line_paragraph | 단락이 인라인인지 여부를 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| hyperlink | 프래그먼트 하이퍼링크를 가져오거나 설정합니다 (PDF 생성기용). |
| z_index | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 <br/>            ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. 음수 ZIndex를 가진 그래프는 <br/>            페이지의 텍스트 뒤에 배치됩니다. |
| background_color | 테이블 배경 색을 가져오거나 설정합니다. |
| break_text | 테이블의 줄 바꿈 텍스트를 가져오거나 설정합니다 |
| corner_style | 테두리 모서리 스타일을 가져오거나 설정합니다 |
| repeating_rows_style | 반복 행에 대한 스타일을 가져옵니다 |
| repeating_columns_count | 테이블의 최대 열 수를 가져오거나 설정합니다 |
| repeating_rows_count | 여러 페이지에 걸쳐 반복되는 첫 번째 행 수를 가져옵니다 |
| column_widths | 테이블의 열 너비를 가져옵니다. |
| broken | 테이블 수직 파손을 가져오거나 설정합니다; |
| default_cell_border | 기본 셀 테두리를 가져옵니다; |
| default_column_width | 기본 셀 테두리를 가져옵니다; |
| rows | 테이블의 행을 가져옵니다. |
| 테두리 | 테두리를 가져오거나 설정합니다. |
| default_cell_padding | 기본 셀 패딩을 가져오거나 설정합니다. |
| default_cell_text_state | 기본 셀 텍스트 상태를 가져오거나 설정합니다. |
| 정렬 | 테이블 정렬을 가져오거나 설정합니다. |
| left | 테이블 왼쪽 좌표를 가져오거나 설정합니다. |
| top | 테이블 상단 좌표를 가져오거나 설정합니다. |
| is_broken | 테이블이 파손되었는지 가져오거나 설정합니다 - 다음 페이지에서 잘릴 것입니다. |
| is_borders_included | 열 너비에 포함된 테두리를 가져오거나 설정합니다. |
| column_adjustment | 테이블 열 조정을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| clone() | 테이블을 복제합니다. |
| get_width() | 너비를 가져옵니다. |
| get_height(parent_page) | 높이를 가져옵니다. |
| set_column_text_state(col_number, text_state) | 높이를 설정합니다. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | 데이터의 1차원 배열을 테이블에 가져옵니다. 가져오기는 배열의 각 항목당 하나의 셀에 매핑되며<br/>              매개변수에 정의된 행 및 열부터 시작합니다. 가져오는 동안 필요한 행이 아직 없음을 감지하면(예: 대상 테이블이 모든 데이터를 수용하기에 너무 작음), 필요한 행이 생성됩니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

