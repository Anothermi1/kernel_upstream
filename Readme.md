# Upstream Linux Kernel For Android

#### Here

    git fetch https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/ <next-ver>

### Example :

My kernel version is v4.9.304, and i want to upstream to 4.9.305, so type :

    git fetch https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/ v4.9.305
    
### Wait a minute, if done type :

    git merge FETCH_HEAD

### Fix the conflicts and

    git add .

### Last Step
    git merge --continue
