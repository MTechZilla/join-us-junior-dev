# Assignment 1

### Build a Pomodro timer app

1. Login user with email and password using google ( you can use firebase authentication or any other authentication).
2. Show 25 minutes of timer where the user can reset, pause and start the timer
3. Show a 5 minutes break timer when the 25 minutes timer gets complete.



# Assingment 2

### Show a card ui with users github public information.


1. Ask for username in form with a single input field of `username`. 
2. When the user submits the username, show a nicely designed card with nicely desinged UI showing users public informations 
- Required public information expected to see on card is given below.

    - Avatar Image ( `avatar_url` )
    - Username  ( `login` )
    - Name  ( `name` )
    - No. of public repos ( `public_repos` )
    - No. of public gists ( `public_gists` )
    - Profile created at in time format of `YYYY-MM-DD`.  ( `created_at` )


The api path to get the public information of Github user is given below

```bash
GET - https://api.github.com/users/{username}
```

---

_Recommended tech stack to be used:_
1. React / Nextjs
2. Chakra UI / Tailwind css
3. Firebase
