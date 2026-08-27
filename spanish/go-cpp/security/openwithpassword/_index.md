---
title: "OpenWithPassword"
second_title: "Aspose.PDF para Go vía C++"
description: "Abrir un documento PDF protegido con contraseña."
type: docs
url: /es/go-cpp/security/openwithpassword/
---

_Abrir un PDF-document protegido con contraseña._

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
	// OpenWithPassword(filename string, password string) abre un documento PDF protegido con contraseña
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// trabajando...
}
```
