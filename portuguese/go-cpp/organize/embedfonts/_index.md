---
title: "EmbedFonts"
second_title: "Aspose.PDF para Go via C++"
description: "Incorporar fontes em um documento PDF."
type: docs
url: /pt/go-cpp/organize/embedfonts/
---

_Incorporar fontes em um PDF-document._

```go
func (document *Document) EmbedFonts() error
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
        // EmbedFonts() incorpora fontes em um PDF-document
        err = pdf.EmbedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
        err = pdf.SaveAs("sample_EmbedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
