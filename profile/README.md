# Xavier AI Research and Development Team

We are the Research and Development Arm of the Xavier AI Pvt Ltd.

We are responsible for the development and maintenance of the xavier navigation and exploration software stack (based on ROS2 and Nav2) and the complete design and develepment of xavierbot robot, its electrical system and the control software.

When interacting with our repositories, please follow the below mentioned guidelines.

1. We use multiple branches for development and following are the important ones.

  - "main" hosts the latest stable and tested version of the code base that supports latest underlying frameworks such as ROS2 or NodeJS
  - "develop" hosts the experimental code that are under development or testing.
  - "distro name" hosts the stable code base tested for the respective underlying framework ("melodic" for ROS framework based repositories).
  
2. Use the following Pull Request Message when creating a pull request for merging a branch
  
  ```
    What is the feature/bug?
    (Describe what the feature/bug is)

    What is the solution?
    (Describe at a high level how the feature was implemented)

    What areas of the site does it impact?
    (Describe what parts of the site are impacted and*if*code touched other areas)

    How to reproduce the bug or test the new feature?
    (Describe the prerequisites and the steps to test)

    Other Notes
    (Add any additional information that would be useful to the developer or QA tester)
  ```
  
3. Usually development occur in the following order

  - Creating a feature branch with name "[feature] short name" tag or "[fix] short name" tag .
  - Doing the development and testing on the feature branch and using meaning full commit messages.
  - Creating a pull request to merge the feature/fix branch to "develop" branch.
  - Doing further testing on the "develop" branch.
  - Creating a pull request to merge "develop" branch with "main branch".
  - Creating a release on the main branch.
