---
title: "SetMetaInfo"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 메타 정보 값을 설정합니다."
type: docs
url: /ko/go-cpp/core/setmetainfo/
---

_PDF 문서의 메타 정보 값을 설정합니다._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// SetMetaInfo(key, value string) 은 PDF 문서의 메타 정보 값을 설정합니다
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
