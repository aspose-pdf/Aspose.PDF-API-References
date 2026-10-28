---
title: "FormDataConverter"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "데이터를 한 형식에서 다른 형식으로 변환하는 클래스를 나타냅니다.<br/>            fdf/xml/pdf/xfdf 형식의 데이터를 OLEDB/OdbcDB로 변환할 수 있습니다.<br/>            또한 OLEDB/OdbcDB의 데이터를 fdf/xml/xfdf 형식으로 변환할 수 있습니다.<br/>            fdf를 \"hard-named\" 태그가 있는 xml로 변환할 수 있습니다."
type: docs
weight: 100
url: /ko/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

데이터를 한 형식에서 다른 형식으로 변환하는 클래스를 나타냅니다.<br/>            fdf/xml/pdf/xfdf 형식의 데이터를 OLEDB/OdbcDB로 변환할 수 있습니다.<br/>            또한 OLEDB/OdbcDB의 데이터를 fdf/xml/xfdf 형식으로 변환할 수 있습니다.<br/>            fdf를 "hard-named" 태그가 있는 xml로 변환할 수 있습니다.

FormDataConverter 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| FormDataConverter() | FormDataConverter 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| create_missing_field | ConvertToDataTable은 테이블에 존재하지 않을 경우 필요한 필드를 생성합니다. |
| replace_existing_table | ImportIntoDatabase는 이 속성이 true로 설정된 경우 기존 테이블을 삭제하고 새 테이블을 생성합니다. |
| clear_table_before_export | ExportFromData는 데이터 내보내기 전에 테이블을 정리합니다. |
| create_missing_table | ImportIntoDatabase는 테이블이 존재하지 않을 경우 테이블을 생성합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | XML 가져오기/내보내기 양식 데이터 파일을 FDF 형식으로 변환합니다. |
| convert_fdf_to_xml(source_fdf, dest_xml) | FDF 파일을 XML로 변환합니다. |
| convert_to_data_table(source_streams, source_type) | 스트림 파일을 테이블로 변환합니다. |
| import_into_data_base(connect_string, db_type) | 테이블에서 데이터베이스로 데이터를 가져옵니다. |
| export_from_data_base(connect_string, db_type) | 데이터베이스에서 테이블로 데이터를 내보냅니다. |
| convert_to_streams(dest_stream, dest_type) | 테이블의 데이터를 스트림으로 변환합니다. |
| conver_to_streams(dest_stream, dest_type) | 이 메서드는 더 이상 사용되지 않습니다. 대신 ConvertToStreams()를 사용하십시오. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

