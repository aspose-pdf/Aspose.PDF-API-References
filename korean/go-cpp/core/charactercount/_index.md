---
title: "CharacterCount"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 문자 수를 반환합니다."
type: docs
url: /ko/go-cpp/core/charactercount/
---

_PDF-document의 문자 수를 반환합니다._

```go
func (document *Document) CharacterCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - character count of the PDF-document
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
	// CharacterCount()는 PDF-document의 문자 수를 반환합니다
	character_count, err := pdf.CharacterCount()
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Character count:", character_count)
}
```
