# 📱 KSP Mobile App Manual QA Testing

This project presents a comprehensive **Manual QA Test Report (STR)** for the **KSP Mobile App**, one of Israel's largest electronics retailers. The test plan was designed and executed in May 2025, with a detailed analysis of the app’s features, UI/UX, bugs, and overall usability on mobile (iPhone 11, iOS 18.4.1).

## 🧪 Project Overview

- **Test Type:** Manual QA Testing
- **Platform Tested:** KSP Mobile App
- **Tested Device:** iPhone 11 (iOS 18.4.1)
- **Testing Date:** May 2025
- **Reported By:** Husein Aljohary
- **Test Environment URL:** [ksp.co.il](https://ksp.co.il/web/)

## 🎯 Objectives

- Verify functionality of key app features (search, cart, registration, checkout).
- Assess UI/UX quality and design consistency.
- Test language localization (Hebrew/English/Arabic).
- Identify critical bugs before production release.
- Provide actionable recommendations to improve quality and accessibility.

## 🔍 Scope of Testing

- Homepage navigation & layout
- Product search & filtering
- Cart operations
- User registration/login
- Checkout flow
- UI/UX elements and accessibility
- Language switching
- Mobile responsiveness
- Input validations & error handling

## 🧰 Tools Used

| Tool     | Purpose                      |
|----------|------------------------------|
| **TestRail** | Test case management         |
| **Jira**     | Bug tracking & reporting     |

## 📊 Metrics

- ✅ Total Test Cases: *Executed and tracked*
- 🐞 Total Bugs Found: **36**
  - High Priority: 18
  - Medium Priority: 13
  - Low Priority: 5

## 🐛 Sample Bugs Reported

| Bug ID | Title                                              | Priority |
|--------|----------------------------------------------------|----------|
| KSP-1  | Slow loading home page                             | Low      |
| KSP-10 | First name field accepts numbers                   | High     |
| KSP-15 | App lacks accessibility support                    | Medium   |
| KSP-19 | Registration page not translated to English        | Medium   |
| KSP-28 | Scroll-to-top arrow causes incomplete UI refresh   | High     |

Full list of 36 bugs is available in the STR PDF and on Jira.

## ✅ Exit Criteria

- All core features tested
- All bugs documented on Jira
- No blocking issues remain
- Localization issues identified
- Non-functional issues like performance noted

## 📌 Recommendations

- Fix high-severity bugs before production
- Improve multilingual UI consistency
- Add accessibility features
- Optimize homepage performance
- Ensure back navigation works consistently
- Enhance error messages and field validations

## 📄 Files

- [`STR.pdf`](./STR.pdf): Full test strategy report with test cases and bug documentation.

## 🌐 Links

- 🔗 [Jira Bug Reports](https://husein390.atlassian.net/browse/KSP-1)
- 🔗 [Live Site](https://ksp.co.il/web/)

---

> This project demonstrates strong QA analysis and manual testing skills, focusing on user experience, accessibility, and multi-language behavior. A great example of real-world mobile testing with thorough bug tracking and clear documentation.
