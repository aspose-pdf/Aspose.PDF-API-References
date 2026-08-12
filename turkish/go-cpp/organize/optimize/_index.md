---
title: "Optimize"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesi içeriğini optimize et."
type: docs
url: /tr/go-cpp/organize/optimize/
---

_PDF belgesi içeriğini optimize et._

```go
func (document *Document) Optimize() error
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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// Optimize() PDF belgesi içeriğini optimize eder
	err = pdf.Optimize()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_Optimize.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
