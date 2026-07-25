---
title: "PageReplaceText"
second_title: "Aspose.PDF per Go via C++"
description: "Sostituisci il testo sulla pagina."
type: docs
url: /it/go-cpp/organize/pagereplacetext/
---

_Sostituisci il testo nella pagina._

```go
func (document *Document) PageReplaceText(num int32, findText, replaceText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageReplaceText(num int32, findText, replaceText string) sostituisce il testo nella pagina
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
