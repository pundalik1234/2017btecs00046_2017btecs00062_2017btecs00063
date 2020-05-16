# Dip1
dipproject
What is Optical Mark Recognition (OMR)?

Optical Mark Recognition, or OMR for short, is the process of automatically analyzing human-marked documents and interpreting their results.

Arguably, the most famous, easily recognizable form of OMR are bubble sheet multiple choice tests, not unlike the ones you took in elementary school, middle school, or even high school.

If you’re unfamiliar with “bubble sheet tests” or the trademark/corporate name of “Scantron tests”, they are simply multiple-choice tests that you take as a student. Each question on the exam is a multiple choice — and you use a #2 pencil to mark the “bubble” that corresponds to the correct answer.

The most notable bubble sheet test you experienced (at least in the United States) were taking the SATs during high school, prior to filling out college admission applications.

I believe that the SATs use the software provided by Scantron to perform OMR and grade student exams, but I could easily be wrong there. I only make note of this because Scantron is used in over 98% of all US school districts.

In short, what I’m trying to say is that there is a massive market for Optical Mark Recognition and the ability to grade and interpret human-marked forms and exams.

implementation:
  bubble sheet scanner and grader using OMR, 
  Python, and 
  OpenCV
  
 Steps:-
 To accomplish this, our implementation will need to satisfy the following 7 steps:

Step #1: Detect the exam in an image.

Step #2: Apply a perspective transform to extract the top-down, birds-eye-view of the exam.

Step #3: Extract the set of bubbles (i.e., the possible answer choices) from the perspective transformed exam.

Step #4: Sort the questions/bubbles into rows.

Step #5: Determine the marked (i.e., “bubbled in”) answer for each row.

Step #6: Lookup the correct answer in our answer key to determine if the user was correct in their choice.

Step #7: Repeat for all questions in the exam.


to run the file 
  Make sure you install NumPy and SciPy:

$ pip install numpy
$ pip install scipy

and other required files depending on version of python you have.
