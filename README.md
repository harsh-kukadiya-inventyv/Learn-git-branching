# Learn-git-branching Main

## Level 1

### Task 1
```bash
git commit
```
![alt text](assets-main/image.png)

### Task 2
```bash
git checkout -b bugFix
```
![alt text](assets-main/image2.png)

### Task 3
```bash
git checkout -b bugFix
git commit
git checkout main
git commit
git merge bugFix 
```
![alt text](assets-main/image3.png)


### Task 4
```bash
git checkout -b bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main
```
![alt text](assets-main/image4.png)

## Level 2

### task 1

```bash
git checkout c4
```

![alt text](assets-main/image-0.png)


### task 2

```bash
git checkout HEAD^
```

![alt text](assets-main/image-1.png)

### task 3

```bash
git checkout c6
git branch -f main HEAD
git branch -f bugFix HEAD~4
git checkout c1
```

![alt text](assets-main/image-2.png)

### task 4

```bash
git reset HEAD~1
git checkout pushed
git revert HEAD
```

![alt text](assets-main/image-3.png)

## Level 3

### Task 1

```bash
git cherry-pick c3 c4 c7
```

![alt text](assets-main/image-4.png)

### Task 2

```bash
git rebase -i HEAD~4
```

![alt text](assets-main/image-5.png)


## Level 4

### Task 1

```bash
git checkout main
git cherry-pick c4
```
![alt text](assets-main/image-6.png)

### Task 2

```bash
git rebase -i HEAD~2
git git commit --amend
git rebase -i HEAD~2
git branch -f main c3''
```

![alt text](assets-main/image-7.png)


### Task 3

```bash

git checkout main
git cherry-pick c2
git commit --amend
git cherry-pick c3

```

![alt text](assets-main/image-8.png)

### Task 4

```bash
git tag v0 c1
git tag v1 c2
git checkout v1
```

![alt text](assets-main/image-9.png)

### Task 5

```bash
git describe <branch/commit-hash>
```

![alt text](assets-main/image-13.png)


## Level 5
### Task 1

```bash
git rebase main bugFix
git rebase bugFix side
git rebase side another
git branch -f main another
```

![alt text](assets-main/image-10.png)

### Task 2

```bash
git branch bugWork main~1^2~1
```

![alt text](assets-main/image-11.png)

### task 3

```bash
git checkout one
git cherry-pick c4 c3 c2
git checkout two
git cherry-pick c5 c4 c3 c2
git branch -f three c2
```

![alt text](assets-main/image-12.png)

# Learning-git-braching Remote

## Level 1
### Task 1

```bash
git clone
```
![alt text](assets-remote/image.png)


### Task 2

```bash
git commit
git checkout o/main
git commit
```
![alt text](assets-remote/image-1.png)


### Task 3

```bash
git fetch
```

![alt text](assets-remote/image-2.png)


### Task 4

```bash
git pull
```

![alt text](assets-remote/image-3.png)

### Task 5

```bash
git clone
git fakeTeamwork 2
git fetch
git commit
git merge o/main

```

![alt text](assets-remote/image-4.png)

### Task 6

```bash
git commit
git commit
git push
```
![alt text](assets-remote/image-5.png)

### Task 7

```bash
git clone
git fakeTeamwork 1
git commit
git pull --rebase
git push    
```
![alt text](assets-remote/image-6.png)

### Task 8
```bash

git branch -f main o/main
git branch feature c2
git push origin feature
git checkout feature 
```

![alt text](assets-remote/image-7.png)


## Level 2

### Task 1

```bash
git fetch
git rebase o/main side1
git rebase side1 side2
git rebase side2 side3
git rebase side3 main
```

![alt text](assets-remote/image-9.png)

### Task 2

```bash
git checkout main
git pull
git merge side1
git merge side2
git merge side3
git push origin main
```

![alt text](assets-remote/image-8.png)

### Task 3

```bash
git checkout -b side o/main
git commit
git pull --rebase
git push
```

![alt text](assets-remote/image-10.png)

### Task 4
```bash
git push origin main
git push origin foo
```

![alt text](assets-remote/image-11.png)

### Task 5
```bash
git push origin foo:main
git push origin main^:foo
```
![alt text](assets-remote/image-12.png)

### Task 6

```bash
git fetch origin c3:foo
git fetch origin c6:main
git checkout foo
git merge main
```

![alt text](assets-remote/image-13.png)

### Task 7
```bash
git push origin :foo
git fetch origin :bar
```

![alt text](assets-remote/image-14.png)

### Task 8
```bash
git pull origin c3:foo
git pull origin c2:side
```
![alt text](assets-remote/image-15.png)
