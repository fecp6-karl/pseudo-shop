# Final Project Retrospective

## Team Members
- Agner, Neil Dustin Benedict
- Alcayde, Aidan Carl
- Cheng, Xian Hui
- Cruz, John Adrian
- Romero, Karl


## 1. How did you divide the work between you and your partner?
_(Who worked on which features? How was the work assigned or negotiated?)_
Among 5 members, 3 were assigned to features 1,3, and 4 while the remaining 2 were assigned to feature 2 because it was what the group thought was most appropriate for two members, given that it involved user registration and login. Meanwhile, for the rest of the features, it was agreed upon by the group that it was able to be accomplished by one person. As for how the work was assigned, each member just chose which features they wanted to work on.

## 2. What Git strategies or commands helped you most during the project?
_(E.g., branching, rebasing, frequent commits, etc.)_

## 3. Describe a merge conflict you encountered. What caused it and how did you resolve it?
_(Include any lessons learned or techniques used to resolve the issue.)_
The primary merge conflicts were due to multiple branches editing the same pseudo-code files. One conflict was in user_controller.pseudo, because the Feature 2 work was split between user creation and login, so both branches changed the same area of the user model and had to be combined into one consistent registration/login flow. After pulling the product management branch up to date, we encountered another conflict in store_view.pseudo the storefront display and filtering branches had been merged into main already. Our branch had a simple display_products() function to display product details. Main had storefront formatting, filter handling, and empty-list logic. We used the collaboration technique from Lesson 3 to resolve the conflicts where we communicate, compare both versions, keep both useful changes instead of overwriting one side, remove the conflict markers, commit the resolved pseudo-code, and push the updated branch back to GitHub. The main thing to note is that feature branches help keep things organized but when multiple features touch the same pseudo-code function the team has to coordinate earlier and pull down the latest changes before opening or updating pull requests.
## 4. What were the biggest challenges you faced as a team?
_(This can include communication, Git usage, or coordination.)_

## 5. What did you learn about using Git in a collaborative setting?
_(Any insights or habits you’d apply in future projects?)_
- It is important to have a centralized checklist, to-do-list, or ticketing system for features to be implemented. Having an actual work plan helps streamline the workflow and collaboration, and most importantly avoids redundant work by having a clear implementation sequence.
- git can significantly help in collaboration, provided everyone has a clear understanding of how it works, how the workflow works, and how the project is structured. git is just a tool; it's effectiveness greatly depends on its users.
- To avoid divergent code and general conflict issues, it is important to discuss potential overlaps among team members, to make use of git's features such as branching, NEVER force-pushing, and to just keep commits small and targeted.


## 6. How would you improve your workflow next time?
_(Think about technical habits and teamwork practices.)_
- Communication is KEY! Plan ahead, discuss and distribute work, and have a stringent review process. Development is not the most difficult part of the job: knowing what exactly to develop is.
- Have consistent conventions and make sure that the team strictly follows it. From branch naming to actual code implementation, to merging timelines and code/PR reviews, things are easier if everyone is onboard with the same ideas and patterns in mind.
- Keep commits small and targeted to specific features, and create branches for specific tasks: this avoids code divergence and conflicts, as well as making it easy to understand how the codebase evolved, and ensuring that things can be rolled back easily when things go wrong.

## 7. Optional: Any feedback on the activity?
_(What worked well? What was confusing or could be improved?)_
- Working with pseudo code was quite difficult: every team member had a different approach to pseudocode, which led to a multiple passes of code consistency reviews after the initial compliance to the git branching and workflow management requirements were met.
- The bare-bones project structure led to some conflicts on how deep and serious the implementation logic is supposed to be, as opposed to simply mimicing collaborative git workflow.
