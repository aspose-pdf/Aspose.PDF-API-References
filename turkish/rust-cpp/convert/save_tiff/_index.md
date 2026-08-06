---
title: "save_tiff"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Açılmış PDF-dökümanını bir Tiff-dökümanına dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/save_tiff/
---

_Açılmış PDF-dökümanını bir Tiff-dökümanına dönüştürür ve kaydeder._

```rust
pub fn save_tiff(&self, resolution_dpi: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Açılmış PDF-dökümanını Tiff-dökümanına dönüştür ve kaydet
    pdf.save_tiff(100, "sample.tiff")?;

    Ok(())
}
```