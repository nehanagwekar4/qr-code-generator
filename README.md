# QR Code Generator in Python

A simple Python project that generates QR codes from text or URLs. The project also supports custom colors and personalized QR codes with a logo placed at the center.

Built using Python, `qrcode`, and `Pillow`.

---

## Features

- Generate QR codes from plain text
- Generate QR codes for URLs
- Black & White QR Codes
- Custom colored QR Codes
- Personalized QR Codes with a custom logo
- High error correction (ERROR_CORRECT_H) for reliable scanning even with a logo

---

## Technologies Used

- Python 3
- qrcode
- Pillow (PIL)
---

## Installation

Install the required library:

pip install qrcode[pil]


## How to Run

### Install dependencies

pip install qrcode[pil]


### Run
python qr_code_generator.py

Enter any text or URL when prompted.

## Examples

**1. Black & White QR Code**
Input:
Hello World
Output:
- Standard QR Code
**2. Colored QR Code**
Input:
Hello World
Output:
- Pink QR Code
- Beige Background
### 3. QR Code with Logo
Input:
Any Link
Upload a logo image when prompted.
Output:
- Personalized QR Code with logo in the center

## Error Correction

This project uses:
```python
ERROR_CORRECT_H
```
which provides approximately **30% error correction**, allowing the QR code to remain scannable even after placing a logo at its center.

---

## Libraries Used

```python
import qrcode
from PIL import Image
```

---

## Future Improvements

- Rounded QR modules
- Gradient QR codes
- SVG export
- Batch QR generation from CSV
- GUI using Tkinter
- Web application using Flask or Streamlit
- Download QR codes directly from the browser
