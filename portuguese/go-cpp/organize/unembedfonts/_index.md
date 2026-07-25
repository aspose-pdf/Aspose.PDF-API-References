---
title: "UnembedFonts"
second_title: "Aspose.PDF para Go via C++"
description: "Desincorporar fontes de um documento PDF."
type: docs
url: /pt/go-cpp/organize/unembedfonts/
---

_Desincorporar fontes de um PDF-document._

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
        // Open(filename string) abre um documento PDF com o nome de arquivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera os recursos alocados para o documento PDF
        defer pdf.Close()
        // UnembedFonts() desincorpora fontes de um PDF-document
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
