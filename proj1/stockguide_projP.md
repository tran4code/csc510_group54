# Stock Exchange Prediction using Machine Learning [(Project P)](https://github.com/lokesh45/StockPrediction)
## Grading Rubric

Prepare a markdown table with **three** columns:

- Column1 has all the following points PLUS all the points from the
  [Software Sustainability Evaluation](https://docs.google.com/forms/d/e/1FAIpQLSf0ccsVdN-nXJCHLluJ-hANZlp8rDKgprJa0oTYiLZSDxh3DA/viewform).
- Column2 is your self-assessment. For each items, score yourself zero (none), one (a litte), two (somewhat), three (a lot).
- Column3 is for any links you  are adding to support your claim in column two.
- At the top, show the sum of column2

|Notes|Score|Evidence|
|-----|------|---------|
| Docs: doco generated, format not ugly                                                                                                                                                                                       | 3      | Repo has a readme.md file<br />https://github.com/lokesh45/StockPrediction#readme<br />Also a wiki page <br />https://github.com/lokesh45/StockPrediction/wiki> |
| Docs: what: point descriptions of each class/function (in isolation)                                                                                                                                                        | 0      | doesn't have this documentation                                                                                                                                            |
| Docs: how: for common use cases X,Y,Z mini-tutorials showing worked examples on how to do X,Y,Z                                                                                                                             | 0      | None                                                                                                                                                                       |
| Docs: why: docs tell a story, motivate the whole thing, deliver a punchline that makes you want to rush out and use the thing                                                                                               | 2      | In the introductory video and readme.md file they explain about the product. but its not convincing enough                                                                 |
| Docs: short video, animated, hosted on your repo. That convinces people why they want to work on your code.                                                                                                                 | 2      | There is a video but its not of good quality. https://youtu.be/7ZUhyTCfLUM.                                                                                                |
| Use of version control tools                                                                                                                                                                                                | 3      | They have used Git https://github.com/lokesh45/StockPrediction                                                                                                           |
| Use of style checkers                                                                                                                                                                                                       | 3      | Flake 8 and Pylint                                                                                                                                                         |
| Use of code formatters.                                                                                                                                                                                                     | 3      | Black and Prettier                                                                                                                                                         |
|Use of syntax checkers. |0||
|Use of code coverage |0||
|Other automated analysis tools|0||
|Test cases exist|0|dozens of tests and those test cases are more than 30% of the code base: code coverage is not reported and tests under test directory do not seems sufficient |
|Test cases are routinely executed|0|E.g. travis-com.com or github actions or something|
|The files CONTRIBUTING.md lists coding standards and lots of tips on how to extend the system without screwing things up|0||
|Issues are discussed before they are closed, even if you discuss in slack, need a sumamry statement here|1| For some yes, and for some no.
|Chat channel: exists|0|Link or screenshots: Not available|
|**Online form evaluation**||
|Q5 - How you support your software                                                                                                                                                                                          |        |                                                                                                                                                                            |
| Question 5.1: Does your software describe how a user can get help with using your software?                                                                                                                                 | No     | They don't have a contact me part                                                                                                                                          |
| Question 5.2: Does your website and documentation describe what support, if any, you provide to users and developers?                                                                                                       | No     | They don't have a contact me part                                                                                                                                          |
| Question 5.3: Does your project have an e-mail address or forum that is solely for supporting users?                                                                                                                        | No     | They don't have contact email.                                                                                                                                             |
| Question 5.4: Are e-mails to your support e-mail address received by more than one person?                                                                                                                                  | No     | They didn't provide email addresses.                                                                                                                                       |
| Question 5.5: Does your project have a ticketing system to manage bug reports and feature requests?                                                                                                                         | No     | They don't have.                                                                                                                                                           |
| Question 5.6: Is your project's ticketing system publicly visible to your users, so they can view bug reports and feature requests?                                                                                         | N/A    |                                                                                                                                                                            |
| Question 6.1: Is your software's architecture and design modular?                                                                                                                                                           | Yes    | Visible in code                                                                                                                                                            |
| Question 6.2: Does your software use an accepted coding standard or convention?                                                                                                                                             | Yes    | Their code adheres to python PEP standards, using pylint in their travis.yml file                                                                                          |
| Q7 - Open standards and your software                                                                                                                                                                                       |        |                                                                                                                                                                            |
| Question 7.1: Does your software allow data to be imported and exported using open data formats? e.g. GIF, SVG, HTML, XML, tar, zip, CSV, JSON, NetCDF, or domain specific ones                                             | Yes    | Allows to be exported to .html                                                                                                                                             |
| Question 7.2: Does your software allow communications using open communications protocols? e.g. HTTP, FTP, XMPP, SOAP over HTTP, or domain-specific ones                                                                    | Yes    | with google over HTTP                                                                                                                                                      |
| Q8 - Your software's portability                                                                                                                                                                                            |        |                                                                                                                                                                            |
| Question 8.1: Is your software cross-platform compatible? *e.g. does it run under two or more of Windows, Unix/Linux and Mac OS X, or can be used from within two or more of Internet Explorer, Chrome, Firefox and Safari? | Yes    | Available on Mac/ windows                                                                                                                                                  ||
|Question 9.1: Does your software adhere to appropriate accessibility conventions or standards?|No||
|Question 9.2: Does your documentation adhere to appropriate accessibility conventions or standards?|No||
|Question 10.2: Is each source code release a snapshot of the repository?|Yes||
|Question 10.3: Are releases tagged in the repository?|Yes||
|Question 10.4: Is there a branch of the repository that is always stable? (i.e. tests always pass, code always builds successfully)|N/A||
|Question 10.5: Do you back-up your repository?|N/A||
|Question 11.1: Do you provide publicly-available instructions for building your software from the source code?|Yes||
|Question 11.2: Can you build, or package, your software using an automated tool?|Yes||
|Question 11.3: Do you provide publicly-available instructions for deploying your software?|Yes||
|Question 11.4: Does your documentation list all third-party dependencies?|No||
|Question 11.5: Does your documentation list the version number for all third-party dependencies?|No||
|Question 11.6: Does your software list the web address, and licences for all third-party dependencies and say whether the dependencies are mandatory or optional?|No||
|Question 11.8: Do you have tests that can be run after your software has been built or deployed to show whether the build or deployment has been successful?|Yes||
|Question 12.1: Do you have an automated test suite for your software?|N/A||
|Question 12.2: Do you have a framework to periodically (e.g. nightly) run your tests on the latest version of the source code?|N/A||
|Question 12.3: Do you use continuous integration, automatically running tests whenever changes are made to your source code?|N/A||
|Question 12.4: Are your test results publicly visible?|No||
|Question 12.5: Are all manually-run tests documented?|No||
