# dingco-aws-serverless

딩코딩코 무료 프리코스 **`Spring 백엔드 개발자를 위한 AWS 서버리스 최소 기초`** 의 교재 이미지 호스팅 저장소입니다.

- 강의·기술 검증: 칸(이창민)
- 커리큘럼·교재·편집: 박현준
- 공동제작: 딩코랩스

## 이 저장소의 역할

노션 교재 페이지가 여기 있는 이미지를 `raw.githubusercontent.com` URL 로 직접 참조합니다.

> **이 저장소를 비공개로 바꾸거나 삭제하면 노션 교재의 이미지가 전부 깨집니다.**
> 파일명도 바꾸지 마세요.

## 이미지 목록

| 파일 | 쓰이는 곳 | 내용 |
|---|---|---|
| `diag-sync-vs-async.png` | 1-1 | 요청 기반과 이벤트 기반 처리 흐름 비교 |
| `term-region.png` | 1-2 | 리전만 바꿔 조회했을 때의 실제 출력 |
| `diag-service-map.png` | 1-3 | Lambda·SQS·DLQ·S3·DynamoDB 역할 배치도 |
| `term-resources.png` | 1-3 | 큐·DLQ·버킷·테이블 생성 확인 출력 |
| `diag-payload-ref.png` | 1-3 | 본문 크기와 무관하게 일정한 메시지 크기 |
| `diag-local-to-aws.png` | 1-4 | 로컬 검증에서 배포·teardown 까지 6단계 |
| `term-redelivery.png` | 1-5 | 삭제하지 않은 메시지가 같은 MessageId 로 재전달되는 실제 출력 |
| `term-dlq.png` | 1-5 | 재시도 한도 초과 후 DLQ 로 이동한 실제 출력 |
| `term-teardown.png` | 1-5 | teardown 후 목록이 비어 있는 실제 출력 |

터미널 캡처는 모두 **LocalStack 4.9 에서 실제로 실행한 출력**입니다. 지어낸 출력은 없습니다.
