# 📚 Clinical Reference Suite (CRS)

**Version:** 1.0 BUILD #8  
**Last Updated:** January 2026  
**Optimized for:** iPad (iOS Safari) • Hospital Use • Board Review

---

## 🎯 Overview

A comprehensive, iPad-optimized collection of clinical reference tools and study materials for Internal Medicine residents and hospitalists. Designed for rapid bedside access with dark mode optimization, touch-friendly navigation, and offline capability.

**Total Files:** 39 HTML files  
**Categories:** Clinical References • Study Guides • Audio Editions

---

## 📱 Quick Start

1. **Main Entry Point:** `index.html` — Clinical Reference Suite dashboard
2. **Study Guides Hub:** `study_guides_index.html` — All specialty study guides + audio editions
3. **Deploy to GitHub Pages** for instant mobile access

---

## 📂 File Inventory

### 🏥 Clinical Reference Tools (11 files)

| File | Description |
|------|-------------|
| `index.html` | Main CRS dashboard with sidebar navigation |
| `im_guide.html` | Internal Medicine Clinical Reference (118 conditions) |
| `id_guide.html` | Infectious Disease Quick Reference |
| `drug_reference_guide.html` | Drug Reference Guide (500+ medications) |
| `lab_values.html` | Laboratory Values Clinical Reference |
| `dx_framework.html` | Diagnostic Framework & Decision Support |
| `renal_dosing_reference.html` | Renal Dosing Adjustments |
| `antimicrobial_stewardship_guide.html` | Antimicrobial Stewardship Principles |
| `drug_interactions.html` | Drug Interactions Reference |
| `procedures_guide.html` | Common Procedures Guide |
| `high_value_care.html` | High-Value Care Recommendations |

### 📖 Study Guides (17 specialties)

All study guides follow consistent formatting with:
- Expandable sections
- High-yield boxes
- Clinical pearls
- Board-style vignettes
- Evidence-based guidelines

| File | Specialty | ABIM Weight |
|------|-----------|-------------|
| `cardio_study_guide.html` | Cardiology | 14% |
| `pulmonology_study_guide.html` | Pulmonology | 10% |
| `gi_study_guide.html` | Gastroenterology | 9% |
| `endocrinology_study_guide.html` | Endocrinology | 8% |
| `heme_onc_study_guide.html` | Hematology/Oncology | 8% |
| `rheumatology_study_guide.html` | Rheumatology | 8% |
| `id_study_guide.html` | Infectious Disease | 8% |
| `nephrology_study_guide.html` | Nephrology | 7% |
| `neurology_study_guide.html` | Neurology | 6% |
| `general_im_study_guide.html` | General Internal Medicine | 6% |
| `geriatrics_study_guide.html` | Geriatrics | 4% |
| `psychiatry_study_guide.html` | Psychiatry | 4% |
| `allergy_immunology_study_guide.html` | Allergy & Immunology | 3% |
| `dermatology_study_guide.html` | Dermatology | 3% |
| `womens_health_study_guide.html` | Women's Health | 3% |
| `palliative_care_study_guide.html` | Palliative Care | 2% |
| `perioperative_study_guide.html` | Perioperative Medicine | — |
| `board_pearls.html` | High-Yield Board Pearls | — |

### 🎧 Audio Study Guides (9 specialties)

Text-to-speech optimized for commute listening. Features:
- Web Speech API integration
- English-only voice selection (iOS Safari compatible)
- Adjustable speed (0.75× to 2×)
- Configurable pause lengths
- Chapter navigation
- Position memory (resume playback)
- Real-time text highlighting

| File | Specialty | Est. Duration |
|------|-----------|---------------|
| `cardio_study_guide_audio.html` | Cardiology | ~72 min |
| `pulmonology_study_guide_audio.html` | Pulmonology | ~51 min |
| `gi_study_guide_audio.html` | Gastroenterology | ~37 min |
| `endocrinology_study_guide_audio.html` | Endocrinology | ~33 min |
| `heme_onc_study_guide_audio.html` | Hematology/Oncology | ~37 min |
| `rheumatology_study_guide_audio.html` | Rheumatology | ~35 min |
| `neurology_study_guide_audio.html` | Neurology | ~35 min |
| `nephrology_study_guide_audio.html` | Nephrology | ~62 min |
| `id_study_guide_audio.html` | Infectious Disease | ~59 min |

**Total Audio Content:** ~7 hours

---

## ✨ Features

### 🌙 Dark Mode Optimized
- OLED-friendly dark backgrounds
- Reduced eye strain for night shifts
- High contrast text and accents

### 📱 iPad Optimized
- Touch-friendly tap targets (44px minimum)
- CSS Grid layouts tested on iOS Safari
- Safe area padding for notch/home bar
- Offline-capable (no external dependencies)

### 🔍 Search & Navigation
- Real-time filtering across all entries
- Collapsible sections for quick scanning
- Back-to-top buttons
- Cross-linked references between tools

### 🎯 Board Review Features
- ABIM weight indicators per specialty
- High-yield content boxes
- Clinical vignette examples
- Guideline references (ACC/AHA, IDSA, etc.)

---

## 🚀 Deployment

### GitHub Pages (Recommended)

```bash
# Create repository
git init
git add .
git commit -m "Clinical Reference Suite v1.0"
git remote add origin https://github.com/YOUR_USERNAME/clinical-reference-suite.git
git push -u origin main

# Enable GitHub Pages in repository settings
# Select: main branch, root folder
```

Access at: `https://YOUR_USERNAME.github.io/clinical-reference-suite/`

### Local Use

Simply open `index.html` in any modern browser. All files are self-contained HTML with inline CSS/JS.

---

## 📋 Technical Specifications

- **Format:** Single-file HTML with inline CSS and JavaScript
- **Dependencies:** None (fully self-contained)
- **Browser Support:** Safari (iOS/macOS), Chrome, Firefox, Edge
- **Offline:** Full functionality without internet
- **Storage:** LocalStorage for audio position memory

---

## 🔄 Version History

### BUILD #8 (January 2026)
- Added 9 audio study guide editions (~7 hours content)
- iOS Safari voice selection fix for audio guides
- Renal dosing reference expansion
- Antimicrobial stewardship guide
- Standardized versioning across all 39 files

### BUILD #7
- Drug Reference Guide (500+ medications)
- Drug interactions reference
- Enhanced search functionality

### BUILD #6
- Initial 17 specialty study guides
- Clinical reference tools suite
- Dark mode optimization

---

## 📝 Content Sources

Study materials synthesized from evidence-based sources:
- UpToDate
- Harrison's Principles of Internal Medicine
- NEJM / JAMA reviews
- IDSA Guidelines
- ACC/AHA Guidelines
- ADA Standards of Care
- KDIGO Guidelines
- GOLD Guidelines

---

## ⚠️ Disclaimer

This reference suite is designed for educational purposes and clinical decision support. It is not a substitute for clinical judgment, institutional protocols, or direct patient evaluation. Always verify drug dosing and contraindications with current pharmacy references.

---

## 👨‍⚕️ Author

Developed for Internal Medicine residency training and board preparation.

---

*Last generated: January 2026*
