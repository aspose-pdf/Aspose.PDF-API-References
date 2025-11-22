---
title: "About"
second_title: Aspose.PDF for Go via C++
description: "Return metadata information about the Aspose.PDF for Go via C++."
type: docs
url: /go-cpp/miscellaneous/about/
---

_Return metadata information about the Aspose.PDF for Go via C++._

```go
func (document *Document) About() (*ProductInfo, error)
```

**Parameters**: 

**Return**: 
  * **ProductInfo** - struct, includes product name, version, release date, licensing status, and related details
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// About() returns metadata information about the Aspose.PDF for Go via C++
	info, err := pdf.About()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Aspose.PDF Product Info:")
	fmt.Println("  Product:     ", info.Product)
	fmt.Println("  Family:      ", info.Family)
	fmt.Println("  Version:     ", info.Version)
	fmt.Println("  ReleaseDate: ", info.ReleaseDate)
	fmt.Println("  Producer:    ", info.Producer)
	fmt.Println("  IsLicensed:  ", info.IsLicensed)
}
```
