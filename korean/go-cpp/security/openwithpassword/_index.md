---
title: "OpenWithPassword"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "암호로 보호된 PDF-document를 엽니다."
type: docs
url: /ko/go-cpp/security/openwithpassword/
---

_비밀번호로 보호된 PDF-document을 엽니다._

```go
func OpenWithPassword(filename string, password string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document
  * **password** - user/owner password of the password-protected PDF-document

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
	// 작업 중...
}
```
