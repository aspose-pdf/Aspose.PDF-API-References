---
title: "OpenWithPassword"
second_title: "Aspose.PDF untuk Go via C++"
description: "Buka PDF-dokumen yang dilindungi kata sandi."
type: docs
url: /id/go-cpp/security/openwithpassword/
---

_Buka dokumen PDF yang dilindungi kata sandi._

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
	// OpenWithPassword(filename string, password string) membuka dokumen PDF yang dilindungi kata sandi
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// sedang bekerja...
}
```
