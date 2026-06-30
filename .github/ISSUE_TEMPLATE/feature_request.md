---
name:  기능 요청
about: 새로운 기능을 제안하세요
title: "[FEATURE] "
labels: " enhancement"
assignees: ""
---

## � 기능 설명
<!-- 요청하는 기능이 무엇인지 명확하게 설명해주세요 -->

## 🎯 문제점
<!-- 이 기능이 해결할 문제가 무엇인가요? -->

## 💡 해결 방안
<!-- 원하는 해결 방안을 설명해주세요 -->

##  대안 검토
<!-- 고려했던 다른 해결 방안이 있다면 설명해주세요 -->

##  기술 사양 (해당하는 경우)
<!-- 예상되는 API, 데이터 구조, 성능 요구사항 등을 정의해주세요 -->

### API 엔드포인트 (해당하는 경우)
\\\
Method: GET/POST/PUT/DELETE
Path: /api/endpoint
Request: {...}
Response: {...}
\\\

### 데이터 모델 (해당하는 경우)
\\\java
@Data
@Builder
public class FeatureDto {
    private String id;
    private String name;
}
\\\

## 📦 관련 컴포넌트
- [ ] Frontend
- [ ] Backend (API Gateway)
- [ ] User Service
- [ ] Order Service
- [ ] Product Service
- [ ] Database
- [ ] Kafka Event

##  영향도 분석
- **영향받는 서비스**: (예: user-service, order-service)
- **데이터베이스 변경**: (예: Yes/No, 어떤 테이블)
- **API 변경**: (예: Yes/No, Breaking change 여부)

##  테스트 계획
<!-- 이 기능을 어떻게 테스트할 것인지 설명해주세요 -->
- [ ] 단위 테스트
- [ ] 통합 테스트
- [ ] 성능 테스트
- [ ] 보안 테스트

##  예상 작업량
- **예상 시간**: (예: 1-2일, 1주일)
- **복잡도**: (Low, Medium, High)

##  레이블
- 우선순위: (P0, P1, P2, P3)
- 카테고리: (API, Database, Architecture, UI)