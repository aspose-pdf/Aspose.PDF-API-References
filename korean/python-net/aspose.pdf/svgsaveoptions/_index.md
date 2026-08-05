---
title: "SvgSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "SVG 형식으로 내보내기 위한 저장 옵션"
type: docs
weight: 1460
url: /ko/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

SVG 형식으로 내보내기 위한 저장 옵션

SvgSaveOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| SvgSaveOptions() | SvgSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 저장 작업이 계속되지만, 사용자가 Abort를 반환하면 저장 작업이 중단되어야 합니다. |
| save_format | 데이터 저장 형식. |
| close_response | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| extract_ocr_sublayer_only | 없음 |
| try_merge_adjacent_same_background_images | 없음 |
| treat_target_file_name_as_directory | 이 옵션은 대상 디렉터리를 생성할지 여부를 정의합니다<br/>             (아직 존재하지 않을 경우) 요청된 출력 파일과 동일한 이름으로<br/>             요청된 출력 파일 자체 대신에.<br/>             이렇게 하면 해당 디렉터리에 페이지들의 모든 출력 SVG 이미지가 포함됩니다(아래에 설명된 대로).<br/>               아니오인 경우, 첫 번째 페이지를 제외한 페이지들의 출력 파일은 요청된 디렉터리 안에 정확히 생성되며<br/>            메인 출력 파일과 동일하지만 파일 이름에 _[2...n] 접미사가 붙으며,<br/>             이는 페이지 번호에 따라 정의됩니다. 예를 들어 출력 파일을 "C:\\AsposeTests\\output.svg" 로 정의하고<br/>             출력에 여러 페이지의 svg 파일이 포함되는 경우,<br/>             페이지 파일들은 또한 "C:\\AsposeTests\\" 디렉터리에 생성되고 이름은 'output.svg', 'output_2.svg', 'output_3.svg' 등입니다. |
| compress_output_to_zip_archive | 출력이 하나의 zip-archive로 생성될지 여부를 지정합니다.<br/>             'TreatTargetFileNameAsDirectory' 옵션에 대한 주석을 참조하여 다중 페이지 소스 문서의 페이지별 svg 파일 명명 규칙을 확인하십시오. 이 규칙은 압축된 출력 파일 세트에도 적용됩니다. |
| scale_to_pixels | 출력 문서를 타이포그래픽 포인트에서 픽셀로 스케일링할지 여부를 지정합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

