---
title: "UnembedFonts"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort inbäddade teckensnitt i ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/unembedfonts/
---

_Ta bort inbäddning av teckensnitt i ett PDF-dokument._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // UnembedFonts() tar bort inbäddning av teckensnitt i ett PDF-dokument
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
