---
title: "PageIsBlank"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver si la página está en blanco en el documento PDF."
type: docs
url: /es/go-cpp/core/pageisblank/
---

_Devuelve que la página está en blanco en el documento PDF._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
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
	// PageIsBlank(num int32) devuelve que la página está en blanco en el documento PDF.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Imprimir
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
