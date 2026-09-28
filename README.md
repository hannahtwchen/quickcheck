### Live Project:
https://hannahtwchen.github.io/quickcheck/
### GitHub Repository: 
https://github.com/hannahtwchen/quickcheck

# Quick Check

A small browser-based quiz prototype for a classroom. The Student and Teacher buttons in the top-right of `index.html` switch between identities at any time. The student view hides time and score; the teacher dashboard tracks the student's score, correct rate, selected answers, and time per question after every answer.

## Main Idea

My idea was to create a quick quiz using HTML, CSS, and JavaScript. Students answer some questions and receive immediate feedback, while teachers can track their learning progress through the results. 

To help teachers better understand learners' performance, I asked Codex to collect useful data, including the accuracy rate, average response time, and total completion time. This information can help teachers identify which topics students understand well and which areas may need additional support.

## Run it

Open `index.html` in any modern browser. Use the Student and Teacher buttons in the top-right to switch views. No installation or server is required.

## Reflection

My intention was to make a simple quiz where the student has a focused experience while a teacher can review useful information separately. The finished prototype matches that goal: the student sees questions one at a time without seeing their response time, while the teacher can switch to a dashboard at any time to see correctness, correct rate, and time per question. I tested the full sequence by choosing both correct and incorrect answers, switching views between questions, and checking that the teacher dashboard updated after each answer.

AI helped turn the idea into the initial HTML, CSS, and JavaScript structure, but I made the important design decisions: using only three questions to keep the test manageable, defining response time as the time from a question appearing until an answer is clicked, and keeping timing data out of the student view. One unresolved limitation is that this is a local prototype: it represents one student and one teacher using the same page. A future version would need accounts and a database to support a real classroom with multiple devices.
