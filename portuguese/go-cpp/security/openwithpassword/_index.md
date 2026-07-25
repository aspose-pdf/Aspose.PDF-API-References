---
title: "OpenWithPassword"
second_title: "Aspose.PDF para Go via C++"
description: "Abra um documento PDF protegido por senha."
type: docs
url: /pt/go-cpp/security/openwithpassword/
---

_Abra um documento PDF protegido por senha._

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
	// OpenWithPassword(filename string, password string) abre um documento PDF protegido por senha
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// processando...
}
```
