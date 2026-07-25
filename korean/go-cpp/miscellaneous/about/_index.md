---
title: "About"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "C++를 통해 Aspose.PDF for Go에 대한 메타데이터 정보를 반환합니다."
type: docs
url: /ko/go-cpp/miscellaneous/about/
---

_C++를 통해 Go용 Aspose.PDF에 대한 메타데이터 정보를 반환합니다._

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
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// About() 은 C++를 통해 Go용 Aspose.PDF에 대한 메타데이터 정보를 반환합니다
	info, err := pdf.About()
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Aspose.PDF Product Info:")
	fmt.Println("  Product:     ", info.Product)
	fmt.Println("  Family:      ", info.Family)
	fmt.Println("  Version:     ", info.Version)
	fmt.Println("  ReleaseDate: ", info.ReleaseDate)
	fmt.Println("  Producer:    ", info.Producer)
	fmt.Println("  IsLicensed:  ", info.IsLicensed)
}
```
