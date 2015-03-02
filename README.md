# GitRepoWorkflow
 - Follows closely traditional GitFlow - https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow  
 - Steps below document the differences and needed clarifications, without duplicating the GitFlow docs
 
- Branch names should use dashes, rather than slashes
- Branch names should include the dev's initials
- Branch names should end with a hash and the issue number the work is under
  - ie: feature-dme-xcode-static-library#557
  - ie: feature-dme-xcode-static-library-DoubleNode/DoubleNode#557 (if the issue is in a different repo)

### When working an issue:
- Create feature branch (ie: feature-dme-xcode-static-library#557)
- Publish feature branch immediately (moves tagged issue to "In Progress")
- Do work, commit, push, rinse and repeat...
- 
