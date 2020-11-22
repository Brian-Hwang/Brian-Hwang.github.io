---	
layout: post	
title:  "[ 팀별 진행사항 정리 // 선정 프로젝트 분석 및 개선방향]"	
author: Brian
categories: [ instruction, tutorial ]	
tags: [what, project]
image: assets/images/Instagram_button.gif
description: "Project Description"	
featured: true	
hidden: false	
rating: 4.0	
---	

Github Link: https://github.com/hluhovskyi/CameraButton?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=6877 

OSS_5 MEMBERS : Brian-Hwang, leedayun, Na-Hyeon-Oh, Jungseoyeon, ChoHyeonSu, jihye0



오픈소스 소개(README.md 참고):

```html	
→ 안드로이드 스튜디오에서 인스타그램과 같은 카메라 촬영/동영상 버튼으로 
기존 심심했던 카메라 버튼을 누를 수 있게 활용.

특히 동영상 촬영의 경우 최대 가능한 영상의 길이를 한눈에 알 수 있고 영상의 
길이를 촬영중에 알 수 있다는 장점이 있다.

나아가 여러가지 메뉴를 버튼 자체에서 스와이프를 통해 선택할 수 있다는 장점이 있다.

마지막으로 복잡한 Java코드가 필요없이 xml과 handler을 사용하여 바로 생성이 가능하다.
```

다음과 같은 라이선스를 따름:
http://www.apache.org/licenses/LICENSE-2.0


최근 커밋이나 이슈: 

```html	
<프로젝트의 최근 이슈 내용>
1. Expanded stroke width를 설정할 수 있는 옵션이 없다는 이슈
2. 동영상을 촬영할 때, undefined 된 시간 동안 촬영할 수 있게 하는 기능이 없다는 이슈
→ 2019년에 만들어진 이슈임에도 불구하고 아직 해결이 되고 있지 않음
<새로운 issue 제안>
1. 버튼 색 customization
2. 튜토리얼 작성
기존의 이슈들과 더불어 튜토리얼 작성, 버튼 색 customization 과 관련된 
issue를 개설하여 개발을 진행할 예정.
이 외에도 개발을 하면서 다양한 issue를 추가할 예정입니다.
```

개선방향:

```html	
1) 이 깃헙 코드의 장점은 여러가지 customization이 가능하다는 것이다. 
이에 카메라 버튼 자체의 다체로운 색을 고를 수 있게 활용할 수 있게 해 더 
다체로운 customization을 지원할 수 있었으면 좋겠다.
2) 같은 맥락으로 최근 이슈 중 하나였던 Stroke의 너비를 조절할 수 없다는 데에
있어 이는 명백한 니즈가 있는것을 보아 개발 계획 중 하나로 꼽을 수 있으면 좋겠다.
```

개발 계획 및 진행 상황:
```html	

<팀 내 개발 진행 상황>
먼저 팀 개개인 각자가 관심 있는 분야의 오픈소스를 조사했습니다.
이후 팀 회의를 통해 개인이 조사해온 오픈소스 프로젝트에 대한 소개
및 설명을 한 후 투표를 통해 팀원 모두가 관심 있어 하는 프로젝트를 선정했습니다.
	
이후 함께 프로젝트를 완성해나갈 커뮤니티로 github를 골랐습니다.
회의를 통해 팀원 개인별 역할 및 활동을 정했습니다.
프로젝트에서 팀원 개인별 역할을 크게 <개발>과 <깃헙관리> 부분으로 나누었습니다.
각자가 관심있어하는 분야에 대해 이야기를 나누고 역할을 나누었습니다.
	
<주차별 진행 상황>
	
	09주차:
    • 프로젝트 5개중 2개로 선정 (후보: instagram camera button 및 C++ 가이드라인 한글화 프로젝트)
    •프로젝트 내 업무 분담
	
	10주차:
    • 정적 페이지 활용 방식 숙지
    • github repository 정리 및 보완
    • 프로젝트 pre-start 자료조사
	
	11주차:
    • 현제 진행 프로젝트에 맞춰 원하는 커뮤니티 결정 → github Community
    •  커뮤니티 사용법 숙지 및 활용법 토론
    • 커뮤니티 사용시 활용 가능한 활동 정하기 및 역할 분담
	
	12주차& 13주차:
    • 버튼 색 Customization 및 Stroke 너비 조절 개선을 위한 프로젝트 진행
    • 기타 이슈 개선을 위한 프로젝트 추가 진행
    • 진행시 생기는 문제점 해결들은 지속적으로 Pull Request 및 커뮤니티 기여
    • 프로젝트 진행 상황을 문서화하여 커뮤니티에 기여 및 피드백
    • 깃허브 페이지 지속적으로 관리 → 페이지 공유를 통한 커뮤니티의 기여
      
	14주차& 15주차:
    • 프로젝트 최종 Wrap-up
    • 프로젝트 진행 상황을 문서화하여 커뮤니티에 기여 및 피드백
    • 깃허브 페이지 지속적으로 관리 → 페이지 공유를 통한 커뮤니티의 기여
```
