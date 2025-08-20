---
title: "page_to_pdf"
second_title: Aspose.PDF for Rust via C++
description: "Converts and saves the specified page as a PDF-document."
type: docs
url: /rust-cpp/convert/page_to_pdf/
---

_Converts and saves the specified page as a PDF-document._

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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert and save the specified page as PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```