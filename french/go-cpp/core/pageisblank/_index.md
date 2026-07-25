---
title: "PageIsBlank"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner si la page est vide dans le PDF-document."
type: docs
url: /fr/go-cpp/core/pageisblank/
---

_Renvoie que la page est vide dans le PDF-document._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageIsBlank(num int32) renvoie que la page est vide dans le PDF-document.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
