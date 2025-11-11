# 🐾 JPetStore – פרויקט בדיקות ידניות (Manual QA Project)
**מסמכי בדיקות תוכנה מלאים למערכת JPetStore**

Repository זה כולל את כל תיעוד הבדיקות הידניות שבוצעו על אתר ההדגמה JPetStore.  
הפרויקט נבנה כחלק מקורס מקצועי בבדיקות תוכנה ומציג את מחזור חיי הבדיקות המלא –  
מתכנון ובניית תרחישי בדיקה ועד הפקת דו"חות סיכום וניתוח באגים.

---

## 📋 סקירת הפרויקט / Project Overview
**מערכת נבדקת / System under test:** JPetStore Demo Website  
**סוג הבדיקות / Testing type:** Manual Functional & GUI Testing  
**מספר מקרי בדיקה / Number of Test Cases:** 245  

**סביבות שנבדקו / Environments tested:**  
- Environment 1: Windows 11 – Firefox / Edge / Chrome  
- Environment 2: iOS / Android  
- Environment 3: (in progress)

---

## 👥 צוות הבדיקות / QA Team
| שם | תפקיד | Role |
|------|----------|------|
| **מירב לנקרי** | מנהלת בדיקות | Test Lead |
| **אסתי** | בודקת פונקציונלית | QA Tester |
| **משה** | בודק פונקציונלי | QA Tester |

---

## 🧪 מסמכי הבדיקות / Testing Artifacts
- 📘 **STP** – תכנית בדיקות מערכת (Software Test Plan)  
- 📗 **STD** – עיצוב מקרי בדיקה (Test Design Document)  
- 📙 **STR** – דו"ח סיכום בדיקות (Test Summary Report)  
- 📒 **RTM** – מטריצת עקיבות דרישות (Requirement Traceability Matrix)  
- 📔 **Use Cases** – תרחישי שימוש מפורטים (Detailed User Scenarios)  
- 🐞 **Bug Report** – דו"ח באגים מפורט (Detailed Bug Log)

🎥 **סרטוני ההרצות ודוגמאות לתקלות זמינים ב-OneDrive:**  
👉 [לחצי כאן לצפייה / Click here to view videos](YOUR_ONEDRIVE_LINK_HERE)

---

## 📈 תוצאות הבדיקות / Summary Results
| סביבה / Environment | מקרי בדיקה שהורצו | עברו / Passed | נכשלו / Failed | אחוז הצלחה / Success Rate |
|----------------------|-------------------|----------------|----------------|----------------------------|
| Environment 1 | 218 | 150 | 68 | 68.8% |
| Environment 2 | 196 | 113 | 83 | 57.6% |

---

## 🧩 טכניקות בדיקה / Techniques Used
- מחלקות שקילות (Equivalence Partitioning)  
- ניתוח ערכי גבול (Boundary Value Analysis)  
- טבלת החלטות (Decision Tables)  
- החלפת מצבים (State Transition Testing)

---

## 🏁 מסקנות / Conclusion
רוב הפונקציות הקריטיות עברו בהצלחה.  
כשלים עיקריים נמצאו במודולי ניווט הקטגוריות, עדכון סל הקניות וולידציות בממשק הניהול.  
המערכת **יציבה ומוכנה לסבב רגרסיה נוסף** לאחר תיקון הבאגים.

Most core functionalities passed successfully.  
Main defects were found in category navigation, cart updates, and admin validation screens.  
The system is **stable for further regression testing** after fixes.

---

## 🔗 מסמכים קשורים / Related Documents
- [STP_JPetStore_Full.docx](./STP_JPetStore_Full.docx)  
- [STD_JPetStore.xlsx](./STD_JPetStore.xlsx)  
- [STR_JPetStore.docx](./STR_JPetStore.docx)  
- [RTM_JPetStore.xlsx](./RTM_JPetStore.xlsx)

---

> © 2025 QA Manual Testing Project – Created by Merav Lankri | נכתב ע"י מירב לנקרי  
> קורס בדיקות תוכנה ידניות | Manual Software Testing Course
