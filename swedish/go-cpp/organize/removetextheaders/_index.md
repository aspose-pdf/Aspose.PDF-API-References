---
title: "RemoveTextHeaders"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort textrubriker från PDF-dokumentet."
type: docs
url: /sv/go-cpp/organize/removetextheaders/
---

_Ta bort textrubriker från PDF-dokument._

```go
func (document *Document) RemoveTextHeaders() error
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
        // RemoveTextHeaders() tar bort textrubriker från PDF-dokument
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
