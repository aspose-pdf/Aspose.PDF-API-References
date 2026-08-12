---
title: "page_remove_watermarks"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki filigranları kaldırır."
type: docs
url: /tr/rust-cpp/organize/page_remove_watermarks/
---

_Sayfadaki filigranları kaldırır._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfadaki filigranları kaldır
    pdf.page_remove_watermarks(1)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```