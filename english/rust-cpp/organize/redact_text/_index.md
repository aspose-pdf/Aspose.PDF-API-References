---
title: "redact_text"
second_title: Aspose.PDF for Rust via C++
description: "Redact permanently and blacks out sensitive text in PDF-document."
type: docs
url: /rust-cpp/organize/redact_text/
---

_Redact permanently and blacks out sensitive text in PDF-document._

```rust
pub fn redact_text(&self, search_pattern: &str) -> Result<(), PdfError>
```

**Arguments**
  * **search_pattern** - the regular expression (regex, C#-like syntax) pattern used to search

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Redact permanently and blacks out sensitive text in PDF-document
    pdf.redact_text("aspose|pdf")?;

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_redact_text.pdf")?;

    Ok(())
}

```