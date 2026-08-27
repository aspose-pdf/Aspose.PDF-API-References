---
title: "IsSigned"
second_title: "Aspose.PDF para Go vía C++"
description: "Obtener el estado de firma del documento PDF."
type: docs
url: /es/go-cpp/security/issigned/
---

_Obtener el estado de firma de PDF-document._

```go
func (document *Document) IsSigned() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is signed
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// IsSigned() obtiene el estado de firma de PDF-document
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
