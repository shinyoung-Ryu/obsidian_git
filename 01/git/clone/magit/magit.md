---
date: 2025-03-19
---

1. [[sshSetup]]
2.  parentFolder -> magit status (spc g g) -> magit-dispatch (C-c C-c) -> Clone (S-c) -> url(u) -> user@Host:repositoryAddress
- parentFolder/repository folder 생성
- 생성된 local folder는 Host에 등록된 identityFile(ssh private key)로만 git이 작동한다!!

![[file-20250319163910384.png]]

- nix flake ssh config setup
![[file-20250319164059236.png]]

- ssh config 확인
![[file-20250319164235644.png]]

![[file-20250319164258466.png]]