# 1stAssignmentJS
১. Variable কি?

Variable হলো একটি কন্টেইনার যা ডাটা সংরক্ষণ করে। এর মাধ্যমে প্রোগ্রামে ডাটা ব্যবহার করা এবং পরিবর্তন করা যায়।


---

২. Variable কিভাবে লিখতে হয়?

Variable ডিক্লেয়ার করতে var, let, বা const কিওয়ার্ড ব্যবহার করা হয়।

let name = "John"; // Example of a variable


---

৩. String type variable কি ও কিভাবে লিখতে হয়?

String হলো টেক্সট ডাটা। এটি ডাবল কোট (" ") বা সিঙ্গেল কোট (' ') এর মধ্যে লিখতে হয়।

let city = "Dhaka"; // String type variable


---

৪. Number type variable কি ও কিভাবে লিখতে হয়?

Number type variable হলো সংখ্যাকে সংরক্ষণ করার জন্য। এটি ডাবল বা সিঙ্গেল কোট ছাড়াই সরাসরি সংখ্যা হিসেবে লেখা হয়।

let age = 25; // Number type variable


---

৫. Boolean type variable কি ও কিভাবে লিখতে হয়?

Boolean type variable এর মান true বা false হয়।

let isStudent = true; // Boolean type variable


---

৬. toUpperCase() & toLowerCase() এর ব্যবহার কিভাবে করতে হয়?

toUpperCase(): String এর সব অক্ষরকে uppercase (বড় হাতের অক্ষর) এ রূপান্তর করে।

toLowerCase(): String এর সব অক্ষরকে lowercase (ছোট হাতের অক্ষর) এ রূপান্তর করে।


let text = "hello world";
console.log(text.toUpperCase()); // HELLO WORLD
console.log(text.toLowerCase()); // hello world


---

৭. JavaScript এর মোট কয়টি অপারেটর আছে ও কি কি?

JavaScript এ ৮ ধরনের অপারেটর আছে:

1. Arithmetic Operators: +, -, *, /, %


2. Assignment Operators: =, +=, -=, *=, /=


3. Comparison Operators: ==, ===, !=, <, >, <=, >=


4. Logical Operators: &&, ||, !


5. Bitwise Operators: &, |, ^, ~, <<, >>, >>>


6. String Operators: +, +=


7. Type Operators: typeof, instanceof


8. Ternary Operator: ? :




---

৮. Math.abs() এর ব্যবহার লিখুন।

Math.abs() একটি সংখ্যার Absolute মান (ধনাত্মক মান) প্রদান করে।

let number = -10;
console.log(Math.abs(number)); // Output: 10


---

৯. Math.ceil() এর ব্যবহার লিখুন।

Math.ceil() দশমিকের উপরের নিকটতম পূর্ণসংখ্যা প্রদান করে।

let number = 4.3;
console.log(Math.ceil(number)); // Output: 5


---

১০. Math.floor() এর ব্যবহার লিখুন।

Math.floor() দশমিকের নিচের নিকটতম পূর্ণসংখ্যা প্রদান করে।

let number = 4.7;
console.log(Math.floor(number)); // Output: 4


---

১১. Math.round() এর ব্যবহার লিখুন।

Math.round() দশমিক সংখ্যাকে নিকটতম পূর্ণসংখ্যায় রাউন্ড করে।

let number = 4.5;
console.log(Math.round(number)); // Output: 5


---

১২. Math.random() এর ব্যবহার লিখুন।

Math.random() ০ এবং ১ এর মধ্যে একটি র‍্যান্ডম সংখ্যা প্রদান করে।

console.log(Math.random()); // Output: e.g., 0.735693


