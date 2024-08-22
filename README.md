# MachineLearning
autograding of algebraic using mathbert embedidngs and analysing through ML models
Autograding offers significant advantages for teachers and
students alike. Marking work by hand is subject to time
constraints and also to errors which hinders the fairness of
evaluation. It ensures fairness by providing consistent and
unbiased evaluation across all student submissions, addressing
a common issue where some teachers award full marks only
for correct final answers, overlooking partial correctness and
the problem-solving process. Autograding models can assign
marks for partially correct solutions, thereby recognizing
students understanding and effort even when the final answer
is incorrect. This approach not only enhances the fairness of
grading but also reduces the workload on teachers, freeing
up valuable time that can be used towards personalized
instruction and other educational activities. Consequently, the
integration of autograding systems in educational settings
fosters a more equitable and efficient learning environment.


Autograding is beneficial for algebraic questions due to the
structured and logical nature of algebra. Algebraic problems
often have well-defined steps and intermediate solutions that
can be systematically evaluated. Traditional manual grading
can be subjective, especially when it comes in giving partial
marks for intermediate steps. This not only ensures fairer
grading but also helps students understand their mistakes
and learn more effectively. Additionally, algebra forms the
foundation for many advanced topics in mathematics and
science, making accurate and consistent grading crucial for
building a solid understanding of these subjects.


The project employing machine learning techniques
aims to develop a dependable system for autograding
algebraic questions. The model has been explored with
different types of algebraic questions using MathBERT.
Our methodology encompasses several essential stages:
pre-processing, embedding and feature extraction, clustering
and dimensionality reduction, similarity computation, and
validation using performance metrics. The process of data
preparation consisted of assembling training datasets in
mathematical format and in LaTeX format and providing with
correctness labels for each answer. MathBERT embeddings
converted these text-based answers into high-dimensional
numerical arrays, which allowed to include semantic details
of the mathematical hints. t-SNE was as a tool for
dimensionality reduction, thereby getting retained the locally
structured data, and K-means cluster was utilized for forming
the data based on questions and correctness label. The cosine
similarity analysis function was used to make comparisons
between student answers and key solutions by dividing them
into correct, partially correct and incorrect sets based on
specific levels of similarity.



The research primarily answers the following questions:
RQ1: Can cluster based classification helps in grading the
mathematical responses more accurately when compared
to the rule based approach?
RQ2: How well does MathBERT trained on Latex codes
understand the semantics of mathematical expressions?
