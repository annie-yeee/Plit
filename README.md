# PLIT 🎮

> WebSocket 기반 실시간 리그 오브 레전드 매칭 플랫폼

롤을 잘 모르는 상태에서 용감하게 뛰어든 롤 매칭 플랫폼입니다.
전적 검색, 팀 매칭, 클랜 기능을 한 서비스에 통합했습니다.

---

## 🏆 성과
- 멀티캠퍼스 백엔드 개발자 과정 최종 프로젝트 **최우수상 (1등)**

---

## 🛠 기술 스택
| 분류 | 기술 |
|------|------|
| Language | Java 21 |
| Framework | Spring Boot 3, JPA |
| Database | MySQL |
| Infra | AWS EC2, AWS S3 |
| Frontend | Thymeleaf |
| Realtime | WebSocket |

---

## 👥 팀 구성
| 역할 | 인원 |
|------|------|
| Backend | 5명 |

---

## 담당 기능 (김우영)

### 🔍 전적 검색
- Riot API 연동 전적 검색 기능 전담
- Personal Key 호출 제한 환경에서 단계적 해결
  - 화면 로딩 시 필요 데이터 우선 호출
  - 검색된 유저 데이터 DB 캐싱으로 재호출 최소화
  - 정적 리소스 S3/static 분리 및 CDN 적용
  - Riot 업데이트 시간대 피한 스케줄링 자동 갱신 설계
- 전적 검색 페이지 Thymeleaf 화면 구현

**전적 검색**
<img width="800" alt="전적검색" src="https://github.com/user-attachments/assets/c4062d0c-5206-4cd6-b52a-395b80e1a421" />

**게임 상세 페이지**
<img width="604" height="603" alt="상세페이지자세히" src="https://github.com/user-attachments/assets/616ffdd9-c6b9-4731-bc7f-63102f1f3243" />

### 🚀 인프라 / 배포
- AWS EC2 배포 참여
- AWS S3 전담

---

## 📅 프로젝트 기간
2025.06 ~ 2025.07 (1개월)
