---
title: "PageWordCount"
second_title: "Aspose.PDF für Go über C++"
description: "Wortanzahl auf der angegebenen Seite im PDF-Dokument zurückgeben."
type: docs
url: /de/go-cpp/core/pagewordcount/
---

_Gibt die Wortanzahl auf der angegebenen Seite im PDF-Dokument zurück._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) gibt die Wortanzahl auf der angegebenen Seite im PDF-Dokument zurück.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
