---
title: "page_set_size"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümandaki bir sayfanın boyutunu ayarlar."
type: docs
url: /tr/rust-cpp/organize/page_set_size/
---

_PDF-dökümandaki bir sayfanın boyutunu ayarlar._

```rust
pub fn page_set_size(&self, num: i32, page_size: PageSize) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **page_size** - page size as enum `PageSize`: `A0`, `A1`, `A2`, `A3`, `A4`, `A5`, `A6`, `B5`, `PageLetter`, `PageLegal`, `PageLedger`, or `P11x17`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, PageSize};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümandaki bir sayfanın boyutunu ayarla
    pdf.page_set_size(1, PageSize::A1)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_set_size_A1.pdf")?;

    Ok(())
}

```