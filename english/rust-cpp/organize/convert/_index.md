---
title: "convert"
second_title: Aspose.PDF for Rust via C++
description: "Converts a PDF-document into a PDF-document with the specified PDF format."
type: docs
url: /rust-cpp/organize/convert/
---

_Converts a PDF-document into a PDF-document with the specified PDF format._

```rust
    pub fn convert(
        &self,
        pdf_format: PdfFormat,
        action: ConvertErrorAction,
    ) -> Result<(bool, String), PdfError>
```

**Arguments**
  * **pdf_format** - the target PDF format standard (enum [PdfFormat](../../))
  * **action** - the action to take on conversion errors (enum [ConvertErrorAction](../../))

**Returns**
  * **Ok((bool, String))** - the operation result, `String` contains the conversion log
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{ConvertErrorAction, Document, PdfFormat};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Convert a PDF-document into a PDF-document with the specified PDF format
    let (ok, log) = pdf.convert(PdfFormat::PDF_A_2A, ConvertErrorAction::Delete)?;

    // Print conversion result and full log
    println!("Convert PDF/A result: {}", ok);
    println!("Convert PDF/A log:\n{}", log);

    // Save the previously opened PDF-document with new filename
    pdf.save_as("sample_convert.pdf")?;

    Ok(())
}

```