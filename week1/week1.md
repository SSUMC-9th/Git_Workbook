# Git 명령어 정리

##  Git 설정

```bash
git config --global user.name "사용자이름"     # 사용자 이름 설정
git config --global user.email "이메일주소"    # 사용자 이메일 설정
git config --list                              # 설정 정보 확인
```

---

##  로컬 저장소

```bash
git init                 # Git 저장소 초기화
git clone [URL]          # 원격 저장소 복제
```

---

##  변경 사항 관리

```bash
git status                   # 변경된 파일 상태 확인
git add [파일명]             # 특정 파일 스테이징
git add .                    # 전체 파일 스테이징
git commit -m "메시지"       # 커밋 생성
git commit -am "메시지"      # 수정 및 커밋 동시에 (tracked 파일만)
```

---

##  브랜치

```bash
git branch                  # 브랜치 목록 확인
git branch [브랜치명]       # 새 브랜치 생성
git checkout [브랜치명]     # 브랜치 이동
git checkout -b [브랜치명]  # 새 브랜치 생성 및 이동
git merge [브랜치명]        # 브랜치 병합
git branch -d [브랜치명]    # 브랜치 삭제
```

---

##  원격 저장소

```bash
git remote -v                          # 원격 저장소 확인
git remote add origin [URL]           # 원격 저장소 추가
git push origin main                  # 원격 저장소로 푸시
git push -u origin main               # 기본 브랜치 설정 후 푸시
git pull origin main                  # 원격 저장소에서 가져오기
```

---

##  기타 유용한 명령어

```bash
git log                      # 커밋 로그 확인
git log --oneline            # 간단한 로그 확인
git diff                     # 변경된 내용 비교
git reset --hard HEAD~1      # 이전 커밋으로 되돌리기
git stash                    # 작업 임시 저장
git stash pop                # 임시 저장 복원
```

---

##  도움말

```bash
git help [명령어]            # 해당 명령어 도움말 보기
```

