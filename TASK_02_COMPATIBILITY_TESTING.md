# ✅ Internship Task 2: Compatibility Testing for a Basic Web Page

**Internship Role:** Software Testing Intern  
**Internship Provider:** Prodigy Infotech  
**Task:** Conduct Compatibility Testing for a Basic Web Page  
**Task Type:** Manual Testing  
**Website Tested:** [Demo E-commerce Website](https://example-ecommerce-demo.com) <!-- Replace with actual link -->  
**Date:** 16 June 2025   
**Submitted by:** Kanishkaa Balu
---

## 🧪 Objective

To perform compatibility testing of a basic e-commerce website across different browsers and devices. Identify layout issues, broken links, and functional discrepancies. Provide documentation and recommendations for fixes.

---

## 🖥️ Browsers Tested

| Browser          | Version   |
|------------------|-----------|
| Google Chrome    | 125.0.x   |
| Mozilla Firefox  | 127.0.x   |
| Microsoft Edge   | 125.0.x   |
| Safari (Mobile)  | 17.4      |

---

## 📱 Devices Used

| Device         | Type     | OS          | Screen Size |
|----------------|----------|-------------|--------------|
| Dell Laptop    | Desktop  | Windows 11  | 1920x1080    |
| iPad (Gen 9)   | Tablet   | iPadOS 17   | 810x1080     |
| iPhone 13      | Mobile   | iOS 17      | 390x844      |
| Samsung M14    | Mobile   | Android 14  | 412x915      |

---

## ✅ Compatibility Testing Checklist

| Test Case                          | Chrome | Firefox | Edge | Safari (Mobile) | Notes |
|-----------------------------------|--------|---------|------|------------------|-------|
| Homepage loads correctly          | ✅     | ✅      | ✅   | ✅               | -     |
| Navigation bar responsive         | ✅     | ✅      | ✅   | ⚠️                | Menu not collapsing on iOS Safari |
| Product images loading            | ✅     | ✅      | ✅   | ✅               | -     |
| “Add to Cart” button functionality| ✅     | ✅      | ✅   | ✅               | -     |
| Checkout form rendering properly  | ✅     | ✅      | ✅   | ✅               | -     |
| Broken links                      | ❌     | ❌      | ❌   | ❌               | FAQ page link broken |
| Font & layout consistent          | ✅     | ✅      | ✅   | ⚠️                | Minor font size issue on Safari |
| Touch responsiveness (mobile)     | ✅     | ✅      | ✅   | ✅               | -     |

---

## 🐞 Issues Found

| Issue                          | Browser/Device         | Description                                | Severity | Recommendation                              |
|--------------------------------|------------------------|--------------------------------------------|----------|----------------------------------------------|
| Navbar not collapsing          | Safari (iPhone/iPad)   | Hamburger menu doesn’t function properly   | Medium   | Use JS-based fix or polyfill for Safari CSS  |
| FAQ page link broken           | All browsers           | Link returns 404 error                     | High     | Fix the target URL or update navigation      |
| Font inconsistency             | Safari (iOS)           | Slight font size mismatch                  | Low      | Use relative units like `em` or `rem`        |
