# Freelancer GST Invoice Generator (Indian Tax Compliant)

A modern, fast, and 100% client-side GST invoice generator specially designed for Indian freelancers, agencies, consultants, and remote contractors.

---

## 🚀 Quick Start

You can run this immediately in any browser—**no installation or server needed**!

1. Open the file directly in your browser:
   - Double-click **`index.html`** or **`open_invoice_generator.bat`**
   - Or open `C:\Users\Guruvayurappan\.gemini\antigravity\scratch\freelance-gst-invoice-generator\index.html` in Chrome / Edge / Firefox.

2. Fill in your details or test with the pre-filled sample data.
3. Click **"Print / PDF Download"** (or press `Ctrl + P`) and select **"Save as PDF"**!

---

## 💡 Key Features Built for Indian Freelancers

### 1. Automated GST Tax Determination
- **Intra-State Supply**: When your state matches the client's place of supply, tax is automatically split into **CGST (9%) + SGST (9%)**.
- **Inter-State Supply**: When billing clients in a different state, the system automatically applies **IGST (18%)**.
- **Export of Services under LUT (0% GST)**:
  - Supports foreign clients (US, Europe, etc.) under Letter of Undertaking (LUT) with ARN tracking.
  - Automatically adds the statutory declaration required under Section 16 of the IGST Act:
    > *"SUPPLY MEANT FOR EXPORT UNDER BOND OR LETTER OF UNDERTAKING WITHOUT PAYMENT OF INTEGRATED TAX"*
- **Export with Payment of IGST**: Option to bill foreign clients with integrated tax.
- **Reverse Charge Mechanism (RCM)**: Toggle for transactions subject to reverse charge.

### 2. Standard Service Accounting Codes (SAC)
Includes a curated quick-select dropdown of the most common SAC codes for freelancers:
- **998314**: Web design, software original, and programming services
- **998311**: Information technology (IT) consulting and support services
- **998312**: Application development services
- **998365**: Graphic, UI/UX, and multimedia design
- **998361**: Advertising, marketing strategy, and social media consultancy
- **998439**: Translation, content writing, copywriting, and editing
- **998431**: Video production and audio editing
- **998391**: Technical consultancy and SEO strategy

### 3. Instant UPI QR Code Generator
- Generates a standard NPCI-compliant dynamic UPI QR code (`upi://pay?pa=...&pn=...&am=...`).
- Domestic Indian clients can point their phone camera (Google Pay, PhonePe, Paytm, CRED, BHIM) to pay the exact invoice amount instantly.

### 4. Indian Currency & Number-to-Words
- Formats amounts in Indian format (`₹1,00,000.00`).
- Automatically translates the grand total into Indian words (e.g., *"One Lakh Eighteen Thousand Rupees Only"*).
- Multi-currency support (USD, EUR, GBP, AED, CAD, SGD) for international clients.

### 5. Local Storage Auto-Save
- Click **"Save Profile"** to store your Trade Name, GSTIN, PAN, Address, Bank details, and UPI ID directly in your browser.
- Next time you open the app, your profile is automatically loaded.

### 6. A4 Pixel-Perfect PDF Export
- Engineered with strict `@page` print rules to fit standard A4 paper without pagination glitches or broken tables.
- Multiple color themes (Indigo Modern, Emerald Growth, Sky Tech, and Minimal Slate).

---

## 📋 Standard GST Invoice Checklist Included:
- [x] Document Title (`TAX INVOICE` / `BILL OF SUPPLY`)
- [x] Consecutive Invoice Number (Alphanumeric)
- [x] Date of Invoice & Payment Due Date
- [x] Supplier Name, Address, GSTIN, PAN & State Code
- [x] Client / Recipient Name, Address, GSTIN & Place of Supply (POS)
- [x] Itemized Table with Service Description, SAC, Qty, Rate & Taxable Value
- [x] Tax breakdown (CGST, SGST, IGST)
- [x] LUT ARN Number & Export Clause (for zero-rated exports)
- [x] Bank Details & IFSC Code
- [x] Authorized Signatory Block
