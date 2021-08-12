# Concurrency Demo
- 동시성 제어를 위한 샘플코드를 구현 및 테스트하기 위한 프로젝트
- 1개의 인스턴스, N개의 인스턴스 등에서, 발생할 수 있는 동시성 이슈를 해결하기 위한 코드를 작성해본다.

## Index
***
- Specification
- Project Structure
- Concurrency Case
- Reference

## Specification
***
- TBD

## Project Structure
***
- TBD
 
## Concurrency Case
***
### # 인스턴스가 N개일때
- 일반적으로, 실무에서 직면하게 되는 케이스
- 대용량 트래픽이 인입되는 시스템이라면, 스케일아웃이 되는, 분산컴퓨팅 환경일것이고, 그렇다면 N개의 인스턴스에서 트랜잭션 경합이 일어나는 케이스를 반드시 고려해야 함!

#### 1) Select for update [nowait | wait n] 사용

#### 2) Redis를 활용한 @Transactional 처리 

### # 인스턴스가 1개일때 

## Reference
***
- Tech Note : TBD