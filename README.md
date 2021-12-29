# 1890_Jump

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1890_Jump/blob/main/1890_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

At first , I tried to do with the queue. Starting from the end and push the possible cases and at last, if (0,0) pop out, ans + 1.

This approach got failed, because of lack of memory.

After that I notice that if there is only 2 way (right, down) searching it with two for loop will not miss the next jump location.

After that I check the possible jump location from the starting point. Save the possible cases to reach the current location and if I can jump to some location, add the possible cases to reach the current location.

Then [n-1][n-1] location will be possible cases to reach the end.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
