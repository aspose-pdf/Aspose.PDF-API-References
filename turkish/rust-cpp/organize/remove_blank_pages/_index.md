---
title: "remove_blank_pages"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dosyadan boş sayfaları kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_blank_pages/
---

_PDF-dosyadan boş sayfaları kaldırır._

```rust
pub fn remove_blank_pages(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dokümanından boş sayfaları kaldır
    pdf.remove_blank_pages()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_blank_pages.pdf")?;

    Ok(())
}

```