---
title: "FileSpecification"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "임베디드 파일을 나타내는 클래스."
type: docs
weight: 360
url: /ko/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

임베디드 파일을 나타내는 클래스.

FileSpecification 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| FileSpecification(file) | FileSpecification 클래스의 새 인스턴스를 초기화합니다 |
| FileSpecification(stream, name) | FileSpecification 클래스의 새 인스턴스를 초기화합니다 |
| FileSpecification(file, description) | FileSpecification 클래스의 새 인스턴스를 초기화합니다 |
| FileSpecification(stream, name, description) | FileSpecification 클래스의 새 인스턴스를 초기화합니다 |
| FileSpecification(file_name, annot) | FileSpecification 클래스의 새 인스턴스를 초기화합니다 |
| FileSpecification() | 새로운 빈 파일 사양을 생성합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| 인코딩 | 인코딩 형식을 가져오거나 설정합니다.<br/>            가능한 값: Zip - 파일이 ZIP으로 압축됨, <br/>            None - 파일이 압축되지 않음. |
| include_contents | true이면 파일의 내용이 파일 사양에 포함됩니다. |
| encrypted_payload | 암호화된 페이로드를 가져옵니다. |
| description | 파일 사양과 연결된 텍스트를 가져오거나 설정합니다. |
| af_relationship | 연관된 파일 관계입니다. |
| stream_contents | 파일 내용을 스트림으로 가져옵니다. <br/>            내용이 메모리에 로드되지 않아 메모리 사용량을 줄일 수 있습니다.<br/>            그러나 이 스트림은 위치 지정 및 Length 속성을 지원하지 않습니다. 이러한 기능이 필요하면 대신 Contents 속성을 사용하십시오. |
| 내용 | 내용 파일을 가져오거나 설정합니다. <br/>            이 속성은 메모리에 로드된 데이터를 반환하며, 대용량 데이터의 경우 메모리 부족 예외가 발생할 수 있습니다.<br/>            메모리 사용량을 줄이려면 StreamContents를 사용하십시오. |
| params | 파일 매개변수를 가져옵니다. |
| mime_type | 내장 파일의 서브타입을 가져옵니다. |
| 이름 | 파일 사양 이름을 가져오거나 설정합니다. |
| unicode_name | 파일 사양 유니코드 이름을 가져오거나 설정합니다. |
| file_system | 파일 시스템의 이름을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_value(key) | 응용 프로그램별 매개변수를 가져옵니다. |
| set_value(key, value) | 응용 프로그램별 매개변수를 설정합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

