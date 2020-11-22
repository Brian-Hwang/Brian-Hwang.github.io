---	
layout: post	
title:  "[나의 개발 능력 및 역할분석 // 기여방안 및 계획 정리]"	
author: Brian
categories: [ instruction, tutorial ]	
tags: [what, project]
image: assets/images/MRP_0453_명함판.jpg
description: "Project Description"	
featured: true	
hidden: false	
rating: 4.5	
---	

> 우리 OSS5조는 최종적으로 인스타그램에서 활용되는 instagram camera button에 대해 프로젝트를 진행하기로 했다. 이 프로젝트는 필자가 산학협력 프로젝트에서 CurvSurf라는 회사와 함께 카메라를 활용한 AR 나무 지름 측정기 앱을 만들 당시 사용했던 툴이다. 또한 필자는 이번 OSS 수업 5조에 조장을 맡고있기 때문에 어떻게 팀을 이끌어 나갈지, 또 어떤 부분에 기여하여 팀의 발전에 이바지 할 수 있을지에 대해 posting 하겠다.

나의 개발 능력: 
```	
앞에서 언급했듯이 필자는 이번 산학협력 프로젝트에서 이 github source를 활용하여 앱 개발 경험이 있다. 때문에 기본적으로 이 github 페이지에서 활용되고 있는 XML코드와 Java 코드의 사용에 대해 잘 숙지하고 있다. 또한, 이 코드를 직접 사용하므로써 어떠한 상황에서 코드가 잘 돌아가는지, 또 어떠한 상황에서 그렇지 않은지에 대해 잘 숙지하고 있어 많은 도움을 줄 수 있다. 따라서 다른 팀원들에 비해 비교적 우위를 가지고 있는 개발 능력은 다음과 같다고 할 수 있다.
1. 실제 이 코드를 가지고 활용한 경험이 있다
2. Java 및 XML 개발 경험이 있다. 
3. Android Studio 개발 경험이 있다. 
4. Github를 사용하여 commit, push, pull 등의 기능을사용하여 이 코드를 구현해보았다.

```


필자가 실제로 활용한 XML 코드:

```xml
    <com.hluhovskyi.camerabutton.CameraButton
        android:id="@+id/recBtn"
        android:layout_width="@dimen/cb_layout_width_default"
        android:layout_height="@dimen/cb_layout_height_default"
        android:layout_marginBottom="10dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintVertical_bias="0.906" />
	
```

OSS 5조의 역할 분담:
5조의 역할분담은 다음과 같다. 우선 이것을 확인 후, 다음과 같이 분담을 한 이유를 차후 설명하겠다.
```
<개발>

    • 튜토리얼 작성(작동방식 설명 추가) (1명) - 황준용
    • 버튼 색 Customization (3명) - 이다윤 오나현 조현수
    • Stroke 너비 조절 (2명) - 임지혜 정서연
    • 이 외의 issue 및 개발 enhancement 진행 (6명) - 전원 참여
      
<github 관리>

1. 매주 진행 내용을 [문서화 작업]하여 이를 [깃허브 페이지에 반영]하고 이를 [정리 및 피드백]하는 구조
    • 문서화 작업 (2명) - 이다윤 조현수
    • 깃허브 페이지 및 정적페이지 관리(2명) - 오나현 황준용
    • 최종 정리 및 피드백 (2명) - 임지혜 정서연
2. git 활용: 개발 과정에서 생길 수 있는 Issue들을 작성하여 PR(Pull Request) 보내고, 각 이슈의 해결에 대해서는 주차별 이슈로 나눠서 위 역할을 반영한 관련 Assignee 지정 및 작업 할당
```
역할분석:

다음과 같이 역할을 분담했을때, 필자가 맡게되는 파트는 github관리에서는 github 페이지 및 static 페이지 관리이며, 개발에서는 튜토리얼 작성을 맡았다.
1)github 페이지 및 static 페이지 관리는 필자가 github static page 개발 경험이 있기 때문에 맡았다.
2) 또한, 튜토리얼 작성은 앞에서 언급한것과 같이 우리가 발전하고자 하는 깃허브 페이지에 대해 정통하고 있기때문에 기존 페이지의 문제점 및 보완점, 어떻게 보완했는지에 대해 가장 잘 알고 있을것이라고 생각했다. 

![alt text](https://github.com/Brian-Hwang/Brian-Hwang.github.io/tree/main/assets/images/socialmatic_2_mini.jpg)

개인별 기여 방안 및 계획 정리: 

```

<개발 진행 상황>
1) github page static page의 개선을 위해서는 필자가 우선 자료조사를 해야한다고 생각한다. 때문에 markdown 및 yml 파일에 적응하는것이 중요하다. 때문에 이러한 자료조사를 위해 다음과 같은 여러 사이트를 참고하고 실력을 키우는 것이 중요하다고 판단된다.
https://github.com/wowthemesnet/mediumish-theme-jekyll
https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
https://gist.github.com/kannankumar/4c613cac6d9db896062a16e1cc57d3e5
https://gist.github.com/uupaa/f77d2bcf4dc7a294d109

2) 두번째로 듀토리얼 페이지의 작성을 위해서는 지금껏 해왔던 여러가지 앱개발을 추가적으로 하며 이 instagram camera button의 여러가지 기능들을 경험해보고, 체험해보며 장단점을 확실하게 정리해야할 것이다. 아래에 보이는 사진이 우리 curvSurf 산학협력에서 실제로 만든 앱 화면이다.

![alt text](https://github.com/Brian-Hwang/Brian-Hwang.github.io/tree/main/assets/images/socialmatic_2_mini.jpg)

이렇게 만든 앱의 개발 개선 뿐만 아니라 팀원들이 지속적으로 개발하는 추가 개선 사항들 또한 실제로 사용해보고 어떻게 개선되었는지 실시간으로 듀토리얼 페이지의 업데이트가 중요할 것으로 보인다.

	
<주차별 진행 상황 中 개인별 계획 추가>
	
	09주차:
    • 프로젝트 5개중 2개로 선정 (후보: instagram camera button 및 C++ 가이드라인 한글화 프로젝트)
    •프로젝트 내 업무 분담
    + github관리에서는 github 페이지 및 static 페이지 관리이며, 튜토리얼 작성 맡음
	
	10주차:
    • 정적 페이지 활용 방식 숙지
    • github repository 정리 및 보완
    • 프로젝트 pre-start 자료조사
    + 개인 및 팀 static page 구성 리드 및 구축
	
	11주차:
    • 현제 진행 프로젝트에 맞춰 원하는 커뮤니티 결정 → github Community
    •  커뮤니티 사용법 숙지 및 활용법 토론
    • 커뮤니티 사용시 활용 가능한 활동 정하기 및 역할 분담
    + 커뮤니티 선정 및 커뮤니티 활용 오픈소스 기여 방식 결정
    + 듀토리얼 작성을 위한 기본 자료조사 시작
	
	12주차& 13주차:
    • 버튼 색 Customization 및 Stroke 너비 조절 개선을 위한 프로젝트 진행
    • 기타 이슈 개선을 위한 프로젝트 추가 진행
    • 진행시 생기는 문제점 해결들은 지속적으로 Pull Request 및 커뮤니티 기여
    • 프로젝트 진행 상황을 문서화하여 커뮤니티에 기여 및 피드백
    • 깃허브 페이지 지속적으로 관리 → 페이지 공유를 통한 커뮤니티의 기여
    + Static 페이지에 팀원들의 개발 내용 추가/update
    + Static 페이지 지속적으로 
    +듀토리얼 페이지 자료조사 완료 및 작성
      
	14주차& 15주차:
    • 프로젝트 최종 Wrap-up
    • 프로젝트 진행 상황을 문서화하여 커뮤니티에 기여 및 피드백
    • 깃허브 페이지 지속적으로 관리 → 페이지 공유를 통한 커뮤니티의 기여
    + 듀토리얼 페이지 최종본 확립 및 Wrap up
    + Static 페이지 최종본 확립 및 Wrap up
    
    
    * "+"이 개인별 계획을 의미
```
