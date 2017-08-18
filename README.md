# jobadparser

At [SheCanCode](https://shecancode.io/), we always wonder what is in a job ad in tech. Sure, companies try to describe a role and get people to apply, but what do they really need? And how is the language influencing who applies?

This project aims to understand job ads better in order to get insights as well as providing a way to normalize job ads.

## how it works

As we are very much in the genesis of the project, this section will change in the future, but here is the plan:
1. Compile a list of many tech job ads - for space reasons, these will not live in this repo but rather on an external CDN. If you want to add job ads to the CDN, please contact [alice](mailto:alice@shecancode.io).
2. Write parsers that turn job ads from different formats (PDF, docx, etc.) into normalized plain text
3. Create rules/NLP/ML/\<insert buzzword here\> to try and understand what job ads mean (is a "JS guru" the same thing as a "Front-End Engineer"? What are the skills that everyone wants? Is the language gendered? Can we predict the industry purely from the language? etc.)
4. Compile a list of actionable results and insights from the step above.
5.  Develop a tool that - using step 4 - will take a job ad and return a normalized ad with neutral language and skill list, as well as possible insights from the language.

Wow, that's a lot of work! Well, this is the perfect segue into:

## contributing

This project would not become real if not for the help of milions (one can dream) of contributors.
Some parts are quite straightforward and will be perfect to start on the project, some parts are more fuzzy and we are especially happy to welcome anyone who would like to run some intelligence in our step 3 from the plan above.

I'll try and create issues for any straightforward part, and feel free to create issues for any part you'd like to work on. Or just send your pull requests. All code should ideally be reviewed.
