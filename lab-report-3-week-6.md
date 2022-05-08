# CSE15L Lab Report 3 | Week 6

```
Written and Submitted by: Billy Phan
```

> **Task 1: Streamlining SSH Configuration**

![Adding to .ssh/config](cse15l-lab-report-3-ss1.png)

* I first accessed my `ssh/config` file through `nano`.

![Adding a host](cse15l-lab-report-3-ss2.png)

* From there I added a host to be able to log into my ieng6 account with a simple alias `(bphan)`.

![Logging in easy](cse15l-lab-report-3-ss3.png)

* As you can see above I was able to log into my remote host through an alias instead of having to type out the whole email. 

![Scping with an Alias](cse15l-lab-report-3-ss4.png)

* I was then able to `scp` a file over using my alias instead of the email.

---

> **Task 2: Setting up Github Access from ieng6 acocunt**

![Stored public key github](cse15l-lab-report-3-ss5.png)

* Here you can see where I have my `public keys` stored on my github account.

![Stored public and private key local](cse15l-lab-report-3-ss5-ss6.png)

* Here you can see where I have my **public and private keys** stored on my remote account.
* To specificy: I am in my remote account and in the `.ssh` directory.

![Creating a file to push through remote](cse15l-lab-report-3-ss7.png)

* This is a file that I created from my ieng6 account.
* What you should be paying attention to is the bottom lines that i've edited to show that I could commit from the linux remote system
* Since this was not my first attempt, I've simply edited the file instead of adding more lines.

![Showing the git commands I used](cse15l-lab-report-3-ss8.png)

* I used `git add [filename]`, `git commit -m "[message]"`, and `git push origin main` to get my file from the remote host to the repository.

[Link to commit for proof](https://github.com/b-ianphan/cse15l-lab-reports/commit/1bf2ff520d75c605b21d1d7e102f9aeaed45ce00)

> **Task 3: Copying whole directories with `scp -r`**

![Copying directory 1](cse15l-lab-report-3-ss9.png)
![Copying directory 2](cse15l-lab-report-3-ss10.png)
![Copying directory 3](cse15l-lab-report-3-ss11.png)

* Although long, the above picture(s) show all files from my `markdown-parser` directory being `scp`'d to my remote account (ieng6).

![Copying only java and md files](cse15l-lab-report-3-ss12.png)

* To make it so I only send my `.java` and `.md` files from my local to remote computer, I remove the files I sent originally, and tried `scp`ing with the new command (as seen above).

![Showing that the files were sent to the remote host](cse15l-lab-report-3-ss13.png)
![Running the commands on the remote host](cse15l-lab-report-3-ss14.png)

* As seen above, I logged into my remote account and ran the markdown tests.

![Copying a directory and running commands all at once](cse15l-lab-report-3-ss15.png)

* I was also able to send a directory and run the tests all in one line!