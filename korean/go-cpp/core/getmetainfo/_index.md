---
title: "GetMetaInfo"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 메타 정보 값을 가져옵니다."
type: docs
url: /ko/go-cpp/core/getmetainfo/
---

_PDF 문서의 메타 정보 값을 가져옵니다._

```go
func (document *Document) GetMetaInfo(key string) (string, error)
```

**Parameters**: 
  * **key** - key whose value to get

**Return**: 
  * **string** - value associated with the specified key
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// GetMetaInfo(key string) 메서드는 PDF 문서의 메타 정보 값을 가져옵니다
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Author: ", value)
}
```
