## 1\. 사건 개요
 
### 2026년 4월 말~5월 초

### Canvas 관련 보안 사고 발생

4월 29일, Instructure에서 Canvas에서의 무단 활동을 감지했다. ([Instructure](https://www.instructure.com/incident_update))

5월 초, Canvas LMS를 운영하는 Instructure는 Canvas와 관련된 보안 사고를 확인했다.

Instructure는 이 사고가 자사 환경의 일부에 대한 무단 접근과 관련되어 있으며, 영향을 받은 데이터에는 다음과 같은 정보가 포함될 수 있다고 밝혔다.

-   사용자 이름
-   이메일 주소
-   강좌 이름
-   수강 등록 정보
-   사용자 간 메시지

반면 Instructure는 다음 정보는 침해되지 않았다고 설명했다.

-   수업 콘텐츠
-   과제 제출물
-   로그인 자격 증명
-   비밀번호
-   생년월일
-   정부 발급 신분증 번호
-   금융 정보

Instructure는 공식 사고 업데이트에서 “core learning data”, 즉 수업 콘텐츠, 제출물, 자격 증명은 침해되지 않았다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

### 2026년 5월 3일 전후

### ShinyHunters의 공격 주장

Reuters에 따르면, 해킹 그룹 ShinyHunters는 2026년 5월 3일 자신들이 Instructure의 Canvas 플랫폼에서 데이터를 훔쳤다고 주장했다.  
ShinyHunters는 약 9,000개 학교와 관련된 학생 이름, 이메일 주소, 메시지 등을 보유하고 있다고 주장했다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

다만 이 피해 규모는 공격자의 주장에 포함된 내용이므로, 실제 전체 규모가 독립적으로 모두 검증된 것은 아니다. AP News도 ShinyHunters가 약 9,000개 학교와 2억 7,500만 명의 데이터를 언급하며 협박했다고 보도했지만, 이는 공격자의 주장과 Instructure의 대응 내용을 함께 다룬 것이다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))

### 2026년 5월 6일

### Instructure의 정상화 언급

Reuters 보도에 따르면, Instructure는 2026년 5월 6일 상태 메시지를 통해 상황이 해결되었고 Canvas 플랫폼이 완전히 운영 중이라고 밝혔다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

그러나 이후 다시 무단 활동이 발생했다.

### 2026년 5월 7일

### Canvas 로그인 포털 변조

2026년 5월 7일, 여러 학교의 Canvas 로그인 화면에 ShinyHunters의 협박성 메시지가 표시되었다.

The Hacker News는 2026년 5월 7일 같은 사건과 관련된 두 번째 무단 활동이 탐지되었고, 약 330개 기관의 Canvas 로그인 포털에 협박 메시지가 표시되었다고 보도했다. 해당 메시지는 Instructure가 2026년 5월 12일까지 협상하지 않으면 데이터를 유출하겠다는 내용을 담고 있었다. ([The Hacker News](https://thehackernews.com/2026/05/instructure-reaches-ransom-agreement.html))

BleepingComputer도 ShinyHunters가 2026년 5월 7일 같은 취약점을 다시 이용해 Canvas 로그인 포털을 변조하고 협박 메시지를 남겼다고 보도했다. ([BleepingComputer](https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/))

### 이후 Canvas 일시 중단 및 복구

Reuters에 따르면, 학생들이 ShinyHunters의 메시지를 확인한 뒤 Instructure는 Canvas를 몇 시간 동안 오프라인 상태로 전환했고, 이후 서비스를 복구했다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

### 2026년 5월 12일

### Instructure와 ShinyHunters의 합의 발표

2026년 5월 12일, Reuters는 Instructure가 ShinyHunters와 합의에 도달했다고 보도했다.

Instructure는 합의 결과 다음과 같은 내용을 전달받았다고 밝혔다.

-   훔친 데이터가 Instructure에 반환됨
-   데이터가 삭제되었다는 디지털 확인을 받음
-   Instructure 고객들이 추가로 협박받지 않을 것이라는 통보를 받음
-   개별 고객이 ShinyHunters와 따로 접촉할 필요는 없음

Reuters는 ShinyHunters 측도 Reuters에 “데이터는 삭제되었고, 회사와 고객은 추가로 표적이 되거나 금전 요구를 받지 않을 것”이라고 말했다고 보도했다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

다만 Instructure는 합의의 구체적인 조건이나 금전 지급 여부를 공개하지 않았다. AP News는 Instructure가 “데이터가 완전히 삭제되었는지를 확실히 보장할 방법은 없다”고 인정했다고 보도했다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))


---

## 2\. 배경, 원인

## 2.1. Canvas

Canvas는 Instructure가 운영하는 웹 기반 학습관리시스템이다.

Canvas 기반 LMS는 미국 대학교에서 주로 사용되는 플랫폼이며, 고려대학교에서 사용하는 Learning X 또한 Canvas 기반이다.

Canvas에서 주로 사용되는 기능은 다음과 같다.

-   수업 자료 제공
-   과제 제출
-   퀴즈 및 시험
-   성적 확인
-   교수와 학생 간 메시지
-   수업 공지
-   토론 게시판

AP News는 Canvas가 성적 관리, 디지털 강의 자료, 과제, 메시지, 시험, 최종 프로젝트 제출 등에 사용되는 플랫폼이라고 설명했다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))

따라서 Canvas는 단순한 게시판이나 보조 도구가 아니라, 많은 학교에서 실제 수업 운영에 직접 연결된 시스템이다.

## 2.2. ShinyHunters

ShinyHunters는 여러 기업과 기관을 대상으로 데이터 탈취 및 협박을 해 온 해킹 그룹으로 알려져 있다.

Reuters는 ShinyHunters를 “글로벌 기업을 대상으로 협박을 해 온 이력이 있는 해킹 그룹”이라고 설명했다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

Canvas 사건에서도 ShinyHunters는 자신들이 데이터를 훔쳤다고 주장했고, Instructure 및 관련 학교들을 상대로 데이터 유출을 압박했다.

## 2.3. 기술적 배경

### Free-for-Teacher 환경

Free-for-Teacher는 개별 교사가 무료로 사용할 수 있는 Canvas 계정 환경이다.  
미국 교육부 Federal Student Aid의 보안 경고는 Free-for-Teacher 계정을 “enterprise-managed environments”, 즉 기관이 중앙에서 관리하는 환경 밖에서 흔히 사용되는 무료 Canvas 계정 유형이라고 설명했다. ([FSA Partner Connect](https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system))

Instructure는 공식 사고 업데이트에서 공격자가 Free-for-Teacher 계정과 관련된 문제를 이용했다고 밝혔다. 또한 Free-for-Teacher 서비스를 일시적으로 중단했다고 설명했다. ([Instructure](https://www.instructure.com/incident_update))

### 2.3.1. 지원 티켓 시스템

Instructure는 공식 사고 업데이트에서 Free-for-Teacher 환경의 support tickets, 즉 지원 티켓과 관련된 취약점이 악용되었다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

지원 티켓 시스템은 사용자 입력을 많이 받기 때문에 보안상 주의가 필요하다. 사용자 입력값이 적절히 검증되지 않거나, 관리자 화면에서 안전하게 처리되지 않으면 공격자가 악성 스크립트나 조작된 데이터를 넣을 수 있다.

지원 티켓 시스템은 사용자가 서비스 이용 중 발생한 문제를 문의하고, 운영자나 지원 담당자가 그 문의를 처리하기 위해 사용하는 시스템이다.

예를 들어 사용자가 로그인 오류, 계정 문제, 수업 접근 문제, 과제 제출 오류 등을 문의하면 하나의 “티켓”이 생성된다. 지원 담당자는 관리자 화면에서 해당 티켓을 확인하고 답변하거나 필요한 조치를 진행한다.

지원 티켓 시스템이 보안적으로 중요한 이유는 다음과 같다.

-   외부 사용자의 입력이 내부 관리자 화면에 표시될 수 있음
-   문의 내용에 링크, 첨부파일, HTML 형식의 내용이 포함될 수 있음
-   지원 담당자가 높은 권한을 가진 계정으로 티켓을 확인할 수 있음
-   티켓 시스템이 사용자 정보나 계정 관리 기능과 연결되어 있을 수 있음

### 2.3.2. XSS ( Cross-Site Scripting)

BleepingComputer는 Instructure가 자세한 기술 내용을 공개하지는 않았지만, 공격자가 여러 개의 XSS 취약점을 악용한 것으로 파악했다고 보도했다. 또한 공격자가 사용자 생성 콘텐츠 기능에 악성 JavaScript를 삽입해 인증된 관리자 세션을 얻고 권한 있는 작업을 수행했다고 설명했다. ([BleepingComputer](https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/))

XSS는 웹사이트가 사용자의 입력값을 충분히 검증하거나 이스케이프 처리하지 않고 페이지에 출력할 때, 공격자가 JavaScript 코드를 삽입할 수 있는 취약점이다.

예를 들어 사용자가 게시글, 댓글, 문의 내용에 다음과 같은 HTML 스크립트를 넣었다고 가정할 수 있다.

```
<script>
  // 악성 JavaScript 코드
</script>
```

웹사이트가 이 내용을 단순한 글자로 처리하지 않고 실제 HTML/JavaScript로 실행해버리면, 다른 사용자의 브라우저에서 공격자의 코드가 실행된다.

XSS가 위험한 이유는 다음과 같다.

-   로그인한 사용자의 브라우저에서 악성 코드가 실행될 수 있음
-   세션 정보나 토큰이 악용될 수 있음
-   사용자 대신 요청을 보내는 동작이 가능할 수 있음
-   관리자 계정에서 실행되면 더 높은 권한의 작업으로 이어질 수 있음
-   화면 변조, 피싱 페이지 삽입, 데이터 접근 시도에 사용될 수 있음

### 2.3.3. 인증 세션

인증 세션은 사용자가 로그인한 상태를 서버가 기억하기 위해 사용하는 정보이다.

웹서비스에서는 사용자가 페이지를 이동할 때마다 아이디와 비밀번호를 다시 입력하지 않는다. 대신 로그인에 성공하면 서버는 세션을 만들고, 이후 요청에서 이 세션을 확인해 사용자가 이미 로그인한 상태인지 판단한다.

일반적인 로그인 과정은 다음과 같다.

1.  사용자가 아이디와 비밀번호를 입력한다.
2.  서버가 로그인 정보를 확인한다.
3.  로그인에 성공하면 서버가 세션을 생성한다.
4.  브라우저는 세션 정보를 쿠키 등에 저장한다.
5.  이후 요청마다 세션 정보가 함께 전송된다.
6.  서버는 세션을 보고 로그인된 사용자라고 판단한다.

인증 세션은 로그인 상태를 증명하는 값처럼 사용되므로 세션이 탈취되면 비밀번호를 몰라도 로그인된 사용자처럼 행동할 수 있다. 관리자 세션이 악용되면 일반 사용자 세션보다 피해가 커질 수 있고, 오래 유지되거나 보호 설정이 부족하면 위험이 커질 수 있다.

### 2.3.4. MFA ( Multi-Factor Authentication, 다중 인증)

사용자가 로그인할 때 비밀번호 하나만 사용하는 것이 아니라, 두 가지 이상의 인증 요소를 함께 사용하는 방식이다.

일반적인 로그인은 아이디 + 비밀번호로 이루어지고, MFA가 적용된 로그인은 여기에 추가 인증 요소가 붙는다.

추가 인증 수단의 예시는 다음과 같다.

-   휴대폰 인증 앱의 일회용 코드
-   문자 인증번호
-   이메일 인증
-   보안 키
-   지문이나 얼굴 인식 같은 생체 인증

MFA를 사용하면 비밀번호가 유출되어도 추가 인증 없이는 로그인이 어려우므로 계정 탈취 가능성을 줄일 수 있다. 

### 2.3.5. 토큰과 권한

토큰은 사용자가 인증되었거나 특정 기능을 사용할 수 있음을 나타내는 값이다.  
웹서비스나 API에서는 사용자가 매번 비밀번호를 입력하지 않아도 되도록 토큰을 사용한다.

예를 들어, 사용자가 로그인하면 서버는 access token과 같은 값을 발급할 수 있다. 이후 사용자가 데이터를 요청하거나 기능을 사용할 때, 서버는 함께 전달된 토큰을 확인하고 요청을 허용할지 판단한다.

권한은 사용자가 시스템 안에서 어떤 작업을 할 수 있는지를 정하는 기준이다.

예를 들어, LMS 시스템에서는 계정에 따라 다른 권한이 주어질 수 있다.

-   학생 계정: 자신의 과제, 성적, 수업 정보를 확인할 수 있음
-   교수 계정: 수업 자료를 올리거나 과제를 확인할 수 있음
-   관리자 계정: 여러 사용자 정보나 시스템 설정에 접근할 수 있음

토큰이 노출되면 비밀번호 없이도 요청을 보낼 수 있으므로 사용자가 필요한 범위 이상의 권한을 가지면 사고 발생 시 피해가 확산될 수 있다.

## 2.4. 구조적 원인

이 사건의 구조적 원인은 Canvas 같은 SaaS 기반 교육 플랫폼의 특성과 관련된다.

### 여러 기관이 하나의 플랫폼에 의존

Canvas는 여러 학교와 대학이 공통으로 사용하는 플랫폼이다.  
따라서 한 학교의 내부 시스템만 침해된 것이 아니라, 여러 기관이 사용하는 공통 플랫폼에서 문제가 발생했다.

이 경우 사고 범위가 넓어질 수 있다.

-   한 플랫폼 장애가 여러 학교의 수업에 영향을 줄 수 있음
-   한 플랫폼의 데이터 유출이 여러 기관의 사용자 정보 유출로 이어질 수 있음
-   공격자는 개별 학교를 하나씩 공격하지 않고도 공통 플랫폼을 통해 더 넓은 영향을 노릴 수 있음

### 무료·부가 서비스와 핵심 서비스의 연결

Free-for-Teacher는 기관 단위로 관리되는 정식 엔터프라이즈 환경과 다르게, 개별 교사들이 무료로 사용하는 계정 유형이다. 미국 교육부 Federal Student Aid는 이 사건이 MFA(다중 인증)이 없는 계정의 높은 위험을 보여준다며, 행정 시스템, 클라우드 시스템, 벤더 플랫폼, 학교 정보 시스템에 MFA를 일관되게 적용하라고 권고했다. ([FSA Partner Connect](https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system))

즉, 구조적으로는 다음과 같은 문제가 드러난다.

-   무료 계정 환경도 전체 플랫폼 보안에 영향을 줄 수 있음
-   기관 관리 밖의 계정이 공격 경로가 될 수 있음
-   지원 티켓처럼 부가적인 기능도 공격 표면이 될 수 있음
-   사용자 입력을 받는 기능은 핵심 서비스가 아니더라도 보안 검증이 필요함

---

## 3\. 대응

## 3.1. 대응 과정

### 사고 인지 후 조사

Instructure는 사고 이후 무단 접근을 조사했고, 영향을 받은 데이터 범위를 확인하고 있다고 밝혔다.

공식 사고 업데이트에 따르면 Instructure는 다음 작업을 진행했다.

-   포렌식 분석
-   사이버 보안 태세 개선
-   관련 데이터에 대한 종합 검토
-   Free-for-Teacher 환경의 보안 검토
-   Free-for-Teacher 서비스 임시 중단

Instructure는 공식 업데이트에서 Free-for-Teacher 환경의 지원 티켓 관련 취약점이 악용되었고, 전체 보안 검토를 위해 Free-for-Teacher를 일시적으로 비활성화했다고 설명했다. ([Instructure](https://www.instructure.com/incident_update))

### 2026년 5월 7일 이후 Canvas 일시 중단

Reuters는 2026년 5월 7일 학생들이 ShinyHunters의 메시지를 발견한 뒤 Instructure가 Canvas를 몇 시간 동안 오프라인으로 전환하고 이후 복구했다고 보도했다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

Instructure는 예방 차원에서 활동을 차단하고 조사 및 추가 보안 조치를 적용하기 위해 Canvas를 일시적으로 유지보수 모드로 전환했다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

### Free-for-Teacher 임시 중단

Instructure는 공격자가 Free-for-Teacher 계정을 이용해 두 차례 활동을 수행한 것으로 확인했고, 그 결과 Free-for-Teacher 제품을 일시적으로 중단했다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

미국 교육부 Federal Student Aid도 Instructure가 Free-for-Teacher 계정과 서비스를 임시로 중단했다고 안내했다. ([FSA Partner Connect](https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system))

### 권한 및 토큰 관련 조치

The Hacker News는 Instructure가 다음과 같은 조치를 했다고 보도했다. ([The Hacker News](https://thehackernews.com/2026/05/instructure-reaches-ransom-agreement.html))

-   영향을 받은 시스템의 privileged credentials 회수
-   access token 회수
-   내부 키 회전
-   토큰 생성 경로 제한
-   추가 보안 통제 배포

### 2026년 5월 12일 합의 발표

Reuters에 따르면 Instructure는 ShinyHunters와 합의에 도달했다고 밝혔다. 합의 내용에는 데이터 반환, 데이터 삭제에 대한 디지털 확인, 고객 대상 추가 협박 중단이 포함되었다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

AP News는 Instructure가 “shred logs” 형태의 디지털 확인을 받았다고 보도했다. 다만 Instructure는 데이터가 영구히 삭제되었는지 완전히 확신할 수는 없다고 인정했다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))

## 3.2. 문제점

Instructure에서는 사건이 해결되었고 Canvas가 완전히 복구되어 사용하기에 안전하다고 안내한다.

그러나 사건의 특성상 이후에 영향을 줄 수 있는 문제점이 있다.

### 데이터 삭제를 완전히 검증하기 어려움

AP News에 따르면 Instructure는 해커로부터 데이터 삭제 확인을 받았지만, 데이터가 완전히 삭제되었는지는 확실히 보장할 방법이 없다고 인정했다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180)) 이는 데이터 탈취형 협박 사건의 일반적인 문제이다. 

-   공격자가 복사본을 남겼는지 확인하기 어려움
-   데이터가 제3자에게 이미 전달되었는지 확인하기 어려움
-   삭제 로그가 실제 삭제를 완전히 증명하기 어려움
-   합의 이후에도 피싱이나 사칭 공격 가능성이 남음

또한, 금전 지급 여부와 합의 조건이 명확히 공개되지 않았다. Reuters는 Instructure가 합의 조건과 금전 지급 여부를 공개하지 않았다고 보도했다.  
  

### 고객과 사용자 입장에서 불확실성이 남음

Instructure는 일부 데이터가 유출되었고, 일부 핵심 학습 데이터는 침해되지 않았다고 밝혔다. 그러나 사용자 입장에서는 다음과 같은 불확실성이 남는다.

-   내 정보가 정확히 포함되었는지
-   어떤 메시지가 유출되었는지
-   유출 데이터가 이후 피싱에 사용될 수 있는지
-   데이터가 실제로 완전히 삭제되었는지

AP News는 유출된 정보가 학생 ID, 이메일 주소, 이름, Canvas 메시지 등으로 보인다고 보도했다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))

### 같은 계열 사고가 반복된 점

BleepingComputer는 Instructure가 2025년 9월에도 ShinyHunters가 주장한 다른 침해 사고를 공개한 바 있다고 보도했다.([BleepingComputer](https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/))

같은 조직과 같은 공격 그룹이 반복적으로 언급되었다는 점에서 사고 대응과 보안 관리의 지속성이 중요하다고 할 수 있다.

---

## 4\. 영향

### 개인정보 유출 가능성

Instructure와 AP News 보도 기준으로, 유출 가능성이 언급된 정보는 다음과 같다.

-   이름
-   이메일 주소
-   학생 ID 번호
-   Canvas 내 메시지
-   강좌 이름
-   수강 등록 정보

Instructure는 수업 콘텐츠, 제출물, 자격 증명은 침해되지 않았다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

### 교육 활동 차질

AP News는 이로 인해 기말고사 기간 중 Canvas에 의존하던 학생과 교직원이 혼란을 겪었다고 보도했다. Canvas는 성적 관리, 강의 자료 접근, 과제 제출, 시험, 교수와 학생 간 메시지 등에 사용되기 때문에 접속 장애가 교육 활동에 직접 영향을 주었다. ([AP News](https://apnews.com/article/3d55b9399ae87d49276f354e1c34c180))

-   수업 자료 접근 지연
-   과제 제출 지연
-   시험 및 퀴즈 진행 차질 가능성
-   성적 확인 지연
-   교수와 학생 간 연락 차질

### 피싱 및 사칭 공격 가능성

The Hacker News는 보안 업체 Halcyon의 의견을 인용해, 유출된 데이터가 학생, 교직원, 학부모를 대상으로 한 표적 피싱에 충분한 개인적 맥락을 제공할 수 있다고 보도했다. 또한 공격자가 학교 관리자, IT 지원팀, 재정 지원 부서를 사칭할 수 있다고 설명했다. ([The Hacker News](https://thehackernews.com/2026/05/instructure-reaches-ransom-agreement.html))

이 영향은 실제 비밀번호나 금융정보가 유출되지 않았더라도 중요하다.  
이름, 이메일, 수업 정보, 메시지 내용이 결합되면 더 그럴듯한 사칭 메시지를 만들 수 있기 때문이다.

### 공공기관 차원의 관심

Reuters는 미국 하원 국토안보위원회가 Instructure CEO 또는 고위 임원에게 브리핑을 요청했다고 보도했다. 요청 내용에는 침해 사고, 도난 데이터의 성격과 양, 회사의 대응, 연방 법 집행기관 및 CISA와의 협조 적절성 등이 포함되었다. ([Reuters](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/))

이는 이 사건이 단순히 한 회사의 장애가 아니라, 교육기관 다수가 의존하는 플랫폼의 보안 사고로 다뤄졌음을 보여준다.

---

## 5\. 대책

## 5.1. 회사 정책·구조적 차원

### Free-for-Teacher와 같은 별도 계정 환경 관리 강화

Instructure는 Free-for-Teacher 계정과 관련된 문제가 확인되자 해당 서비스를 임시 중단했다. ([Instructure](https://www.instructure.com/incident_update))

이 사건을 기준으로 정리할 수 있는 구조적 대책은 다음과 같다.

-   무료 계정 환경도 엔터프라이즈 환경과 분리하여 관리
-   무료 계정에서 전체 플랫폼에 영향을 줄 수 있는 권한 제한
-   지원 티켓, 문의 시스템 등 부가 기능의 보안 점검 강화
-   기관 관리 밖 계정의 위험도 평가
-   계정 유형별 접근 권한과 데이터 접근 범위 제한

### 사고 커뮤니케이션 개선

Instructure는 공식 업데이트에서, 사실 확인에 집중하는 동안 고객들이 일관된 업데이트를 필요로 했는데 충분히 소통하지 못했다는 취지로 설명했다. 이후 전용 Incident Update 페이지를 만들고, 포렌식 보고서 요약을 공유하겠다고 밝혔다. ([Instructure](https://www.instructure.com/incident_update))

이와 관련된 대책은 다음과 같다.

-   사고 발생 시 전용 공지 페이지 운영
-   확인된 사실과 미확인 사실 구분
-   영향 범위와 사용자 조치 사항 안내
-   학교·기관별 담당자와 연락 체계 유지
-   포렌식 결과 요약 공개

### 교육기관의 벤더 보안 관리

Canvas 같은 LMS는 학교 내부 시스템이 아니라 외부 SaaS 플랫폼이다. 따라서 학교는 플랫폼을 도입할 때 기능뿐 아니라 보안 관리 수준도 확인해야 한다.

## 5.2. 기술적 차원

### MFA 적용

미국 교육부 Federal Student Aid는 이 사건이 MFA가 없는 계정의 높은 위험을 보여준다고 설명하며, 교육기관에 다음 영역에 MFA를 일관되게 적용하라고 권고했다.

-   행정 및 IT 시스템
-   클라우드 시스템
-   벤더 플랫폼
-   신원 제공자
-   학교 정보 시스템
-   Canvas 계정

([FSA Partner Connect](https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system))

### XSS 방어

BleepingComputer가 보도한 것처럼 XSS가 관련되었다면, 기술적으로는 다음 대책이 필요하다. ([BleepingComputer](https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/))

-   사용자 입력값 검증
-   출력값 이스케이프 처리
-   HTML/JavaScript 삽입 제한
-   Content Security Policy 적용
-   관리자 페이지에서 사용자 생성 콘텐츠 격리
-   세션 쿠키에 HttpOnly, Secure, SameSite 속성 적용
-   관리자 세션 탈취 방지

### 지원 티켓 시스템 보안 강화

Instructure가 공식적으로 언급한 취약점은 Free-for-Teacher 환경의 지원 티켓 관련 취약점이다. ([Instructure](https://www.instructure.com/incident_update))

따라서 지원 티켓 시스템에는 다음 보안 조치가 필요하다.

-   첨부파일 검사, 입력값 필터링
-   티켓 내용 렌더링 시 스크립트 실행 방지
-   관리자 화면에서 사용자 입력 격리
-   지원 담당자 권한 최소화
-   티켓 시스템과 핵심 사용자 데이터 접근 분리
-   티켓을 통한 권한 상승 가능성 점검

### 이상 행위 탐지

대규모 데이터 탈취가 발생한 경우, 다음 행위를 탐지할 수 있어야 한다.

-   비정상적으로 많은 데이터 조회
-   짧은 시간 내 대량 다운로드
-   평소와 다른 위치에서 관리자 접근
-   Free-for-Teacher 계정의 비정상 권한 사용
-   지원 티켓 시스템을 통한 스크립트 실행 시도
-   API 호출량 급증

---

## 6\. 참고 자료

-   Instructure 공식 Security Incident Update & FAQs    
    [https://www.instructure.com/incident\_update](https://www.instructure.com/incident_update)

-   AP News, Data stolen from education platform Canvas is deleted in deal with hackers  
    [https://apnews.com/article/canvas-outage-college-students-exams-grades-3d55b9399ae87d49276f354e1c34c180](https://apnews.com/article/canvas-outage-college-students-exams-grades-3d55b9399ae87d49276f354e1c34c180)
-   Reuters, Canvas’ parent company reaches agreement with hacking group behind breach  
    [https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/](https://www.reuters.com/legal/litigation/canvas-parent-company-reaches-agreement-with-hacking-group-behind-recent-breach-2026-05-12/)

-   BleepingComputer, Instructure reaches ‘agreement’ with ShinyHunters to stop data leak  
    [https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/](https://www.bleepingcomputer.com/news/security/instructure-reaches-agreement-with-shinyhunters-to-stop-data-leak/)
-   The Hacker News, Instructure Reaches Ransom Agreement with ShinyHunters to Stop 3.65TB Canvas Leak  
    [https://thehackernews.com/2026/05/instructure-reaches-ransom-agreement.html](https://thehackernews.com/2026/05/instructure-reaches-ransom-agreement.html)
-   U.S. Department of Education Federal Student Aid, Technology Security Alert – Ongoing Cybersecurity Incident Involving the Canvas Learning Management System  
    [https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system](https://fsapartners.ed.gov/knowledge-center/library/electronic-announcements/2026-05-12/technology-security-alert-ongoing-cybersecurity-incident-involving-canvas-learning-management-system)
