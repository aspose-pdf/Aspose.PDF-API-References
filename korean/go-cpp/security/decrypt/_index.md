---
title: "Decrypt"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document를 복호화합니다."
type: docs
url: /ko/go-cpp/security/decrypt/
---

_PDF-document를 복호화합니다._

```go
func (document *Document) Decrypt() error
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
	// OpenWithPassword(filename string, password string) 은 암호로 보호된 PDF-document를 엽니다
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// Decrypt() 은 PDF-document를 복호화합니다
	err = pdf.Decrypt()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_without_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
