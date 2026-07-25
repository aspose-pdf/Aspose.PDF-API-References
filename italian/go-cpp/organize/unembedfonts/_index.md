---
title: "UnembedFonts"
second_title: "Aspose.PDF per Go via C++"
description: "Rimuovi l'incorporamento dei caratteri da un PDF-document."
type: docs
url: /it/go-cpp/organize/unembedfonts/
---

_Rimuovi l'incorporamento dei caratteri da un documento PDF._

```go
func (document *Document) UnembedFonts() error
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
        // UnembedFonts() rimuove l'incorporamento dei caratteri da un documento PDF
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
