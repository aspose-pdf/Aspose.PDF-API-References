---
title: "LatexLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서에 TeX 파일을 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 820
url: /ko/python-net/aspose.pdf/latexloadoptions/
---

## LatexLoadOptions class

PDF 문서에 TeX 파일을 로드/임포트하기 위한 옵션을 나타냅니다.

LatexLoadOptions 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| LatexLoadOptions() | LatexLoadOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 모든 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환하면 로드 작업이 중단되어야 합니다. |
| load_format | 파일 형식을 나타내며, [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)에서 설명합니다. |
| job_name | 작업의 이름을 가져오거나 설정합니다. |
| input_directory | TeX 입력 디렉터리를 가져오거나 설정합니다. |
| output_directory | TeX 출력 디렉터리를 가져오거나 설정합니다. |
| repeat | TeX 작업을 두 번 실행해야 하는지 여부를 나타내는 플래그를 가져오거나 설정합니다.<br/>            예를 들어 입력 TeX 파일에 참조가 있는 경우입니다. 일반적으로 이 동작은 엔진이 조판 과정에서 일부 데이터를 수집하여 보조 파일에 저장하고,<br/>            첫 번째 실행에서 모두 저장할 때 유용합니다. 그리고 두 번째 실행에서 엔진이 해당 데이터를 어떤 식으로든 사용합니다. |
| subset_fonts | 출력 파일에서 글꼴을 서브셋팅할지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| show_terminal_output | 콘솔에 터미널 출력을 표시할지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
| date_time | \year, \month, \day 및 \time 과 같은 날짜/시간 원시값에 대한 특정 값을 가져오거나 설정합니다. |
| no_ligatures | 모든 글꼴에서 합자를 취소하는 플래그를 가져오거나 설정합니다. |
| rasterize_formulas | 수학 수식을 래스터화하도록 허용하는 플래그를 가져오거나 설정합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

