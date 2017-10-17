# jobadparser

At [SheCanCode](https://shecancode.io/), we always wonder what is in a job ad in tech. Sure, companies try to describe a role and get people to apply, but what do they really need? And how is the language influencing who applies?

This project aims to understand job ads better in order to get insights as well as providing a way to normalize job ads.

## The plan

As we are very much in the genesis of the project, this section will change in the future, but here is the plan:

- [x] Compile a list of tech job ads - for space reasons, these do not live in this repo but rather on S3.

[Click here to download the job ad archive](https://s3.eu-west-2.amazonaws.com/jobadparser/jobads.zip).
If you want to add job ads to the CDN, please contact [alice](mailto:alice@shecancode.io).

- [ ] Write parsers that turn job ads from different formats (PDF, docx, etc.) into normalized plain text
- [ ] Create rules/NLP/ML/\<insert buzzword here\> to try and understand what job ads mean (is a "JS guru" the same thing as a "Front-End Engineer"? What are the skills that everyone wants? Is the language gendered? Can we predict the industry purely from the language? etc.)
- [ ] Compile a list of actionable results and insights from the step above.
- [ ]  Develop a tool that - using step 4 - will take a job ad and return a normalized ad with neutral language and skill list, as well as possible insights from the language.

Wow, that's a lot of work! Well, this is the perfect segue into:

## contributing

This project would not become real if not for the help of milions (one can dream) of contributors.
Some parts are quite straightforward and will be perfect to start on the project, some parts are more fuzzy and we are especially happy to welcome anyone who would like to run some intelligence in our step 3 from the plan above.

Feel free to assign yourself any issue tagged [help wanted](https://github.com/SheCanCodeHQ/jobadparser/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) or create issues for any part you'd like to work on.
