---
title: "RemoveTextFooters"
second_title: "Aspose.PDF per Go via C++"
description: "Rimuovi i piè di pagina di testo dal PDF-document."
type: docs
url: /it/go-cpp/organize/removetextfooters/
---

_Rimuovi i piè di pagina di testo dal documento PDF._

```go
func (document *Document) RemoveTextFooters() error
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
        // Open(filename string) apre un PDF-document con filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() rilascia le risorse allocate per il PDF-document
        defer pdf.Close()
        // RemoveTextFooters() rimuove i piè di pagina di testo dal documento PDF
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
