

---
#### 7) Create a README file to answer the following questions-

> **⚠️ Warning:** Do not use any AI tools to answer these questions. You must write the answers in **Bangla**.

#### 1) What is the difference between `null` and `undefined`?
    undefined
* যখন কোনো ভ্যারিয়েবল ঘোষণা করা হয়েছে কিন্তু মান দেওয়া হয়নি, তখন তার মান হয় undefined।
* এটি JavaScript নিজে থেকে সেট করে।

    null
* এটি একটি ইচ্ছাকৃতভাবে দেওয়া মান।
* ডেভেলপার নিজে থেকে সেট করে বোঝাতে যে এখানে “কোনো মান নেই”।

#### 2) What is the use of the `map()` function in JavaScript? How is it different from `forEach()`?
    map()
* একটি নতুন অ্যারে তৈরি করে।
* প্রতিটি উপাদানের উপর অপারেশন চালিয়ে পরিবর্তিত মান রিটার্ন করে।

    forEach()
* শুধু প্রতিটি উপাদানের উপর কাজ করে।
* কিছু রিটার্ন করে না (undefined রিটার্ন করে)।
* নতুন অ্যারে তৈরি করে না।

#### 3) What is the difference between `==` and `===`?
    == (Loose Equality)
* টাইপ কনভার্সন করে তারপর তুলনা করে।

    === (Strict Equality)
* টাইপ কনভার্সন করে না।
* মান ও টাইপ দুটোই মিলতে হবে।

#### 4) What is the significance of `async`/`await` in fetching API data?
* API কল সহজ ও পরিষ্কারভাবে লেখার জন্য ব্যবহার হয়।
* Promise handling সহজ করে।
* try...catch দিয়ে error ধরতে সুবিধা।

#### 5) Explain the concept of Scope in JavaScript (Global, Function, Block).

* Global Scope

ফাংশনের বাইরে ডিক্লেয়ার করলে
সব জায়গা থেকে অ্যাক্সেসযোগ্য

* Function Scope

ফাংশনের ভিতরে ডিক্লেয়ার করলে
শুধু ওই ফাংশনের ভিতরে কাজ করে

* Block Scope

{} এর ভিতরে let / const ব্যবহার করলে
শুধু ওই ব্লকের ভিতরে কাজ করে