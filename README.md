# PersonaScope

**PersonaScope** হলো একটি ওয়েব অ্যাপ যা ব্যবহারকারীর ভিতরের Sigma, Alpha, এবং Beta ব্যক্তিত্বের বৈশিষ্ট্যগুলো আবিষ্কার করতে সাহায্য করে। এই অ্যাপের মাধ্যমে ব্যবহারকারীরা ১০০টি multiple-choice প্রশ্নের উত্তর দিয়ে তাদের ব্যক্তিত্বের ধরণ জানতে পারবে।  

---

## কিভাবে ব্যবহার করবেন

1. **ল্যান্ডিং পেজ (index.html)**  
   - ওয়েবসাইটে প্রবেশ করলে index.html খুলবে।  
   - এখানে অ্যাপের পরিচিতি, নির্দেশনা এবং “শুরু করুন” বোতাম থাকবে।  

2. **প্রশ্নপত্র পেজ (quiz.html)**  
   - “শুরু করুন” চাপলে quiz.html খুলবে।  
   - প্রতিটি প্রশ্নে তিনটি অপশন (A, B, C) থাকবে।  
   - সব প্রশ্নের উত্তর দিয়ে **Submit** চাপলে একটি **JSON ফাইল ডাউনলোড** হবে।  
   - JSON ফাইলটি চাইলে **copy** করে ChatGPT বা অন্য AI তে paste করেও analysis করা যাবে।  
   - ফাইলের মধ্যে merged prompt (reasoning + care + create) সংযুক্ত থাকবে, যা AI কে personality analysis করতে সাহায্য করবে।  

3. **ফলাফল (JSON)**  
   - JSON ফাইল থেকে analysis পাওয়া যাবে, যেখানে প্রতিটি প্রশ্নের উত্তর এবং Sigma, Alpha, Beta traits অনুযায়ী reasoning থাকবে।  

---

## ফিচারসমূহ

- **Simple এবং Lightweight**  
  - HTML, CSS, এবং JS ভিত্তিক।  
  - কোনো backend বা server এর প্রয়োজন নেই।  

- **Portable**  
  - GitHub Pages এ ফ্রি হোস্ট করা যায়।  
  - যেকোনো ব্রাউজারে কাজ করে।  

- **Future Ready**  
  - পরবর্তীতে AI integration যোগ করা যাবে।  
  - Auto-analysis এর জন্য API ব্যবহার করা যাবে।  

- **User-friendly**  
  - সহজ ও সুন্দর UI।  
  - Landing page এ নির্দেশনা এবং বোঝানোর জন্য লেখা।  

---

## ফাইল স্ট্রাকচার

PersonaScope/
│
├── index.html # Landing page
├── quiz.html # Quiz page
└── README.md # এই ফাইল  


---

## লাইভ ডেমো
[PersonaScope Live](https://susmito-d.github.io/PersonaScope/)  

---

## কপিরাইট ও ক্রেডিট
© 2025 **Susmito Datta**  
- তৈরি করেছেন Susmito Datta  
- সকল ব্যবহারকারীকে স্বাগতম, এই অ্যাপ শুধুমাত্র শিক্ষামূলক ও বিনোদনের জন্য।  

---

## ভবিষ্যতের পরিকল্পনা
- AI API integration (OpenAI / Claude / Gemini)  
- ব্যবহারকারীর JSON ফাইল থেকে সরাসরি বিশ্লেষণ প্রদর্শন  
- নতুন UI / মোবাইল ফ্রেন্ডলি ডিজাইন
