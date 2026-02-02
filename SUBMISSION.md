# Hash It Out Lab - Submission

**Student Name:** [Your Name Here]  
**Date:** [Submission Date]  
**CSPC 250: Computer Systems Security**

--- 

## Part 1: Understanding Hashes (10 points)

### Exercise 1.1: Create Your First Hash

**1. What is the MD5 hash of your name?**

[3610ef210f037af8190988ff751062a4 ]

**2. Run the command again with the exact same name. Did the hash change? Why or why not?**

[3610ef210f037af8190988ff751062a4 The hash did not change because nothing in my name change.]

**3. Change one letter of your name (like capitalizing it) and run again. How different is the hash?**

[be70c68fb9f47eb9f2f63e2ef32276d1The hash is completely diffenrent now.]

---

### Exercise 1.2: Hash Collisions

**4. What is the md5sum of the file you created?**

[3610ef210f037af8190988ff751062a4]

**5. In your own words, explain what a hash collision is and why it's a security concern.**

[A hash collision is when a hash is the exact samething for 2 things and its a security concern because if you can figure out the hash to one thing you have a high posibility to find others witht he same hash]

---

## Part 2: Password Storage (10 points)

### Exercise 2.1: Examine the Shadow File

**6. Why would a system have users with `*` instead of password hashes?**

[So that all the passwords aren't the same and it will be harder to crack]

**7. What do the different parts of karl's password line mean? (Hint: Research the format of `/etc/shadow` entries)**

[username, Encrypted Password, last password change, Min. password age, max. password age, warning period, inactivity period, expiration date]

---

### Exercise 2.2: Understanding Password Hashing

**8. Why don't systems store passwords in plaintext?**

[Plain text arent safe and easier to hack]

**9. What is a "salt" in password hashing and why is it used?**

[Salt is when you addd random things into the password to completely randomized the hash]

**10. Research the `yescrypt` algorithm (the `$y$` prefix). Why is it considered secure?**

[It is a key derivation function and it it made to defend against cpu attacks by using a lot of memory to help defend against attacking schemes that use  GPUs, FPGAs, and ASICs ]

---

## Part 3: Password Cracking (15 points)

### Exercise 3.1: Crack Karl's Password

**11. What was karl's password?**

[lacrosse..pumpkine]

**12. How long did it take John to crack it?**

[like 3 seconds]

**13. Why was this password easy to crack?**

[Because its not salted]

---

### Exercise 3.2: Verify the Password

**14. Does the hash match? (Yes/No)**

[Your answer here]

**15. What does this tell you about how Linux verifies passwords during login?**

[They are hevily secured]

---

## Part 4: Security Analysis (5 points)

**16. Based on this lab, what makes a password "strong"?**

[Randon symbols or the password being randomized all around]

**17. Why do websites now require passwords with numbers, symbols, and mixed case?**

[It make the encryption harder to crack]

**18. If you were designing a password policy for a company, what rules would you set? (At least 3 specific rules)**

[Atleast 8 characters long, Atleast 2 capital letters, Atleast 2 special character, Atleast 2 numbers]

---

## Screenshots Checklist

Include three screenshots in the `screenshots/` folder:

- [ ] `screenshot1.png` - Your name being hashed (Exercise 1.1)
- [ ] `screenshot2.png` - md5sum of your file (Exercise 1.2)
- [ ] `screenshot3.png` - John the Ripper cracking karl's password (Exercise 3.1)

---

## Reflection (Optional but Recommended)

What was the most interesting thing you learned in this lab?

[How easy important it is to make all passwords somewhat different from eachother and i think its pretty intresting how only 1 thing can be different and the whole encryption will be different.]

---

## Academic Integrity Statement

By submitting this lab, I affirm that:
- I completed this work independently
- I did not copy answers from other students
- I did not use AI tools to generate my responses
- I understand the concepts and can explain them in my own words

**Signature (type your name):** [Jayden Harrington]  
**Date:** [2-1-2026]
