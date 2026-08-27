---
title: "PageCount"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el recuento de páginas del documento PDF."
type: docs
url: /es/go-cpp/core/pagecount/
---

_Devuelve el recuento de páginas en el PDF-documento._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
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
	// PageCount() devuelve el recuento de páginas en el PDF-documento
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("Count:", count)
}
```
