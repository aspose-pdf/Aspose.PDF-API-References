---
title: "OpenWithPassword"
second_title: "Aspose.PDF för Go via C++"
description: "Öppna ett lösenordsskyddat PDF-dokument."
type: docs
url: /sv/go-cpp/security/openwithpassword/
---

_Öppna ett lösenordsskyddat PDF-dokument._

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
	// OpenWithPassword(filename string, password string) öppnar ett lösenordsskyddat PDF-dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// arbetar...
}
```
