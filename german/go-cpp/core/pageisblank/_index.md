---
title: "PageIsBlank"
second_title: "Aspose.PDF für Go über C++"
description: "Gibt zurück, ob die Seite im PDF-Dokument leer ist."
type: docs
url: /de/go-cpp/core/pageisblank/
---

_Gibt zurück, ob die Seite im PDF-Dokument leer ist._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// PageIsBlank(num int32) gibt zurück, ob die Seite im PDF-Dokument leer ist.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
