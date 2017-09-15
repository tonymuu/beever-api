# Beever Coding Process
### Creating an Issue:
  - Non-Defect related issue descriptions should follow the story format
  
    **Example:** 
    ```
      As a {user/developer/etc} of Beever
      I would like {some feature}
      So that {some need}
    ```
  - Acceptance criteria should be clearly defined.
  
    **Example:** 
    ```
      Acceptance Criteria:
      - Something is done.
    ```
  - Proper labels should be attached to each issue
    1. Issues that introduce a new feature should have a `Feature` label
    1. Issues that improve or correct a feature's functionality should have a `Improvement` label
    1. Issues that are blocked by other issues should have a `Blocked` label and a section describing the issues that block it in its description
    1. Issues that are related to a bug should have a `Defect` label
    
### Creating a Branch:
  - The name of a branch name should contain the issue number of its related issue.
  
  **Example:**
  ```
    (#2)-Code-Process
  ```
   
### Creating a Pull Request:
  - Every pull request should have a related issue.
  - Link all pull requests in their related issues.
    1. This is to ensure that we can easily perform defect tracking in the future.
  
### Code Reviews: (Optional depending on impact)
  - A code review will be carried out as part of a `Pull Request`.
  - A code review must be signed off by **at least one other contributor.**
  - Upon completing a code review
    1. The pull request should be merged into `master`
    1. The related branch should be deleted.
    1. The `merged pull request` should be linked in the related `issue`
    1. The related issue should be closed if the pull request meets all of its `Acceptance Criteria`
    
