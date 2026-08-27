---
title: "IsEncrypted"
second_title: "Aspose.PDF för Go via C++"
description: "Hämta krypteringsstatus för PDF-dokument."
type: docs
url: /sv/go-cpp/security/isencrypted/
---

_Hämta krypteringsstatus för PDF-dokument._

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
	// OpenWithPassword(filename string, password string) öppnar ett lösenordsskyddat PDF-dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// IsEncrypted() hämtar krypteringsstatus för PDF-dokument
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
