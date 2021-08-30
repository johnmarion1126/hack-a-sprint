# Branching
Git branch allows us to test new features without affecting the main branch directly. In this guide, we'll break down the steps to create a branch and save it's contents.

1. Copy the git link (shown by the picture) and clone it to your computer bu running “git clone <git_link>”. You can use either HTTPS or SSH to do this.<br>
![image](https://user-images.githubusercontent.com/48599206/131269189-0c665b3f-b5a3-4216-9bbc-f0a336c2b899.png)
![image](https://user-images.githubusercontent.com/48599206/131269345-e0235911-30f5-4918-8646-ce3da8849457.png)

2. Move to the new directory with "cd <project_name>.<br>
![image](https://user-images.githubusercontent.com/48599206/131269444-66d73f40-7b5d-461d-b3fb-929ab8f8b5ae.png)

3. To create a new branch, use “git branch <branch_name>”.<br>
![image](https://user-images.githubusercontent.com/48599206/131269424-0086aa69-4c4c-44fd-8103-58b7fffc4e2f.png)

4. Call “git branch” to check if the new branch has been created.<br>
![image](https://user-images.githubusercontent.com/48599206/131269475-1609752e-dfc8-4446-824c-c994a0f33499.png)

5. Switch to the new branch with “git checkout <branch_name>”. (git switch also works here if you prefer that)<br>
![image](https://user-images.githubusercontent.com/48599206/131269498-47a3849d-a9f8-4057-9310-cccaa2baa0ee.png)

6. Now, we’ll make a small change to the README.md to showcase how to push your new branch to github.<br>
![image](https://user-images.githubusercontent.com/48599206/131269566-98d593a1-16ec-4624-8c49-8177b361baac.png)

7. Using git status, we can check what we changed.<br>
![image](https://user-images.githubusercontent.com/48599206/131269611-0a6ee20a-74ab-45bc-b7a8-ec7c2fc0fa0a.png)

8. To add and commit the changes, we call “git add <file_name>” then “git commit <file_name> -m <message>".<br>
![image](https://user-images.githubusercontent.com/48599206/131269665-1be6bf6b-e667-4e55-8e12-8318d9ac2e62.png)

9. If you call git status again, we can now see that our recent changes have been committed.<br>
![image](https://user-images.githubusercontent.com/48599206/131269687-ae2b7588-f28b-4d88-8546-59e96a8b1b2a.png)

10. Now we can push our local branch to the repo using “git push --set-upstream origin <branch_name>”.<br>
![image](https://user-images.githubusercontent.com/48599206/131269717-91c6dd48-22f2-4651-abdc-8d57784d6c07.png)

11. If you now refresh the repo in github, you should see this message.<br>
![image](https://user-images.githubusercontent.com/48599206/131269739-c5e17bd6-3b9a-4762-9bc8-5ba7c19990cd.png)

If you do, then you have successfully made a new branch!<br>
Make sure to periodically pull in your main branch to get any updates from your team.
