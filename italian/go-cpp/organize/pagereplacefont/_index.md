---
title: "PageReplaceFont"
second_title: "Aspose.PDF per Go via C++"
description: "Sostituisci il carattere nella pagina."
type: docs
url: /it/go-cpp/organize/pagereplacefont/
---

_Sostituisci il carattere nella pagina._

```go
func (document *Document) PageReplaceFont(num int32, findFontName, replaceFontName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // PageReplaceFont(num int32, findFontName, replaceFontName string) sostituisce il carattere nella pagina
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
