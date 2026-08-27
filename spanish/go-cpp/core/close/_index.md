---
title: "Close"
second_title: "Aspose.PDF para Go vía C++"
description: "Liberar los recursos asignados para el documento PDF."
type: docs
url: /es/go-cpp/core/close/
---

_Libera los recursos asignados para el documento PDF._

```go
func (document *Document) Close() error
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
	// New crea un nuevo PDF-documento
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
