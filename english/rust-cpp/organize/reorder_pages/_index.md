---
title: "reorder_pages"
second_title: Aspose.PDF for Rust via C++
description: "Reorders pages in PDF-document."
type: docs
url: /rust-cpp/organize/reorder_pages/
---

_Reorders pages in PDF-document._

```rust
pub fn reorder_pages(&self, num_pages: &[i32]) -> Result<(), PdfError>
```

**Arguments**
  * **num_pages** - slice of new page positions (1-based); the pages listed are placed first in the specified order, while all unlisted pages retain their original order and follow them

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Reorder pages in PDF-document
    pdf.reorder_pages(&[2, 1])?;

    // Save the modified PDF-document with a new filename
    pdf.save_as("sample_reorder_pages.pdf")?;

    Ok(())
}

```