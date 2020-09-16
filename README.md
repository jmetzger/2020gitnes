# GIT-Training in Bad Neustadt 

## gitworkflow (used by git.git team) 

  * https://linux.die.net/man/7/gitworkflows
  * https://hackernoon.com/how-the-creators-of-git-do-branches-e6fcc57270fb

  * 2 Eternal Branches 
    - maint
    - master
  
  * Only branch from master 
  
  * 2 Branches that will be rebuild after each release. 
    * next
    * pu
    
  * We will use topic branches (for features) 
    
  ```
  
  o-o-o-o maint (is always the last release/ only bugfixes will done here) 
  
  o-o-o-o master (this is the branch we always branch our topics from 
  \
   \     o-o-o-o-o-o-o-o-o  pu (proposed updates for next release) 
    \                   /
     \   o-o-o-o-o  next (last-release + stories that did not make it into release) 
      \         /     /
       \ o-o-o-o-o-o-o story-1 
       
  ```
