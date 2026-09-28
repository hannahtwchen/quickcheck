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

My intention was to create a small quiz that separates what students need to see from what teachers need to review. In the student view, a student can focus on answering one question at a time without seeing their score or how long they took. In the teacher view, I wanted to display the quiz data in a simple, clear way: the answer selected, whether it was correct, the accuracy rate, and the response time for each question.

I tested the interaction by choosing both correct and incorrect answers, then switching to the teacher view before and after answering questions. The dashboard was initially empty, but it updated after each answer to show the student’s score and timing information.

AI helped me translate my idea into HTML, CSS, and JavaScript, especially when building the quiz structure and recording the time from when a question appeared until an answer was selected. However, I had to decide which information was most useful for each type of user. For example, I chose to hide timing and scores from students because I wanted the student view to feel less distracting and reduce cognitive load. In contrast, the teacher view focuses on tracking student performance.

I also changed the original design from two separate browser pages to one page with buttons for switching between student and teacher views. This made it easier to test both perspectives during development.

One remaining limitation is that this is only a prototype for one student and one teacher using the same page. A real classroom version would need separate student accounts, a database, and a way for teachers to view the results of multiple students. In addition, I would like to find ways to determine whether a student is guessing rather than carefully considering an answer. In the future, I would like to continue adjusting and polishing the design, adding more features to make it more practical for classroom use.
