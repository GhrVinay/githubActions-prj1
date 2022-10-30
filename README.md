# githubActions project 1

This is test project to check variuos github actions features

Currently checked⍻ that:
1. Github actions make use of YAML file which specifies: Events, Jobs, Runners, Steps, Actions
2. We can create a Github actions YAML file by editing & adding an already available template or create a .yml file in .github/workflows 
(Note: Indentation is very important for the yml file)
3. We can run multiple commands using "- run:" or "-name: run:"
4. We can checkout the whole repo and access files inside it

Event - trigger
Jobs - When event occurs, it runs all the jobs within the workflow. Jobs contains multiple steps and under it actions
Runners - Container env that runs our code (github by default provides a runner, but user can also host their own runner)

Ref: https://www.youtube.com/watch?v=mFFXuXjVgkU&feature=share&utm_source=EJGixIgBCJiu2KjB4oSJEQ
