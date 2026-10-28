---
title: "AutoFiller"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "데이터베이스 또는 기타 데이터 소스에서 데이터를 수신하고, 템플릿 PDF의 설계된 필드에 채워 마지막에 새 PDF 파일이나 스트림을 생성하는 클래스를 나타냅니다.<br/>             두 가지 템플릿 파일 입력 모드가 있습니다: 스트림으로 입력하거나 PDF 파일로 입력합니다.<br/>             네 가지 출력 모드가 있습니다: 하나의 병합 스트림, 하나의 병합 파일, 여러 작은 스트림, 여러 작은 파일.<br/>             System.Data.DataTable에 포함된 리터럴 데이터를 수신할 수 있습니다."
type: docs
weight: 20
url: /ko/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

데이터베이스 또는 기타 데이터 소스에서 데이터를 수신하고, 템플릿 PDF의 설계된 필드에 채워 마지막에 새 PDF 파일이나 스트림을 생성하는 클래스를 나타냅니다.<br/>             두 가지 템플릿 파일 입력 모드가 있습니다: 스트림으로 입력하거나 PDF 파일로 입력합니다.<br/>             네 가지 출력 모드가 있습니다: 하나의 병합 스트림, 하나의 병합 파일, 여러 작은 스트림, 여러 작은 파일.<br/>             System.Data.DataTable에 포함된 리터럴 데이터를 수신할 수 있습니다.

AutoFiller 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| AutoFiller() | AutoFiller 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| output_stream | OutputStream을 가져오거나 설정합니다. 네 가지 출력 모드 중 하나입니다. 일반적인 사용 사례는 Response.OutputStream입니다.<br/>            온라인 데모를 참조하십시오. |
| output_streams | 다수의 Output Streams를 가져오거나 설정합니다. 네 가지 출력 모드 중 하나입니다. |
| input_stream | 입력 템플릿 스트림을 가져오거나 설정합니다. 두 가지 입력 모드 중 하나입니다. |
| input_file_name | 입력 템플릿 파일을 가져오거나 설정합니다. 두 가지 입력 모드 중 하나입니다. |
| output_file_name | 하나의 큰 병합된 출력 파일을 가져오거나 설정합니다. 네 가지 출력 모드 중 하나입니다. |
| generating_path | 많은 작은 PDF 파일이 생성될 경우 작은 PDF 파일들의 생성 경로를 가져오거나 설정합니다. 다른 속성인 [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName와 함께 작동합니다.<br/>            네 가지 출력 모드 중 하나입니다. |
| basic_file_name | 많은 작은 파일이 생성될 경우 기본 파일 이름을 가져오거나 설정합니다. 생성된 파일은 "BasicFileName0","BasicFileName1",...와 같은 형태가 됩니다.<br/>            다른 속성인 [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath와 함께 작동합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| save() | 모든 PDF를 저장합니다. |
| save(dest_file) | 모든 PDF를 저장합니다. |
| save(dest_stream) | 모든 PDF를 저장합니다. |
| bind_pdf(src_file) | PDF 파일을 바인딩합니다. |
| bind_pdf(src_stream) | PDF 파일을 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 바인딩합니다. |
| close() | 객체와 출력 스트림을 닫습니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

