# Basic UI Training

두 가지 미션이 있습니다. HTML/CSS/JS를 이용하여 구현해주세요. 주어진 하나의 템플릿에 두 가지 모두 작업해주세요.
자바스크립트의 경우, 동일한 파일에 작업하시되 주석 처리를 하여 Menu 또는 Accordion 관련 부분을 표기해주세요.

1. [메뉴 UI 만들기](#Menu)
2. [아코디언 UI 만들기](#Accordion)

# Menu

- 다음과 같이 작동하는 Menu UI를 만들어 주세요.

![screenshot](https://github.com/vanilla-coding/basic-ui/blob/master/menu.gif?raw=true)

# Accordion

- 다음과 같이 작동하는 Accordion UI를 만들어 주세요.



# Prerequisites

- git
  - Mac: http://sourceforge.net/projects/git-osx-installer/
  - Window: http://msysgit.github.com/
- node
  - Mac/Window: https://nodejs.org/en/download/

---

# Installation

- 우선 repository를 본인 Github 계정으로 fork해주세요. (바닐라코딩 해당 repository 페이지 오른쪽 상단에 보시면 fork 버튼이 있습니다.)

```
** 본인이 원하는 디렉토리내에서 실행할 것. **

// fork해온 프로젝트를 본인 컴퓨터에 다운받는 명령어
git clone https://github.com/당신의유저네임/basic-ui.git

// 방금 clone한 디렉토리로 이동
cd basic-ui

// Git 브랜치 이동
git checkout master

// 작업에 필요한 구성 요소 설치
npm install
```

---

# 쉽게 작업하는 법

```
// 프로젝트 디렉토리로 이동 후, 아래의 명령어를 실행시켜 보세요.
// 브라우저에 자동으로 작업하는 페이지가 열리고,
// 작업을 하시면서 변동 사항을 저장하시면 자동으로 브라우저는 변화를 감지하고 새로운 화면을 보여줍니다.
npm start

// 작업 끝내기
MAC/Window: control + C
```

---

# 작업 내용 저장하는 법

```
// 프로젝트 디렉토리에서 아래의 명령어를 순서대로 실행한다.
git status (작업하고 수정된 파일들의 목록을 보여준다. 그냥 확인하고자 하는 목적.)
git add . (수정한 모든 파일을 git에게 통보한다.)
git commit -m "무엇 무엇 완료" (방금 git에게 통보한 모든 파일을 저장시킨다.)
git push origin master
```

---

# 작업 내용 Ken과 공유하는 법

작업 내용 저장 후, 다음 링크의 방법을 따라하세요.[PR 만들기](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)

**영어 잘 이해 안되시면 슬랙 채널에 물어보세요!**

---
