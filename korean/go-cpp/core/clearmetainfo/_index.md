---
title: "ClearMetaInfo"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 모든 메타 정보 값을 지웁니다."
type: docs
url: /ko/go-cpp/core/clearmetainfo/
---

_PDF 문서의 모든 메타 정보 값을 지웁니다._

```go
func (document *Document) ClearMetaInfo() error
```

**Parameters**: 

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
	// ClearMetaInfo()는 PDF 문서의 모든 메타 정보 값을 지웁니다
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
