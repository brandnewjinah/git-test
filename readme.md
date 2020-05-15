---
title: Git Test
date: "2020-05-15T22:40:32.169Z"
description: 위코드 git test.
---

### Git 사용하기

Git 을 이용해 내 Gatsby blog content 를 올리는 법을 정리

#### Git 에 올릴 파일이 있는 폴더로 이동

```console
cd documents
cd codes
cd blog
```

#### Git Repo 생성한 후 연동시키기

```console
git init
git remote add origin https://github.com/brandnewjinah/blog.git
```

#### Git Staging (telling git which files to put into a commit)

```console
git add .
```

#### Commit

```console
git commit -m "first commit"
git push origin master
```

#### 브랜치 생성하기

```console
git branch develop
git checkout develop
```

#### 브랜치에 올리기

```console
git add .
git commit -m “branch”
git push -u origin develop
```
