Charlotte Kim and Tommy Tran

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

   Within a Github action that runs whenever code is pushed. This is the best option because it is automatic. Every change is tested automatically, meaning it can catch bugs quickly. This keeps the workflow consistent and smooth, allowing you the ability to scale your code and improve team work.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

   No. I would not use an end to end test to check if a function is returning the correct output because these tests are meant to test the flow of the file. If we want to check if a function is returning the correct output, you would use a unit test.

3) What is the difference between navigation and snapshot mode?

   Navigation mode allows the user to record the webapge and examine it. You won't be able to analyze interactions, just performance overall. Snapshot mode analyzes the webpage in its current state. However, it cannot analyze JS performane or changes to the DOM tree.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

- Compress images
- Reduce unused JavaScript
- Better HTML practices (<meta name="viewport"> with width)
