---
title: "OperatorCollection"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 연산자 컬렉션을 나타냅니다."
type: docs
weight: 1010
url: /ko/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

클래스는 연산자 컬렉션을 나타냅니다.

OperatorCollection 타입은 다음 멤버들을 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| is_fast_text_extraction_mode | 컬렉션이 빠른 텍스트 추출에만 제한되는지 여부를 나타냅니다. |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 인덱스로 연산자를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| insert(index, op) | 연산자를 컬렉션에 삽입합니다. |
| insert(at, ops) | 주어진 위치에 연산자를 삽입합니다. |
| insert(at, ops) | 연산자를 컬렉션에 삽입합니다. |
| delete(index) | 컬렉션에서 연산자를 삭제합니다. |
| delete(ops) | 컬렉션에서 연산자를 삭제합니다. |
| delete(list) | 없음 |
| add(ops) | 내용 연산자들의 끝에 연산자를 추가합니다. |
| add(ops) | 새 연산자를 컬렉션에 추가합니다. |
| suppress_update() | 내용 데이터 업데이트를 억제합니다.<br/>            ResumeUpdate가 호출될 때까지 내용 스트림이 업데이트되지 않습니다. |
| resume_update() | 문서 업데이트를 재개합니다.<br/>            보류 중인 변경 사항이 있는 경우 내용 스트림을 업데이트합니다. |
| cancel_update() | 마지막 업데이트를 취소합니다.<br/>            변경 사항이 내용 업데이트를 트리거하지 않아야 할 때 이 메서드를 호출할 수 있습니다. |
| accept(visitor) | 연산자를 처리하기 위해 IOperatorSelector 방문자 객체를 받아들입니다. |
| replace(operators) | 컬렉션의 연산자를 다른 연산자로 교체합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

