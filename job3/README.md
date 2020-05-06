# Procedure for job3:
- Firstly create a job in Jenkins
- Go to Source Code management section in configure of job3 .Give the details of the github repository and give the branch name as master branch .Also you need to give your username and password as you are merging the branches.
- Then go to trigger section select the option by which you want to trigger. In my case I used trigger built remotely as a developer wants his code to be merged with the uploaded code only when the development environment passes all the tests. I used the url to merge the contents.
- Finally I could see the output required i.e. the contents of the merged branches.
