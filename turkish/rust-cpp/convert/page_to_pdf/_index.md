---
title: "page_to_pdf"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Belirtilen sayfayı PDF belgesi olarak dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/page_to_pdf/
---

_Belirtilen sayfayı PDF belgesi olarak dönüştürür ve kaydeder._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Belirtilen sayfayı PDF belgesi olarak dönüştür ve kaydet
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```