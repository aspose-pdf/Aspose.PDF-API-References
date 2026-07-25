---
title: "IsEncrypted"
second_title: "Aspose.PDF para Go vía C++"
description: "Obtener el estado de cifrado del documento PDF."
type: docs
url: /es/go-cpp/security/isencrypted/
---

_Obtiene el estado cifrado del documento PDF._

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
	// OpenWithPassword(filename string, password string) abre un documento PDF protegido con contraseña
	pdf, err := asposepdf.OpenWithPassword("sample_with_password.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// IsEncrypted() obtiene el estado cifrado del documento PDF
	isEnc, _ := pdf.IsEncrypted()
	if isEnc {
		fmt.Println("IsEncrypted() is true")
	}
}
```
