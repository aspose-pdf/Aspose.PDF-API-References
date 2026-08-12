---
title: "page_remove_annotations"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sayfadaki açıklamaları kaldırır."
type: docs
url: /tr/rust-cpp/organize/page_remove_annotations/
---

_Sayfadaki açıklamaları kaldırır._

```rust
pub fn page_remove_annotations(&self, num: i32) -> Result<(), PdfError>
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

    // Sayfadaki açıklamaları kaldır
    pdf.page_remove_annotations(1)?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_page1_remove_annotations.pdf")?;

    Ok(())
}

```