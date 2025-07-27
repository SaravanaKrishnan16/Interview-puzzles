\# 💧 Day 1 Puzzle | Measure 4 Litres with 3L and 5L Bottles



\## 🧠 Puzzle Statement



You have two bottles:

\- One that can hold exactly \*\*3 liters\*\* of water.

\- Another that can hold exactly \*\*5 liters\*\* of water.



Your goal is to measure out \*\*precisely 4 liters\*\* of water using only these two bottles.  

You are allowed to:

\- Fill either of the bottles fully.

\- Empty either bottle.

\- Pour water from one bottle to the other until one is either full or empty.



> ❌ No additional measuring tools or markings allowed.



---



\## 📸 Puzzle Illustration



!\[Puzzle Setup](./water-measure-main)



---



\## ✅ Solution



This puzzle can be solved using \*\*two approaches\*\*. Both lead to exactly 4 liters in one of the bottles.



---



\### 🔁 Approach 1 (6 Steps - Optimal)



!\[Approach 1 Steps 1-3](./water-measure-1)  

!\[Approach 1 Steps 4-6](./water-measure-2)



1\. Fill the 5-liter bottle. (5, 0)

2\. Pour into the 3-liter bottle. (2, 3)

3\. Empty the 3-liter bottle. (2, 0)

4\. Pour remaining 2L from 5L to 3L. (0, 2)

5\. Fill 5-liter bottle again. (5, 2)

6\. Pour into the 3-liter bottle (needs 1L), leaving \*\*4 liters\*\* in the 5-liter bottle. ✅  

&nbsp;  Final state: \*\*(4, 3)\*\*



---



\### 🔁 Approach 2 (8 Steps)



!\[Approach 2 Steps 1-3](./water-measure-2-1)

!\[Approach 2 Steps 4-6](./water-measure-2-2)



1\. Fill 3-liter bottle. (0, 3)

2\. Pour into 5-liter bottle. (3, 0)

3\. Fill 3-liter again. (3, 3)

4\. Pour into 5-liter (now 5L full, 1L left in 3L). (5, 1)

5\. Empty 5-liter bottle. (0, 1)

6\. Pour 1L from 3L to 5L. (1, 0)

7\. Fill 3-liter again. (1, 3)

8\. Pour into 5-liter.  

&nbsp;  Final state: \*\*(4, 0)\*\* ✅



---



\## 🗂️ Images in this folder



\- `water-measure-main.webp` → Puzzle layout

\- `water-measure-1.webp` → Steps 1-3 of Approach 1

\- `water-measure-2.webp` → Steps 4-6 of Approach 1

\- `water-measure-2-1.webp` → All steps of Approach 2



---



\## 🧠 Conclusion



This classic water jug problem is a favorite in interviews to test logical reasoning, sequencing, and minimal-step problem solving.



---



✅ Stay tuned for \*\*Day 2 Puzzle\*\* tomorrow!



