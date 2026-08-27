---
title: "IsLinearized"
second_title: "Aspose.PDF para Go vía C++"
description: "Obtener un valor que indique si el documento está linealizado."
type: docs
url: /es/go-cpp/core/islinearized/
---

_Obtiene un valor que indica si el documento está linealizado._

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// IsLinearized() obtiene un valor que indica si el documento está linealizado
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
