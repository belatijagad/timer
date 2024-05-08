## 1.2 Understanding How It Works
Even though by order, `Howdy` and `Done` is placed first, `Hey Hey` is printed first, just as seen in this picture.

![Alt text](timer_1.png)

This happens because `Howdy` and `Done` is an asynchronous task, so the program doesn't wait for it to be done to execute the next one. Hence, `Hey Hey` is executed first before `Howdy`.