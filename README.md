# 🌐 Claude in Chrome: الـ AI بقى بينفذ بنفسه مش بس بيقولك تعمل إيه

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20PROMPT-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Prompt على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20SITES%20%C2%B7%20SHEET-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Prompt على طول — املا الخانات والصقه في Claude.</b></p>

زمان كنت بتسأل الـ AI "اعمل ده ازاي؟" فيديك خطوات وانت تمشي وراها واحدة واحدة في المتصفح.
دلوقتي مع **Claude in Chrome** الـ AI بيفتح المواقع ويدوس ويملا الـ Forms بنفسه، وانت بتراجع النتيجة.

هنا هتلاقي **خمس مهام جاهزة** تجربهم بنفسك، وكل مهمة معاها Prompt تنسخه وتغيّر بس الحاجات اللي بين `[ ]`.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: تركّب Claude in Chrome

1. افتح Google Chrome على الكمبيوتر، وركّب إضافة **Claude in Chrome** من الـ Chrome Web Store.
2. سجّل دخول بحساب Claude بتاعك (الإضافة حاليًا Beta ومتاحة على الخطط المدفوعة).
3. افتح الـ Side Panel، واختار نمط الصلاحيات اللي يريحك، وابدأ بمواقع تعرفها وتثق فيها.

للتفاصيل الرسمية:
- https://claude.com/chrome
- https://support.claude.com/en/articles/12012173-getting-started-with-claude-for-chrome

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

كل الـ Prompts تحت بتستخدم نفس الخانات دي، فاملاها مرة واحدة وانسخ على طول.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك | Ahmed Hassan |
| `[CONTENT TYPE]` | نوع شغلك أو المجال بتاعك | متجر إلكتروني للموبايلات |
| `[AUDIENCE]` | جمهورك أو عميلك | شباب 18-30 في مصر |
| `[LANGUAGE]` | لغة الرد | Egyptian Arabic |
| `[PRODUCT NAME]` | المنتج اللي عايز تقارن بيه | Logitech MX Master 3S |
| `[SITE 1]` | الموقع الأول | amazon.eg |
| `[SITE 2]` | الموقع التاني | noon.com |
| `[SITE 3]` | الموقع التالت | jumia.com.eg |
| `[GOOGLE SHEET LINK]` | لينك Google Sheet فاضي تحطله النتيجة | https://docs.google.com/spreadsheets/d/... |
| `[FORM LINK]` | لينك الـ Form اللي بتملاها | https://example.com/monthly-form |
| `[FORM DATA]` | كل المعلومات اللي الـ Form محتاجاها | الاسم: ... / الرقم: ... / الفرع: ... |
| `[TIME PERIOD]` | الفترة الزمنية | آخر 30 يوم |
| `[DASHBOARD LINK]` | لينك لوحة الأرقام اللي بتتابعها | https://analytics.example.com/... |
| `[METRICS]` | الأرقام اللي عايزها | Visitors, Sales, Conversion rate |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل: املا والصق

املا الخانات اللي فوق وانسخ الـ Prompt ده في Claude in Chrome، وهيمشي على المهام الخمسة واحدة واحدة ويستناك بينهم.

```
Here are my details:
- My name: [YOUR NAME]
- My business / niche: [CONTENT TYPE]
- My audience: [AUDIENCE]
- Reply language: [LANGUAGE]
- Product to compare: [PRODUCT NAME]
- Sites: [SITE 1], [SITE 2], [SITE 3]
- Google Sheet: [GOOGLE SHEET LINK]
- Form link: [FORM LINK]
- Form data: [FORM DATA]
- Time period: [TIME PERIOD]
- Dashboard: [DASHBOARD LINK]
- Metrics: [METRICS]

Work through these 5 tasks in order, and stop after each one so I can review before you continue:
1. Compare [PRODUCT NAME] across [SITE 1], [SITE 2], [SITE 3] and put specs, price, shipping date and delivery method in a Google Sheet.
2. Open [FORM LINK], fill every field using [FORM DATA], then stop before submitting and show me what you filled.
3. Find expense receipts in my Gmail for [TIME PERIOD] and list merchant, amount, date and category in the Sheet.
4. Open [DASHBOARD LINK], read [METRICS] for [TIME PERIOD] and add them as a new row in the Sheet.
5. Open [SITE 1], summarize what is new there in [TIME PERIOD] and suggest 5 ideas for [CONTENT TYPE] aimed at [AUDIENCE].

Rules: write everything in [LANGUAGE]. Do NOT buy anything, do NOT enter payment details, do NOT send emails or messages, and do NOT delete anything. If a step involves money or an important decision, stop and ask me first.
```

**بيعمل إيه؟** بيجمّع المهام الخمسة في Prompt واحد، وبيقف بعد كل مهمة عشان تراجع قبل ما يكمّل.

---

## 💬 المهام الخمسة خطوة بخطوة

## 🛒 1. مقارنة منتج في 3 مواقع

استخدمها لما عايز تقارن سعر ومواصفات منتج من غير ما تفتح تابات كتير.

```
Compare [PRODUCT NAME] across these 3 websites: [SITE 1], [SITE 2], [SITE 3].
Open each site one by one, search for the product, and collect: exact model, key specs, price, shipping date, and delivery method.
Then put everything in this Google Sheet: [GOOGLE SHEET LINK], one row per website, with clear column headers.
Reply in [LANGUAGE] with a short summary of which option looks best and why.
Do NOT add anything to cart and do NOT buy. I will make the final decision.
```

**بيعمل إيه؟** بيفتح كل موقع، ويرجعلك بالمواصفات والسعر وميعاد الشحن وطريقة التوصيل في Sheet جاهزة للمقارنة.
**نصيحة:** اتأكد إن الموديل هو نفسه في المواقع التلاتة قبل ما تقارن الأسعار.

---

## 📋 2. ملا Form طويلة بتملاها كل شهر

للـ Forms اللي بتاخد وقت وبتتكرر بنفس المعلومات.

```
Open this form: [FORM LINK].
Fill in every field using only the information below. If a field is not covered by it, leave it empty and tell me.
My name: [YOUR NAME]
Information: [FORM DATA]
When you finish, do NOT press Submit. Stop and show me a list of what you filled in each field, so I can review it and submit myself.
Reply in [LANGUAGE].
```

**بيعمل إيه؟** بيملا الـ Form بالمعلومات اللي إنت اديتهوله ويقف قبل الإرسال عشان تراجع.
**نصيحة:** بعد ما تجرّبه كذا مرة وتطمن، تقدر تحوّل المحادثة لمهمة متكررة كل شهر (شوف قسم الجدولة تحت).

---

## 🧾 3. استخراج المصروفات من الـ Gmail لـ Sheet

```
Open my Gmail and find receipts and payment confirmation emails from [TIME PERIOD].
For each one, extract: merchant, amount, date, and a category (food, transport, software, other).
Add them to this Google Sheet: [GOOGLE SHEET LINK] with clear column headers.
Reply in [LANGUAGE] with the total per category.
Read-only on Gmail: do NOT reply to, forward, archive, or delete any email.
```

**بيعمل إيه؟** بيلم الإيصالات من الـ Inbox ويرتبها في جدول فيه التاجر والمبلغ والتاريخ والتصنيف.
**نصيحة:** راجع المبالغ بنفسك قبل ما تعتمد عليها في أي حساب.

---

## 📊 4. سحب أرقام من لوحة (Dashboard) لـ Sheet

```
Open this dashboard: [DASHBOARD LINK].
Read these numbers for [TIME PERIOD]: [METRICS].
Add them as a new row in this Google Sheet: [GOOGLE SHEET LINK], with today's date in the first column.
Reply in [LANGUAGE] with the numbers and one line on what changed compared to the previous row.
Do NOT change any setting on the dashboard.
```

**بيعمل إيه؟** بيقرا الأرقام من اللوحة وبيضيفها كصف جديد في الـ Sheet عشان تتابع التغيير بمرور الوقت.

---

## 🔍 5. متابعة موقع منافس وأفكار منه

```
Open [SITE 1] and look at what is new there in [TIME PERIOD] (new posts, products, or offers).
Summarize the 5 most important updates in [LANGUAGE].
Then suggest 5 ideas for [CONTENT TYPE] aimed at [AUDIENCE], inspired by what you found.
Add the updates and the ideas to this Google Sheet: [GOOGLE SHEET LINK].
Do NOT contact the website, sign up, or submit any form.
```

**بيعمل إيه؟** بيفتح الموقع ويلخصلك الجديد وبيطلعلك أفكار تقدر تشتغل عليها.

---

## ⏰ بعد ما أي مهمة تنجح: خليها تتكرر لوحدها

لما تلاقي Prompt اشتغل معاك كويس، تقدر تحوّله لمهمة مجدولة (يومي، أسبوعي أو شهري) من قايمة المحادثة في الـ Side Panel لو الخيار ظاهرلك، وبعدها يشتغل من غير ما تفتحه.
شوف الـ Help Center الرسمي عشان تتأكد من الخطوات الحالية: https://support.claude.com/en/collections/18031491-claude-in-chrome

## 🇪🇬 تقدر تكتبله بالمصري كمان

```
افتح [FORM LINK] واملا كل الخانات بالمعلومات اللي تحت بس: [FORM DATA].
لو في خانة مش مغطاها، سيبها فاضية وقولي.
لما تخلص ماتدوسش Submit، وقفلي وورّيني كتبت إيه في كل خانة.
ردّ عليا بالعربي المصري.
```

## ⚠️ نصايح مهمة

- أي حاجة فيها فلوس: **انت اللي تراجعها**. حسب الـ Help Center الرسمي، Claude in Chrome مش بيعمل مشتريات ولا معاملات مالية ولا بيدخل بيانات كروت، فخليه يجمع المعلومات وانت تاخد القرار.
- ابدأ بمواقع تعرفها وتثق فيها، لأن الصفحات ممكن تحط تعليمات مخفية بتحاول تخدع الـ AI (Prompt Injection).
- خليه ما يبعتش رسايل ومايمسحش حاجة، واكتب ده صراحة في الـ Prompt.
- راجع النتيجة بنفسك قبل ما تعتمد عليها، خصوصًا الأرقام والأسعار.
- متستخدمهوش على صفحات فيها بيانات حساسة أو منظمة قانونيًا، وبلّر الأسماء لو بتصور.

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| تفتح 3 مواقع وتنقل الأسعار بإيدك | Claude يفتحهم ويحطهم في Sheet |
| تملا نفس الـ Form كل شهر | Claude يملاها وانت بس تراجع وتبعت |
| تجمع الأرقام من اللوحة يدوي | صف جديد في الـ Sheet بدون مجهود |
| تتفرج على خطوات بتقولك اعمل إيه | AI بينفذ وانت بتتخذ القرار |

---
لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
