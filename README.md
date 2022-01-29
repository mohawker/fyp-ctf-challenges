# fyp-ctf-challenges
A series of CTF challenges created to complement Software Security tutorials in university

## Challenges

There are a total of 14 challenges. Of this 14:

- 8 are **Pwn (Binary Exploitation)**
- 4 are **Web**
- 2 are **Miscellaneous**

Challenges are split into three different difficulties: Warmup, Easy and Medium.

> Do take the difficulty levels with _a pinch of salt_, you may find a medium difficulty challenge to be easier than an easy difficulty challenge - They are just general guidelines.

### Pwn (Binary Exploitation)

All challenges are ELF binaries that can be executed on Linux Machines. Challenges touch on fundamental cybersecurity concepts such as buffer overflow, integer overflow and format string vulnerabilities. These challenges have both `static` and `net` implementations, depending on the tutor's preference.

| Difficulty |          Title          |   Challenge Server URL  |                                                                         Description                                                                         |
|:----------:|:-----------------------:|:-----------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Warmup     | Don't Forget the Lyrics | `nc 13.250.39.192 3000` | Rick Astley will never give you up... Can you find a way to not let him down?                                                                               |
| Warmup     | Echo Chamber 1          | `nc 13.250.39.192 3001` | This cave seems to echo back whatever you shout into it. Mysteriously, if you shout in a certain format, the cave echoes back something else ... Spooky.    |
| Easy       | Echo Chamber 2          | `nc 13.250.39.192 3002` | The cave seems alot hollower now. I can't seem to pin-point what is missing though. Maybe you can point it out for me?                                      |
| Medium     | Echo Chamber 3          | `nc 13.250.39.192 3003` | Back to the cave again, but this time, the cave wants some PIE.                                                                                             |
| Easy       | Escape Room 1           | `nc 13.250.39.192 3004` | You're stuck in an Escape Room with no way out! Or is there?                                                                                                |
| Medium     | Escape Room 2           | `nc 13.250.39.192 3005` | You're stuck in an Escape Room with no way out again! Seems like the secret code is 'dead' and 'cafe' ... Not sure how we plan on using these codes though. |
| Easy       | Gotta Catch Them All    | `nc 13.250.39.192 3006` | You've heard of Pikachu, but can you defeat Chikaphu? Just a warning, hitting him with the wrong attacks might heal him.                                    |
| Easy       | Roulette                | `nc 13.250.39.192 3007` | Come try your luck at this new Roulette Table! Can you guess the correct number 7 times in a row?                                                           |                                                     |

### Web

Web challenges only have `net` implementations, and can only be hosted on a challenge server.

| Difficulty | Title         | Challenge Server URL       | Description                                                                                                                  |
|------------|---------------|----------------------------|------------------------------------------------------------------------------------------------------------------------------|
| Warmup     | First Dose    | http://13.250.39.192:5001/ | Vaccines seem to be the talk of the town. Find the correct 'vaccine' and get the flag!                                       |
| Easy       | Second Dose   | http://13.250.39.192:5002/ | Looks like this problem is back for a SeQueL. This time, not all vaccines are effective. Can you find the correct 'vaccine'? |
| Medium     | Booster Dose  | http://13.250.39.192:5000/ | The portal admins claim to have finally fixed their login portal. Find a way to break in!                                    |
| Easy       | Token Machine | http://13.250.39.192:5003/ | This machine seems to produce many different tokens. Can you get the right token?                                            |

### Miscellaneous

Misc challenges only have `static` implementations, and can be distributed to players statically/locally.

| Difficulty | Title         | Description                                                                            |
| ---------- | ------------- | -------------------------------------------------------------------------------------- |
| Warmup     | Metacognition | Learning through lectures is getting boring. How about learning through memes instead? |
| Easy       | Library       | I like big libraries and I cannot lie. Can you find my favourite book?                 |
