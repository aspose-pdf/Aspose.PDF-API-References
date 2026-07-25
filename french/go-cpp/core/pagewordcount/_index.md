---
title: "PageWordCount"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le nombre de mots sur la page spécifiée du PDF-document."
type: docs
url: /fr/go-cpp/core/pagewordcount/
---

_Retourner le nombre de mots sur la page spécifiée du PDF-document._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageWordCount(num int32) renvoie le nombre de mots sur la page spécifiée du PDF-document.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
