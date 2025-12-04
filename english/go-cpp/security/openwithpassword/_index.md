---
title: "OpenWithPassword"
second_title: Aspose.PDF for Go via C++
description: "Open a password-protected PDF-document."
type: docs
url: /go-cpp/security/openwithpassword/
---

_Open a password-protected PDF-document._

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
	// OpenWithPassword(filename string, password string) opens a password-protected PDF-document
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// working...
}
```
