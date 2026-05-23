# 🎬 CineVerse Anime Website – Test Report

## 📌 Project Overview
CineVerse Anime is a responsive anime streaming UI project designed to provide users with a smooth browsing experience, including search, filtering, sliders, and anime grid interaction.

This repository contains the **manual and automated QA test results** for the application.

---

## 🧪 Test Summary

- **Project Name:** CineVerse Anime Website  
- **Test Date:** 23.02.2026  
- **Tester:** Ilajda Sejfulla  
- **Version:** 1.0  
- **Total Test Cases:** 138  
- **Success Rate:** 93% (128 Passed / 10 Failed)

---

## 🧩 Test Coverage

### 1. Functional Testing
- Page load & navigation
- Navbar behavior
- Theme toggle (dark/light mode)
- Slider interactions
- Anime grid display
- Card hover/click effects

---

### 2. Search & Filter Testing
- Full and partial search
- Case-insensitive search
- Genre filtering (Action, Romance, Horror, Comedy, Fantasy)
- Combined search + filter
- Empty and invalid search handling

⚠️ **Known Issue:** Genre filter inconsistencies detected

---

### 3. Image Testing
- All anime images load correctly
- No broken images detected
- Correct dimensions maintained (140x160)

---

### 4. Responsive Testing
Tested across:
- iPhone SE / 12 / 14 Pro
- Samsung S21 / Pixel
- iPad Mini / Air / Pro
- Desktop (Chrome, Firefox, Edge)
- 4K displays

✅ Fully responsive layout confirmed

---

### 5. Performance Testing
- Page load: < 3s
- Search response: < 100ms
- Smooth slider transitions
- Memory usage < 100MB
- CPU usage < 10%

---

### 6. Browser Compatibility
Supported browsers:
- Chrome 120+
- Firefox 115+
- Safari 16+
- Edge 120+
- Opera / Brave / Samsung Internet

---

### 7. Edge Case Testing
- Special characters input
- Very long text input
- Rapid clicking & typing
- Offline behavior
- Broken images
- Large dataset handling (100+ anime)

---

## 🤖 Automation Testing

### K6 Performance Testing
- 10 Virtual Users
- ~280 iterations
- Avg response time: ~460ms
- No failed requests

### Selenium UI Testing
| Test ID | Scenario | Result |
|--------|----------|--------|
| SEL-01 | Page title check | PASSED |
| SEL-02 | Login test | PASSED |
| SEL-03 | Genre filter | FAILED |
| SEL-04 | Watchlist add | PASSED |
| SEL-05 | Watchlist remove | PASSED |

---

## 🐞 Bug Report Summary

| Bug ID | Issue | Severity |
|--------|------|----------|
| BUG-01 | Genre filter not working | High |
| BUG-02 | Filter not updating results | Medium |
| BUG-03 | Anime count incorrect | Medium |
| BUG-04 | Multiple genre selection broken | High |

---

## 📊 Final Test Results

| Category | Passed | Failed | Success Rate |
|----------|--------|--------|--------------|
| Functional | 21 | 1 | 95% |
| Search & Filter | 6 | 9 | 40% |
| Images | 72 | 0 | 100% |
| Responsive | 13 | 0 | 100% |
| Performance | 10 | 0 | 100% |
| Compatibility | 7 | 0 | 100% |

---

## ⭐ Final Evaluation

| Criteria | Rating |
|----------|--------|
| Functionality | 5/5 |
| Usability | 5/5 |
| Performance | 5/5 |
| Design | 3/5 |
| Mobile Experience | 4/5 |

---

## 📌 Conclusion

The CineVerse Anime website demonstrates:
- Strong UI/UX design
- Excellent performance
- Good cross-browser compatibility
- Fully responsive layout

### ⚠️ Improvements Needed
- Fix genre filtering system
- Improve filter + search integration
- Ensure correct anime count updates dynamically

---

## 🧪 Testing Strategy

Testing included:
- Manual UI testing
- Functional validation
- Cross-browser testing
- Responsive design testing
- Performance benchmarking
- Automated testing (Selenium + K6)

---

## 🚀 Overall Verdict

> CineVerse Anime is **production-ready in UI/UX and performance**, but requires **bug fixes in filtering logic** before full deployment.

---
