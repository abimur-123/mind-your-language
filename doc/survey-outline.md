### Survey Question:

Does the first programming language someone learns influence whether they prefer R or Python (or have no preference)?

### Main Questions:

What was the first programming language that you learned?
Do you prefer R or Python or No Preference?



Cofounding variable:

- How much do you agree with the statement: "I learned to program because I viewed it as an employable skill?"
  - Some languages are seen as very employable, so if someone viewed it as an employable skill, it will effect both of the first programming language and preference of R or Python.
 
- What is your academic background?  
  - For example, people who has stat or math background are high-frequency users of Matlab or R, but not for C or python. It will also effect both of the first programming language and preference of R or Python.

- How did you learn your first programming language? (Academia/Online/Book)
  - we want to be able to figure out the effect of learning method. Different platform may have different preference for language. For example, python may be more popular in University than online course.
  
- How long ago did you start learning your first programming language?
  -  given how Python and R have gained a lot of traction over the past few years we feel like this could influence the first language leant and the eventual preference

### How to analyze:
We will use logistic regression to control for the confounding variables and predict the probability that a person prefers Python and the probability that a person prefers R. We can look at the coefficient associated with the first programming languages and see if they are non-zero in a statistically significant way.

### Research Ethics Concerns:
link for UBC Office of Research Ethics document on Using Online Surveys https://ethics.research.ubc.ca/sites/ore.ubc.ca/files/documents/Online_Survey-GN.pdf
We will be using Google Forms to conduct the survey, and so the information will be stored in the US. As such, we will not be collecting identifying information and, in particular, e-mails will not be collected when the survey is filled out. We will also be informing survey participants that their survey information will be stored in the US before their participation and as such the information might be subject to retrieval via the Patriot Act. A sample statement is included in the above document.
