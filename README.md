# VocabularyReviewerApp
Github page: https://oumalicious.github.io/VocabularyReviewer/

A browser app with a 3-way column matching score system, built to practice memorizing languages that use characters.
As a Chinese Asian American, I'm embarrassed to call myself Chinese when I know very little of my language. I only speak it at home or amongst friends. I have good fundamentals in tones and sentence structure, but my weakness lie in vocabulary. I remember going to Saturday school to learn Chinese, reading paragraphs of characters with perfect eunciation, but I had know idea what I was saying. I studied for tests because I had the mindset of "grades are important because it's a reflection of how smart you are." With this app that was initially built on a whim, I can slowly learn more vocabulary at my own pace and occasionally review myself. This current iteration of the app is for learning foreign languages. While it can be used in a more general sense or use more layers, I want this app to be unique and not be the solver of all problems (yet).

There are 3 unique assets of this app: double layered multiple choice, retesting wrong characters/question, and portability. The point of studying is to learn something new. Take one test to eliminate the words that already known, then start working from there.

# Double layered
There are 3 things to learning a foreign language: the foreign word(s) itself, its pronounciation, and its translaion the native tongue. For some, studying can be very difficult. One may need to dig their eyes into papers, create index cards, or use a 3rd party platform like Quizlet. However there are numerous factors and obstacles that make these methods impratically. Words on a paper are static, so its possible that the order of the words influence this "act of memorization". There are three sides to learning a new languages, so index cards would have to fit an extra layer of information. Quizlet is a great platform, but it doesn't have a function to retest the questions that were incorrect. How can it filter the 45 words that you don't know from a 200 word bank?

# Retesting
No punishments or downsides are the beauty of this app. Students are always asking for a practice test because it's a convenient and easy way to "study". With this app, you can create your own tests and strictly focus on the things you don't know. There are options to add a test timer and question timer. The test will automatically end if the user exceeds the inputted test timer. The question timer is a goal for the user. Some questions make take less than 2 seconds, but what if some take more than 10? Color changes in the results screen indicate how well the user did score and time wise. There is even a rapid test function, where the question will automatically skip if the user doesn't answer within the question timer limit.

# Portability
This is a HTML file. A single file. It doesn't need any .dll or packages to run. It's less than 100kb. You can store the test banks anywhere. You can also test multiple banks at the same time. However, the name of the JSON files (word banks) are important. Because the program looks for multiple files, the current iteration of the program will break if the JSON files are renamed. This problem is very rare and occurs when people have extra files around or want to rename test files. If the latter occurs, the JSON object can be editted in a code editor or by reimporting it into the app, then changing the title.
