# docassemble.OutsideActivityMemo

A docassemble extension.

## Author

Kisha Wilson
kwilson5@su.suffolk.edu

## Disclaimer

This form has been created for a class project and should not be considered legal advice or services.

## Project Biography

### Problem: 

Employees must get approval for Outside Employment Activities prior to commencing the activity. Members of the ethics team have identified a number of employment activities that are automatically approved, and also those that would be automatically denied. However, members of the ethics team are also part of the legal team and when the volume is high, the approval responses are slow. Employees and the outside employers can become frustrated as they wait for Ethics approvals to come through. Ethics team members can become frustrated when they don't have adequate information to make a determination.  Additionally, disctretion of the Ethcis introduces the potential for variation amongst the decisions. There is a need for a tool that helps to automate all of the "easy catch" requests and collect the additional information required for the ethics review team. A streamlined solution would increase productivity, save time for more valuable activities for employees and the ethics team, and reduce employee frustration.

### Key Stakeholders: 

Ethics team reviewers, employees, outside employers, local Github hosting team.

### Introduction to the project:  

A five-minute powerpoint introduction to the project can be found at https://github.com/krwilson32/docassemble-OutsideActivityMemo/blob/main/Final%20Project_Kisha%20Wilson.pptx

### Research: 

The first step in my research was figuring out which tool would be most helpful in addressing this issue. I spoke with my Supervisor, who is my Project Partner, and she mentioned that the solution needed to be simple enough to be self-guided. I considered ease of use, cost, portability, user interface, and the tools and training I already had available to me when making a selection. A guided interview was an obvious choice to root out the obvious approvals and denials while gathering the info we need for those requests that need additional review. I considered tools like Community.Lawyer, documate, and QnA Markup but ultimately found that docassemble would be the most helpful tool as it provided me with the most flexibility, was cost-effective, was the one I was most familair with and easliy integrated with GitHub which is actively used in the organization. Once I determined that Docassemble would be the plaform to use, I saw that there were many a number of approval tools that were very helpful to look at but I found docassemble documentation to be the most helpful resource as the approval tool I've created addresses the specific rules associated with this organization. I was able to use some of the conditional logic from other Document Assembly Line projects. For example, I used some conditional logic on my docx file that was used on one of the Tenancy forms to hide sections of the docx based on the variables. I met with my Project Partner when we were orginally framing the solution and then upon completion of an MVP. Both my Project Partner and other testers went through the tool and provided feedback which was incorporated.

I also completed a flowchart which can be found at https://github.com/krwilson32/docassemble-OutsideActivityMemo/blob/main/Outside%20Activity%20Flowchart.png to map out the logic of the tool. 

### Feedback:

This project could not have been accomplished without feedback from multiple users. Final feeback from my project partner can be found here: https://github.com/krwilson32/docassemble-OutsideActivityMemo/blob/main/Project%20Partner%20Letter_Erin%20Devereaux.pdf. Attached you can also find the user testing matrix that was used test all of the possible outcomes at: https://github.com/krwilson32/docassemble-OutsideActivityMemo/blob/main/Outside%20Activity%20Memo_Testing%20Matrix.xlsx. Testing was done by myself, the Project Partner and my partner Kevin Montoya who took the place of an employee who would use the tool.

Key considerations for user personas:
- Officers are automatically pending
- non-officers are automatically approved for non-financial approved positions
- all employees are denied for financial sector positions

User personas for testing:
 1. Non-officer employee who is doing a nonfinancial paid position in an approved category
 2. Non-officer employee in a financial position in approved
 3. Non-officer employee in a financial position not in a approved category
 4. Non-officer employee in a nonfinanancial not approved category
 4. Officer employee who is doing a nonfinancial paid position in an approved category
 5. Officer employee in a financial position in approved
 6. Officer employee in a financial position not in a approved category
 7. BTS employee in a CASUAL IT position nonfinancial
 8. BTS employee in a financial CASUAL IT position 
 
 
Version 1- Identified issues by user tests:
- Multiple scenarios were putting out three different forms. | combined into one form using conditional logic on DOCX
- Checkboxes made the look intimidating | switched to dropdown
- No ability to send to Ethics team 
- No screen indicating approval/pending/denial prior to receiving the memo. | added to the final document printout screen
- Visually Memo needed tweaks | Memo updated to reflect design updates (changes to font size, spacing, and layout)
- Questions should be separated into different categories - too much at once (broke into sections: user info, Activity info, special considerations, final approval screen)

Version 2
- Logic incorrect. If it's a financial sector job, it goes around the denial when it's from an "approved category" - FIXED

Version 3
- Updates from project partner - remove conditional logic for supervision positions if they are in an approved category.

Feedback has been incorporated and all issues have been resolved with the exception of enhancements which can be found in the issues log as well as below.

### Future Enchancements
- Collect approvals, denials and pending into a tracker and then use machine learning to see if certain things might be approved
- automatic e-mails
- automatic tracking
- adding rideshare as approved category
- potential board positions
- Add rideshare



