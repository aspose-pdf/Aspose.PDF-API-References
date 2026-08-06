---
title: "optimize_file_size"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının boyutunu görüntü sıkıştırma kalitesiyle optimize eder."
type: docs
url: /tr/rust-cpp/organize/optimize_file_size/
---

_PDF-dökümanının boyutunu görüntü sıkıştırma kalitesiyle optimize eder._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanının boyutunu görüntü sıkıştırma kalitesiyle optimize et
    pdf.optimize_file_size(50)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```