---
title: "IsEncrypted"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document의 암호화 상태를 가져옵니다."
type: docs
url: /ko/go-cpp/security/isencrypted/
---

_PDF-document의 암호화 상태를 가져옵니다._

```go
func (document *Document) IsEncrypted() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is encrypted
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// OpenWithPassword(filename string, password string) 은 암호로 보호된 PDF-document를 엽니다
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// IsEncrypted() 은 PDF-document의 암호화 상태를 가져옵니다
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
