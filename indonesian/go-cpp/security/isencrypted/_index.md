---
title: "IsEncrypted"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan status terenkripsi dari PDF-dokumen."
type: docs
url: /id/go-cpp/security/isencrypted/
---

_Dapatkan status terenkripsi dari PDF-document._

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
	// OpenWithPassword(filename string, password string) membuka dokumen PDF yang dilindungi kata sandi
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// IsEncrypted() mendapatkan status terenkripsi dari PDF-document
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
