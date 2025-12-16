---
title: "Decrypt"
second_title: Aspose.PDF for Go via C++
description: "Decrypt PDF-document."
type: docs
url: /go-cpp/security/decrypt/
---

_Decrypt PDF-document._

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
	// OpenWithPassword(filename string, password string) opens a password-protected PDF-document
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// Decrypt() decrypts PDF-document
	err = pdf.Decrypt()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_without_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
