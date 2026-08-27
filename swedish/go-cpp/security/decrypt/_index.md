---
title: "Decrypt"
second_title: "Aspose.PDF för Go via C++"
description: "Dekryptera PDF-dokument."
type: docs
url: /sv/go-cpp/security/decrypt/
---

_Dekryptera PDF-dokument._

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
	// OpenWithPassword(filename string, password string) öppnar ett lösenordsskyddat PDF-dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// Decrypt() dekrypterar PDF-dokument
	err = pdf.Decrypt()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_without_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
