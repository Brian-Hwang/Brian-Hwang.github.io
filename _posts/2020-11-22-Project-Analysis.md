---	
layout: post	
title:  "[선정 프로젝트 분석 및 개선방향]"	
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
→ 안드로이드 스튜디오에서 인스타그램과 같은 카메라 촬영/동영상 버튼으로 기존 심심했던 카메라 버튼을 누를 수 있게 활용.
특히 동영상 촬영의 경우 최대 가능한 영상의 길이를 한눈에 알 수 있고 영상의 길이를 촬영중에 알 수 있다는 장점이 있다.
나아가 여러가지 메뉴를 버튼 자체에서 스와이프를 통해 선택할 수 있다는 장점이 있다.
나아가 복잡한 Java코드가 필요없이 xml과 handler을 사용하여 바로 생성이 가능하다.
```

다음과 같은 라이선스를 따름:
http://www.apache.org/licenses/LICENSE-2.0
<p class="mb-5"><img class="shadow-lg" src="assets/images/Instagram_button2.jpg"/></p>

최근 커밋이나 이슈: 

```html	
1) 이를 활용하여 동영상을 녹화하는 방식에 대한 설명/ 방식이 미흡함 → 이를 설명
2) 버튼 Stroke의 너비를 조절할 수 있는 옵션이 없음
```

개선방향:

```html	
1) 이 깃헙 코드의 장점은 여러가지 customization이 가능하다는 것이다. 
이에 카메라 버튼 자체의 다체로운 색을 고를 수 있게 활용할 수 있게 해 더 
다체로운 customization을 지원할 수 있었으면 좋겠다.
2) 같은 맥락으로 최근 이슈 중 하나였던 Stroke의 너비를 조절할 수 없다는 데에
있어 이는 명백한 니즈가 있는것을 보아 개발 계획 중 하나로 꼽을 수 있으면 좋겠다.
```

개발 계획:
```html	
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
      
	14주차& 15주차::
    • 프로젝트 최종 Wrap-up
    • 프로젝트 진행 상황을 문서화하여 커뮤니티에 기여 및 피드백
    • 깃허브 페이지 지속적으로 관리 → 페이지 공유를 통한 커뮤니티의 기여
```
