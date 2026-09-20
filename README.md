# KDS INSURANCE - Life, Motor & Health Insurance Advisory Portal

Ye ek single-page responsive web portal hai jo LIC Life Insurance, General Motor Insurance, aur Health Mediclaim plans ke calculation, comparison aur clean A4 PDF/Print generation ke liye design kiya gaya hai.

---

## 🚀 Key Modules & Features

- **Life Insurance (LIC Engine):**
  - Saalana premium, policy term aur PPT ke anusaar calculation.
  - Year-by-year schedule chart (Normal Cover, ADDB Cover, Loan aur Surrender values).
  - Multi-plan comparison matrix (side-by-side tulna table).
  - Hindi aur English language switcher support.

- **Motor Insurance Engine:**
  - Car, Two-Wheeler aur Commercial vehicles ke liye instant premium estimate.
  - Third Party (TP), Comprehensive, Zero Dep (0-Dep), aur Standalone OD options.
  - NCB discount aur PA Owner-Driver cover calculations.
  - Itemized premium breakdown table with 18% GST.

- **Health Insurance (Mediclaim):**
  - Family Floater, Individual aur Senior Citizen options.
  - Sum Insured customizer (₹5 Lakh se ₹1 Crore tak).
  - Pre-existing disease (PED) loading aur room rent condition breakdown.

---

## 🛠️ Recent Fixes & Updates (Changelog)

1. **Independent Modal Print Engine (Fixed):**
   - Pehle LIC, Motor ya Health ka print command dene par tino modals ek sath print me aate the.
   - Print CSS (`@media print`) ko update kiya gaya jisme `.hidden` class wale modals print engine se exclude ho jate hain. Ab sirf active modal hi print/PDF me aata hai.

2. **Official Header Logo in All Print Layouts:**
   - Pehle `logo.png` sirf LIC ke print layout me render hota tha.
   - Ab **Motor Quotation** aur **Health Quotation** ke print letterhead me bhi `logo.png` aur proper alignment integrate kar diya gaya hai.

---

## 📁 File Structure

- `index.html` - Poora application code (HTML5, Tailwind CSS, Vanilla JS aur Print Styles).
- `logo.png` - Agency branding logo (header aur print formats me use hota hai).

---

## 📞 Advisor Contact Information

- **Agent Name:** Manoher Singh (Authorized Insurance Agent)
- **Helpline / WhatsApp:** +91 8440096343
- **Office:** BASEMENT HALL MR COMPLEX, Near Police Chowki, Malwara, Raniwara, Rajasthan 343039
