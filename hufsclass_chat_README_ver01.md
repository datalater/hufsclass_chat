독자  
- 옐로아이디로 자동응답 API를 구성해보고 싶은 사람  
- 기술이 없더라도 챗봇에 대해 알고 싶은 사람  

## Part I. 챗봇이란 무엇인가? ##

### 1. 챗봇의 정의 ###

사람과 소통하며 서비스를 제공하는 소프트웨어

### 2. 챗봇이 화두로 떠오른 배경 ###
#### __모바일 앱 DOWN ####
현재 우리는 모바일 시대에 살고 있고 그만큼 모바일은 가장 중요한 ICT 패러다임 중 하나입니다. 일상생활은 모바일에 맞게 재편되고 있고 그 안에는 모바일 앱이라는 유형의 서비스가 자리잡고 있습니다. 

그러면 이러한 현상이 앞으로도 꾸준히 지속될까요?

![슬라이드5_모바일앱](https://github.com/datalater/hufsclass_chat/blob/master/images/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C5.PNG?raw=true)

모바일 앱 시장을 살펴보면 그럴 것 같지 않습니다. 앱 시장은 이미 포화상태입니다. 그러다 보니 앱 개발 비용뿐만 아니라 만든 앱을 알리고 홍보하는 마케팅 비용은 점점 더 늘어날 수밖에 없겠죠. 그런데 문제는 새로운 앱을 설치하는 사용자들이 매우 적다는 겁니다. 설치하더라도 사용하지 않고 묵혀두는 앱도 많죠. 

정리하면, 모바일 시대에 진입했지만 모바일 앱 시장은 이미 포화상태이고 미래가 밝지 않습니다. 그러면 모바일 앱 이후의 NEXT 패러다임은 무엇일까요?

#### __What is the NEXT? ####

모바일 생태계에서 사람들이 가장 많이 하는 행동을 살펴보면 힌트를 얻을 수 있습니다.

![스마트폰으로주로무엇을하나](https://github.com/datalater/hufsclass_chat/blob/master/images/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C7.PNG?raw=true)

통계조사에서도 말하고 있지만 굳이 멀리 찾지 않아도 저나 여러분 또한 카카오톡 같은 메신저 앱을 가장 많이 사용할 겁니다. 이때 챗봇이 우리 회사의 미래다, 라고 선언한 CEO가 있습니다. 누굴까요?

![페이스북의미래_챗봇](https://github.com/datalater/hufsclass_chat/blob/master/images/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C8.PNG?raw=true)

그는 페이스북의 10년 후 로드맵을 발표하는 자리에서 새로 개발한 기술에 대해 다음과 같이 말했습니다. 

> *We announced new technology like Messenger bots that use artificial intelligence to make it easier to communicate with businesses.*

'인공지능(AI) 기술을 활용해서 사업자의 소통을 원활하게 만들어주는 메신저 봇', 바로 챗봇입니다. 붉은색으로 포화된 모바일 시장을 표현한 그림 기억나시나요? 챗봇은 기존 메신저 앱의 새로운 서비스이지 새로운 앱이 아니기 때문에 포화된 시장에 새로 진입하거나 경쟁할 필요가 없습니다. 

![4th industrial revolution](https://github.com/datalater/hufsclass_chat/blob/master/images/4th%20industrial%20revolution.jpg?raw=true)

이러한 장점뿐만 아니라 챗봇은 다가오고 있는 4차 산업혁명과도 맞닿아 있습니다. 모바일 생태계에서 사람들이 가장 많은 시간을 보내는 메신저 앱이 4차 산업혁명의 핵심 기술인 AI를 만나 진화한 셈이기 때문입니다. 기계가 사람과 소통하려면 사람의 말을 알아듣고 반응할 줄 알아야 합니다. 때로는 먼저 말을 걸 수도 있겠죠. 이렇게 기계가 사람과 소통할 수 있도록 도와주는 인공지능 기술을 자연어처리(NLP, Natural Language Processing)라고 합니다. 자연어처리 기술이 발달할 수록 인간과 기계의 소통은 더욱 매끄러워질 것입니다. 따라서 챗봇과 인공지능 기술은 불가분의 관계에 있는 것이죠. 

![ICT패러다임챗봇UP](https://github.com/datalater/hufsclass_chat/blob/master/images/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C10.PNG?raw=true)

지금까지의 내용을 정리하면, 포화상태의 모바일 앱 시장에 대한 새로운 ICT 대안으로 챗봇이 떠오르고 있는 것입니다. 

### 3. 챗봇으로 할 수 있는 일  ###

![챗봇활용분야](https://github.com/datalater/hufsclass_chat/blob/master/images/chatbot_%ED%99%9C%EC%9A%A9%EB%B6%84%EC%95%BC_NIA.png?raw=true)

> 출처: 한국정보화진흥원. "인공지능 기반의 '챗봇(ChatBot)' 서비스 등장과 발전 동향"

그러면 과연 챗봇으로 대체 어떤 일을 할 수 있길래 글로벌 기업들이 미래 기술로 인정하고 개발하고 있을까요? 가장 활발하게 진행되고 있는 분야는 대화형 커머스 및 O2O입니다. 메신저 앱에서 상품을 고르고 주문하고, 추천 상품도 받고, 식당에 가기 전 미리 예약하고 메뉴를 주문해둘 수도 있습니다. 이외에도 정보를 알려주는 개인비서 서비스, 전문지식이 필요하거나 절차가 복잡한 공공정보에 대한 접근성을 향상시키는 공공 서비스 등이 있습니다. 메신저 앱은 사용자와 기업을 쉽고 편리하게 연결해주기 때문에 다양한 분야에서 활용될 수 있고 산업 전반에 새로운 부가가치를 창출할 것으로 전망됩니다.

### 4. 사례로 알아보는 챗봇 서비스 ###

말로는 정확히 어떤 느낌인지 체감하기 쉽지 않습니다. 그래서 위에서 이야기 했던 서비스 중에서 실제 사례를 찾아보던 중 가장 매력적이었던 챗봇 서비스를 소개하고자 합니다. 

## 참고문헌 ##
1. 한국정보화진흥원(NIA). "인공지능 기반의 '챗봇(ChatBot)' 서비스 등장과 발전 동향". ICT융합의 Issues & Trends. 2016.08
2. The Guardian, "How Facebook plans to take over the world". 2016.04
3. Reuters, "Facebook's next frontier: chatbots". 2016.04