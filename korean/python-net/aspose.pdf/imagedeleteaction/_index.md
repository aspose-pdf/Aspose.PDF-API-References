---
title: "ImageDeleteAction"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "이미지 객체가 컬렉션에서 제거될 때 수행되는 작업입니다. 이미지 객체가 제거되면"
type: docs
weight: 6450
url: /ko/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

이미지 객체가 컬렉션에서 제거될 때 수행되는 작업입니다. 이미지 객체가 제거되면

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| KEEP_CONTENTS | 이미지는 컬렉션에서 제거됩니다. 페이지 내용에 이미지에 대한 참조가 포함되어 있으면 해당 참조는 제거되지 않습니다. 문서가 손상될 수 있습니다. |
| NONE | 이미지는 컬렉션 및 페이지 내용에서 제거되지만 이미지 객체는 삭제되지 않습니다. 파일 크기가 감소하지 않습니다. |
| FORCE_DELETE | 이미지는 컬렉션에서 제거되고 이미지 객체는 문서에서 제거됩니다. 동일 객체에 다른 참조가 존재하면 문서가 손상될 수 있습니다. |
| CHECK | 이미지는 컬렉션에서 제거되며, 다른 페이지에서 이미지에 대한 다른 참조가 없을 경우에만 이미지 객체가 제거됩니다. 이는 ForceDelete 옵션에 비해 더 많은 시간이 걸릴 수 있습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

