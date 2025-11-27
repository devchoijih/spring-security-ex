# 🔐 spring-security-ex

Spring Security의 인증(Authentication)과 인가(Authorization) 구조를 직접 구현하고 흐름을 이해하기 위한 예제 프로젝트입니다.  
기본적인 Controller 기반 요청 처리부터, Security 설정 확장까지 학습 및 실험용으로 구성되어 있습니다.

---

## 🎯 목적

- Spring Security 필터 체인 구조 이해
- 기본 로그인 / 인증 흐름 학습
- URL 접근 제어 인가 구조 실습
- 향후 실전 프로젝트에 적용 가능한 보안 구조 기반 마련

---

## 📁 현재 프로젝트 구조

현재 저장소는 다음과 같이 최소 구조만 갖춘 상태입니다.

```text
spring-security-ex/
 ├─ settings.gradle
 └─ src/
     └─ main/
         └─ java/
             └─ com/
                 └─ example/
                     └─ controller/
                         ├─ MainController.java
                         └─ ... (요청 처리용 컨트롤러 클래스)
