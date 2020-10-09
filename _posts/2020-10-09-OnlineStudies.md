---
layout: post
title: "Online Sampling & Psychology Experiments"
author: "Yoon Kyung Lee"
tags: Experiments
---

COVID-19의 확산이 지속됨에 따라 심리학계에도 실험 패러다임 전환의 시기가 찾아온 듯 하다. 심리학 연구에 쓰이는 설문/실험은 원래 크게 온라인과 오프라인으로 나뉜다. 온라인은 우리가 보통 아는 자가보고식의 형태의 인지 능력 검사, 주의력 검사, 우울증 검사 등이 있다. 오프라인에서 실험할때는 컴퓨터에 제시된 화면에 나온 내용을 읽고 빠르게 반응 (키보드의 키를 누르거나 마우스 클릭, 또는 터치), 아이트래킹을 통해 눈의 운동과 시선을 추적, 또는 뇌파를 측정하는 등 다양한 도구를 사용했다. 

코로나로 인해 대면 실험이 어려워져서 많은 연구자들이 온라인으로 실험을 진행하고 있다. 그 중 유용하고 많이 쓰이는 설문 플랫폼과 (인지)측정 검사도구를 기본으로 제공하는 사이트 몇개를 정리해보았다. 

설문: 

- Google Forms
- Typeform
- SurveyMonkey

좀 더 복잡하고 맞춤화가 가능한 행동 실험 설계를 하고 싶다면, 

- [Qualtrics](https://www.qualtrics.com/)
- [Gorilla](https://gorilla.sc/) (특히 반응 시간이 중요하다면)
- [Inquisit Web](https://www.millisecond.com/products/inquisit5/weboverview.aspx)

이 외에 직접 오픈소스 (PsychoPy, PsychJS)를 사용해서 직접 개발하는 방법도 있다. 파블로비아(Pavlovia.org)등의 플랫폼에서 연동해서 사용 가능하다.  

랩에서는 고릴라를 주로 쓰고 있다. 인지 심리 실험 특성상 반응 시간과 정확도를 둘 다 잘 측정할 수 있는 도구가 필요하기 때문이다. Gorilla에서는 N-back, IAT, 죄수의 딜레마 등의 유명한 인지능력측정 검사도구를 템플렛으로 제공하기에, 빈 페이지에서 시작할 필요가 없어서 좋다. 

[Prolific 블로그](https://blog.prolific.co/so-you-want-to-run-an-online-experiment/)에 따르면 Millisecond사의 Inquisit Web은 아이트래킹, 마우스트래킹 등의 다중 입력 방법들도 지원한다고 한다 (치매, 뇌경색 등으로 인한 인지 능력 저하의 수준을 측정할때 많이 쓰는 cognitive assessment battery등을 제작하고 싶을때 유용할 듯 하다) 

고릴라에 대해서는 이후 포스트에서 조금 더 다룰까 한다. 

-YK




___
