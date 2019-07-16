# FriendFinder

![Friend](https://puu.sh/DwITv/1b6f2edd67.png)

### Overview

A compatibility-based "FriendFinder" application. This full-stack site will take in results from your users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.

Express is used to handle routing.

### How to use

1. The User answers 10 survey questions to pinpoint your personality. Each of the answers are on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

2. Click submit when all the questions are anserwed. (Note: You will prompt to answer all if not achieved when you click submit)

3. A modal popup will appear with a matching friend along with a picture. Click close to exit the modal.

4. Page will reload with that all the answers reset for the user to find a different friend.

### Folder Structure
  ```
  FriendFinder
    - .gitignore
    - app
      - data
        - friends.js
      - public
        - home.html
        - survey.html
      - routing
        - apiRoutes.js
        - htmlRoutes.js
    - node_modules
    - package.json
    - server.js
  ```


### Submission
Live site: https://pacific-retreat-41533.herokuapp.com/

