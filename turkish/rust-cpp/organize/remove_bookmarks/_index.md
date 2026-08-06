---
title: "remove_bookmarks"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'ten yer imlerini kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_bookmarks/
---

_PDF-document'ten yer imlerini kaldırır._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından yer imlerini kaldır
    pdf.remove_bookmarks()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```