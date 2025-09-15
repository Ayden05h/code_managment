A. What triggers this workflow to run? (Look at the on: section) 
1.The workflow is triggered to run through the push to main branch 
B. What are the four main steps this workflow performs? (List each step name) 
1.check code 
2. set environment 
3.run test 
4.deploy 
C. What does the "Checkout code" step do and why is it necessary? 
1.it downloads the code on github and allows it to run correctly 
D. What is the purpose of the environment configuration? 
1.it allows your workflow to run correctly avoiding compatibility issues 
E. How does this automated deployment improve reliability compared to manual deployment? 
1.it alows less human error, allows the code to be tested before publication, and quickens the delivery time 
F. What would happen if you pushed code to a different branch (not main) 
1.it wouldnt run because it only runs in the main branch.
