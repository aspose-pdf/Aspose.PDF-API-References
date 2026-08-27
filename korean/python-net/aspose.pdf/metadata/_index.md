---
title: "Metadata"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "XMP 메타데이터 스트림에 대한 접근을 제공합니다."
type: docs
weight: 930
url: /ko/python-net/aspose.pdf/metadata/
---

## Metadata class

XMP 메타데이터 스트림에 대한 접근을 제공합니다.

Metadata 형식은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| is_fixed_size | 컬렉션이 고정 크기인지 확인합니다. |
| keys | 메타데이터 키 컬렉션을 가져옵니다. |
| values | 메타데이터의 값을 가져옵니다. |
| is_synchronized | 컬렉션이 동기화되었는지 확인합니다. |
| sync_root | 컬렉션 동기화 객체를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | 네임스페이스 URI를 등록합니다. |
| register_namespace_uri(prefix, namespace_uri, schema_description) | 네임스페이스 URI를 등록합니다. |
| add(key, value) | 메타데이터에 값을 추가합니다. |
| add(key, value) | 메타데이터에 값을 추가합니다. |
| add(prefix, value) | 메타데이터에 pdf 확장을 추가합니다. |
| get_namespace_uri_by_prefix(prefix) | 접두사로 네임스페이스 URI를 반환합니다. |
| get_prefix_by_namespace_uri(namespace_uri) | 네임스페이스 URI로부터 접두사를 반환합니다. |
| contains(key) | 키가 메타데이터에 포함되어 있는지 확인합니다. |
| remove(key) | 메타데이터에서 항목을 제거합니다. |
| contains_key(key) | 이 사전이 지정된 키를 포함하고 있는지 확인합니다. |
| try_get_value(key, value) | 사전에서 키를 찾아서, 찾으면 값을 반환합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

