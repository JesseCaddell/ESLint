I started by following the example for the assignment. After answering the questions to the best of my ability I created the .eslintrc file.
I changed the rules to
"semi": ["error", "always"],
"quotes": ["error", "always"]

but was met with an error. Seems that the quotes rule does not take always as a param.
After looking it up I found it takes single, double, or backtick as a param.
Ran it on my dummy file and was impressed with how it caught all of my potential errors.
