---
title: "set_meta_info"
second_title: Aspose.PDF for Rust via C++
description: "Sets meta information value of PDF-document."
type: docs
url: /rust-cpp/core/set_meta_info/
---

_Sets meta information value of PDF-document._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Set meta information value of PDF-document
    pdf.set_meta_info("Author", "Aspose")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```