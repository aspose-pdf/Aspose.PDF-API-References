---
title: "page_to_png"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Belirtilen sayfayı PNG görüntüsü olarak dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/page_to_png/
---

_Belirtilen sayfayı PNG görüntüsü olarak dönüştürür ve kaydeder._

```rust
pub fn page_to_png(&self, num: i32, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **resolution_dpi** - the resolution in DPI
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Belirtilen sayfayı Png görüntüsü olarak dönüştür ve kaydet
    pdf.page_to_png(1, 100, "sample_page1.png")?;

    Ok(())
}

```