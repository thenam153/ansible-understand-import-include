### Understand about Import and Include scope vars
---
1. Include 
    * Is dynamic
    * Import when process
    * Add vars when call task will overwrite vars in task
    * If not have vars when call tasks, task use vars with precedence
2. Import is static
    * Is static
    * Import pre-process when play was parsed
    * Add vars when call task will NOT overwrite vars in task
    * If not have vars, task use vars with precedence
