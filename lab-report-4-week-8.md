# CSE15L Lab report 1 | Week 2 
```
Written and Submitted By: Billy Phan
```
---
> **Prediction Of Test Results**

### Test 1
![Test1](cse15l-lab-report-4-test1.png)

* According to the file preview, `Test 1` should produce the links "`google.com", "google.com", and "ucsd.edu".

### Test 2
![Test2](cse15l-lab-report-4-test2.png)

* According to the file preview, `Test 2` should produce the links "a.com", "a.com(())", "example.com".

### Test 3
![Test3](cse15l-lab-report-4-test3.png)

* According to the file preview, `Test 3` should produce the link "https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule".

---
> **Turning Test Files into Tests**

### Test 1 
![Test1Imp](cse15l-lab-report-4-test1-implemented.png)

### Test 2 
![Test2Imp](cse15l-lab-report-4-test2-implemented.png)

### Test 3 
![Test3Imp](cse15l-lab-report-4-test3-implemented.png)

---
> **My Implementation**

### Test 1 (failure)
![MyMarkdownTest1](cse15l-lab-report-4-ss4.png)

### Test 2 (failure)
![MyMarkdownTest2](cse15l-lab-report-4-ss5.png)

### Test 3 (failure)
![MyMarkdownTest3](cse15l-lab-report-4-ss6.png)

---

> **Other Implementation**

### Test 1 (failure)
![OtherMarkdownTest1](cse15l-lab-report-4-ss1.png)

### Test 2 (failure)
![OtherMarkdownTest2](cse15l-lab-report-4-ss2.png)

### Test 3 (failure)
![OtherMarkdownTest3](cse15l-lab-report-4-ss3.png)

---
> **Explanations**

* Test 1: My and the other test 1 implementation can be fixed under 10 lines of code. I believe that I would simply need an `if statement` to check if theres an inline command before and after "[", and "]".

* Test 2: My and the other test 2 implementation cannot be fixed under 10 lines of code. I believe that I would need multiple statements `if statements`, as well as temporary variable holders in order to check for nested brackets and paranthesis. 

* Test 3: My and the other test 3 implementation can be fixed under 10 lines of code. I believe that I would just need a loop to check multiple lines if a symbol (`[,],(,)`) is not on the same line. 