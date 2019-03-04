### HooHacks 2019

# Inspiration
Perfect practice makes perfect: Students should be able to receive feedback on the practice they are doing in real times so they are able to correct their strokes for the future.

# What it does
The most convenient and accessible way to teach how to do something is to get students to observe and do it themselves. Using an extended data set, we put together an interface for English learners to practice their letter writing skills. By comparing our students handwriting to other English writers through Optical Character Recognition (OCR), we are able to actively score and guide students.

# How we built it
Front-end was created using HTML/CSS. Backend included several JavaScript functions that perform the linear algebra to conduct client-side binary classification with a confidence score. The support vector classifier was trained on the EMNIST dataset using ScikitLearn Python modules in a Jupyter Notebook running on a Google Cloud compute cluster.

# Challenges we ran into
One problem we faced was not being able to process a very large data set - we solved this with some Google Cloud computing power.

# Accomplishments that we're proud of
Creating a colorful, interactive design that is conducive to young children's learning.

# What we learned
EMNIST is a difficult data set to work with.

# What's next for Support Vector Monsters
We'd like to integrate more features to expand the range of what students can practice. We envision teachers and tutors being able to add word lists to a student's practice queue, and building the word animations out of the character gifs we've already made.
