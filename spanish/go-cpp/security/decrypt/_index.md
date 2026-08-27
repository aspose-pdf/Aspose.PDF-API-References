---
title: "Decrypt"
second_title: "Aspose.PDF para Go vía C++"
description: "Descifrar el documento PDF."
type: docs
url: /es/go-cpp/security/decrypt/
---

_Desencripta documento PDF._

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
	// OpenWithPassword(filename string, password string) abre un documento PDF protegido con contraseña
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// Decrypt() desencripta documento PDF
	err = pdf.Decrypt()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_without_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
