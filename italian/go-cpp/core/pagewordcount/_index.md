---
title: "PageWordCount"
second_title: "Aspose.PDF per Go via C++"
description: "Restituisci il conteggio delle parole nella pagina specificata del documento PDF."
type: docs
url: /it/go-cpp/core/pagewordcount/
---

_Restituisci il conteggio delle parole nella pagina specificata del documento PDF._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageWordCount(num int32) restituisce il conteggio delle parole nella pagina specificata del documento PDF.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
