# Merge Conflicts
Merge conflicts happen when changes on the same file from different branches conflict with each other. These are common problems, but luckily, aren't too hard to fix. We'll see an example of this in this section and provide step-by-step instructions on how to solve it.<br>

1. You'll know if you have a merge request when you get this message when trying to make a pull request.<br>
![image](https://user-images.githubusercontent.com/48599206/131273636-90864013-4548-4b9a-bb2c-6421473ba040.png)

2. To find where the conflict is happening, we need to click on "resolve conflict"
![image](https://user-images.githubusercontent.com/48599206/131273676-4c5f96ba-63bd-419a-9a06-d019c27ef27d.png)

3. From there, we can see the conflict. In this case, we have a conflict in the README.md file. On line two of our README.md, our main says "Hello World", but our current branch says "Different change from a different branch". We can't have them say two different things so we need to choose which ones to keep.<br>
![image](https://user-images.githubusercontent.com/48599206/131273716-6df57b7e-70c7-46c4-80bb-130e74aaa8e2.png)

4. You can resolve the conflicts with your team and decide which code to keep and delete the other code. In my example, I choose to keep the current branch changes and delete the main's version<br>
![image](https://user-images.githubusercontent.com/48599206/131273830-8087c63d-e5e0-4576-9a8b-6688417f69a1.png)

5. Once you've fix all the conflicts, then you can click "mark as resolve".<br>
![image](https://user-images.githubusercontent.com/48599206/131273974-940a82e1-1d5e-4e33-a1e9-32910771f1c5.png)

6. That'll finish the action and allow you to commit the changes and merge to main.<br>
![image](https://user-images.githubusercontent.com/48599206/131274030-4835e12a-5d24-43b5-929c-dbaa57e9d170.png)

7. If all goes well, then it should look like this.<br>
![image](https://user-images.githubusercontent.com/48599206/131274093-fd42f7d3-d221-465e-acbd-3efda87ed79e.png)

Congrants! You've learned how to resolve a merge conflict.
