# Region Performance Analysis - Superstore

## 📌 Project Overview
Task 18: Compare sales and profit across regions using the Superstore dataset.

---

## 📊 Regional Performance Summary

| Region | Total Sales ($) | Total Profit ($) | Profit Margin (%) | Sales Rank | Profit Rank |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **West** | $725,457.82 | $108,418.45 | 14.94% | 1 | 1 |
| **East** | $678,781.24 | $91,522.78 | 13.48% | 2 | 2 |
| **Central** | $501,239.89 | $39,706.36 | 7.92% | 3 | 4 |
| **South** | $391,721.91 | $46,749.43 | 11.93% | 4 | 3 |

---

## 🔍 Key Insights
1. **West Region** sabse aage hai total sales ($725k) aur net profit ($108k) dono mein.
2. **Central Region** ki sales South se zyada hain, fir bhi profit sabse kam ($39.7k) hai kyunki wahan discounts zyada diye gaye hain.
3. **South Region** ki sales kam hone ke bawajood profit margin (~11.9%) Central se behtar hai.

---

## 💡 Interview Questions & Answers

### Q1: Why compare profit with sales?
- **Answer:** Sirf sales (revenue) dekhne se business ki actual growth ka pata nahi chalta. Agar sales badh rahi hain lekin heavy discount ya high cost ki wajah se profit kam ho raha hai (jaise Central region mein), to business loss mein ja sakta hai. Isliye actual performance janne ke liye sales aur profit dono compare kiye jaate hain.

### Q2: How would you rank regions?
- **Answer:** Regions ko sirf sales par rank karne ke bajaye **Net Profit** aur **Profit Margin %** par rank karna chahiye.
- Overall Ranking:
  1. **West** (Top in Sales & Profit)
  2. **East** (Strong volume and margin)
  3. **South** (Healthy profit margin)
  4. **Central** (Lowest profit margin)
  5. 
