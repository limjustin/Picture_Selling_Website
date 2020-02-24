<<<<<<< HEAD
# Node.js 풀 스택 오픈소스 학습 프로젝트, Codeasy(코드이지)  

_본 프로젝트는 컴퓨팅 전문 지식이 부족한 일반인이나 학생들도 기본적인 기술들을 유연하게 활용해서 웹 어플리케이션을 이해하고 개발 할 수 있도록 하는데 목적이 있습니다._

- [설치 & 구동](/docs/install&run.md)
  - [프로젝트 구조](/docs/project_structure.md)
- [템플릿 기초 - 첫 페이지 만들기](/docs/template_basic.md)
  - [HTML 기초 - 기본 요소와 속성](/docs/html_basic.md)
  - [데이터베이스 기초 - 몽고DB 생성/조회/수정/삭제](/docs/mongodb_basic.md)
- [템플릿 활용 - 템플릿에 데이터 전달](/docs/template_basic2.md)
  - [CSS 기초 - 부트스트랩]
- [새 페이지 만들기 - 라우팅](/docs/routing.md)


## 핵심 기술만을 사용합니다. 따라서 쉽고도 강력합니다.
학습의 초기단계부터 프레임워크를 복잡하게 설정하는 것부터 시작하는 것은 매우 비효율 적입니다. 따라서 일반적으로 사용되면서도 유연한 기본 환경을 바탕으로 두고, 단계별로 필요한 구성을 이해하면서 진행하는 것이 전체적인 학습에 도움이 됩니다.

본 프로젝트는 다음과 같이 가장 유명하고도 검증 된 기술들의 유연하고도 강력한 조합으로 이루어져 있기 때문에, 기본과 핵심에만 집중한 학습을 할 수 있습니다. 

- 백엔드/Server: 강력한 서버 플랫폼. [Node.js](https://nodejs.org/)
  - 데이터베이스/DB: 데이터(JSON) 및 파일도 저장. [MongoDB](https://www.mongodb.com/)
  - 클라우드/OS: Azure / EC2 / nCloude ...
- 프론트엔드/Client: HTML을 그대로 사용하는 {{ Template }} 엔진. [Template](http://blazejs.org/)
  - CSS/LESS: 심플 한 여백의 미학. [Bootsttrap](https://getbootstrap.com/docs/4.3/examples/)

각 기술들이 가장 기본적인 요소들을 사용한다는 의미는, 별도의 기술이나 새로운 개념을 통해 보다 쉬운 프로그래밍을 유도하는 것이 아닌, HTML / CSS / Javascript 등 프로그래밍 언어를 가장 기초적인 수준에서 적용하였음을 뜻하며, 사용자의 지식이 향상 됨에 따라 스스로 점점 고차원적인 구성을 스스로 만들어 낼 수 있음을 뜻 합니다. 따라서 Codeasy 프로젝트를 학습한다는 것은 셀 수 없이 쏟아지는 여타 프레임워크들을 학습하는 것이 아닌, 가장 기본적인 학습을 통해 고급 프로그래밍을 이해해 나가는 과정이라고 할 수 있습니다. 

## 풀스택 자바스크립트 오픈소스 플랫폼, [Meteor](https://www.meteor.com/)
이렇듯 핵심적인 여러 기술들은 오픈소스 플랫폼 Meteor의 마술과도 같은 유연한 구조를 통해, 타 자바스크립트 프레임워크들에 비해 웹 어플리케이션의 설치/구현/구동 전체를 상상 할 수 없을 만큼 쉽게 만들어 줍니다. 뿐만 아니라 Meteor는, 리액티브(Reactive)와 같은 뛰어난 기능을 내장하고 있고 및 Node.js NPM 저장소에 등록 된 수 많은 패키지들을 자유롭게 사용 할 수 있기 때문에 학습 뿐만 아니라 상업용 프로젝트로도 이미 전세계에서 수 없이 활용 되고 있는 강력한 플랫폼입니다.([ShowCase](https://www.meteor.com/showcase)

### 이해하고 만들기? vs 만들면서 이해하기!
본 프로젝트는 환경 설정에 시간을 들일 필요가 전혀 없습니다. 사용 프레임워크들의 환경 설정 뿐 아니라 부트스트랩 공식 화면 샘플들을 이미 모두 포함하고 있기 때문에 즉시 참조 및 적용이 가능하게 구성되어 있습니다. 우선 만들고 나면, 이해는 따라 옵니다.
- Bootstrap 공식 샘플: Album / Pricing / Checkout / Product / Cover / Carousel / Blog / Dashboard / History ...
  + font-awesome 등 필수 패키지 

또한 다음과 같이 서버/DB를 활용한 주요 기능 구현에 필요한 대부분의 샘플들 또한 상세한 설명과 함께 포함되어 있기 때문에 즉시 응용 할 수 있습니다. 배웠다고 모든 사람이 바로 응용 할 수 있는 것은 아닙니다. 막막한 응용 기능들, 기본을 반복해서 확장 해 나갑니다.
- 회원가입 / 로그인 / 게시판 작성/수정/삭제 / 데이터 저장/변경/검색/삭제 / 이미지(파일) 업로드/다운로드 및 서비스 / WYSIWYG 에디터 ...

### 원하는 만큼만 배운다.
코스 별 학습을 통해 원하는 수준까지 학습합니다. 모든 사람이 풀 스택 개발자가 될 필요는 없습니다. 시스템의 기초적인 이해와 개인 프로젝트 정도만을 목표로 한다면 Basic 코스를, 풀스택 개발자를 목표로 한다면 주요 SNS와 같은 핵심 사이트들을 직접 구현 해 볼 수 있도록 최종 소스코드 및 API / 개발 메뉴얼 등을 제공하여 스스로 풀스택 과정을 경험 해 볼 수 있도록 합니다.

- Basic 코스: 기본 웹 프로젝트의 이해를 통해 로그인/게시판 등이 있는 간단한 홈페이지 구축
- Advanced 코스: 외부 패키지 사용 및 데이터 기능 확장을 통해 웹 시스템 전반을 이해
- Full Stack 코스: 미니 페이스북, 미니 인스타그램 등의 구현을 통해 풀 스택 개발을 이해

** Codeasy는 학술/대학/기업/공공기관 등과 연계하여 오프라인 수업 과정을 통해 학습자들이 웹 기본 기술에 이어 풀 스택 개발을 이해 할 수 있도록 직접 지원합니다. (별도 공지 예정)

The fastest way to build an app, 
Codeasy.org with Meteorjs.



=======
# Picture-Selling-Site
>>>>>>> 875c0ab1e595dcb4a2163c8846eab7b34018c866
