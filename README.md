# Learn-git-branching

## Level 1

### Task 1
```bash
git commit
```
![alt text](assets/image.png)

### Task 2
```bash
git checkout -b bugFix
```
![alt text](assets/image2.png)

### Task 3
```bash
git checkout -b bugFix
git commit
git checkout main
git commit
git merge bugFix 
```
![alt text](assets/image3.png)


### Task 4
```bash
git checkout -b bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main
```
![alt text](assets/image4.png)

## Level 2

### task 1

```bash
git checkout c4
```

![alt text](assets/image-0.png)


### task 2

```bash
git checkout HEAD^
```

![alt text](assets/image-1.png)

### task 3

```bash
git checkout c6
git branch -f main HEAD
git branch -f bugFix HEAD~4
git checkout c1
```

![alt text](assets/image-2.png)

### task 4

```bash
git reset HEAD~1
git checkout pushed
git revert HEAD
```

![alt text](assets/image-3.png)

## Level 3

### Task 1

```bash
git cherry-pick c3 c4 c7
```

![alt text](assets/image-4.png)

### Task 2

```bash
git rebase -i HEAD~4
```

![alt text](assets/image-5.png)


## Level 4

### Task 1

```bash
git checkout main
git cherry-pick c4
```
![alt text](assets/image-6.png)

### Task 2

```bash
git rebase -i HEAD~2
git git commit --amend
git rebase -i HEAD~2
git branch -f main c3''
```

![alt text](assets/image-7.png)


### Task 3

```bash

git checkout main
git cherry-pick c2
git commit --amend
git cherry-pick c3

```

![alt text](assets/image-8.png)

### Task 4

```bash
git tag v0 c1
git tag v1 c2
git checkout v1
```

![alt text](assets/image-9.png)

### Task 5

```bash
git describe <branch/commit-hash>
```

![alt text](assets/image-13.png)


## Level 5
### Task 1

```bash
git rebase main bugFix
git rebase bugFix side
git rebase side another
git branch -f main another
```

![alt text](assets/image-10.png)

### Task 2

```bash
git branch bugWork main~1^2~1
```

![alt text](assets/image-11.png)

### task 3

```bash
git checkout one
git cherry-pick c4 c3 c2
git checkout two
git cherry-pick c5 c4 c3 c2
git branch -f three c2
```

![alt text](assets/image-12.png)








