---
title: TortoiseSVN External Diff Merge 설정
author: Whtiecoke
data: 2020-12-08 12:23:00 +0800
categories: [Blogging, Test]
tags: [SubVersion]
---

## SVN 외부 Diff, Merge 설정.

기본개념은 = "절대경로" 옵션 이다.
여기서는 Beyond Compare 4 기준으로 External Tool 설정하는 방법을 설명한다.

## Diff

![DiffView](/assets/img/posting/201208_diff.png)
 
 ```terminal
 tortoise SVN - Setting - Diff Viewer Tab - 
 Configure the program used for comparing different revisions of files.
 ```

## Merge

![MergeView](/assets/img/posting/201208_merge.png)

```terminal
tortoise SVN - Setting - Diff Viewer Tab - 
Configure the program used for comparing different revisions of properties.
```
```terminal
tortoise SVN - Setting - Merge Tool Tab - 
Configure the program used for comparing different revisions of properties.
```

각각 이미지 상 해당 부분에 [경로 설정 + 옵션] 설정을 해주면 된다.
참고로 기본 text파일이 아닌, .doc와 같은 파일은 Advanced 버튼을 클릭해서 해당 경로를 연결해줘야 한다.
