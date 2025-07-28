# Question-Generator-Using-Gen-AI
**# 🧠 Text-to-MCQ Generator

Automatically generate multiple-choice questions (MCQs) from educational text using NLP and generative AI. This project combines question generation with answer extraction and distractor generation to create quiz-style assessments directly from a paragraph of content.

---

## 📌 Features

-  Accepts **any educational paragraph** as input
-  Automatically extracts **answer keywords**
-  Generates **relevant questions** using a fine-tuned T5 model
-  Produces **multiple-choice options** with distractors using KeyBERT
-  Prints the final MCQs with the correct answer

---

##  Demo Output

**Input:**
> "Node.js operates on a single thread, using non-blocking I/O calls, allowing it to support tens of thousands of concurrent connections without incurring the cost of thread context switching. It uses asynchronous programming. A common task for a web server can be to open a file on the server and return the content to the client but servers should not be used for simple tasks when you can get them done without the help of servers. 

📚 Generated MCQs:"

Q: How does Node.js operate on a single thread?
A. uses asynchronous
B. client servers
C. web server
D. node js
✅ Answer: D. node js

Q: What type of programming does Node.js use?
A. uses asynchronous
B. web server
C. client servers
D. node js
✅ Answer: A. uses asynchronous

Q: How does Node.js operate on a single thread?
A. node js
B. uses asynchronous
C. web server
D. client servers
✅ Answer: D. client servers

Q: What is a common task for?
A. node js
B. client servers
C. uses asynchronous
D. web server
✅ Answer: D. web server

Q: What does node operate on a single thread?
A. uses asynchronous
B. client servers
C. node js
D. js operates
✅ Answer: D. js operates
**
