# x86 어셈블리 언어 이해하기
## 입출력 작업
- 애플리케이션과 운영 체제 간의 계층적 커뮤니케이션
## 프로세서 아키텍처
- 프로세서의 내부 구조와 기능
## 마더보드 레이아웃
- 마더보드의 구성 요소 물리적 배열
## 인프라 실행
- 프로세서 내에서 명령을 수행하는 과정
## 프로그램 로딩
- 운영체제에서 프로그램을 메모리에 로드하는 방법
---
# CPU 명령어 실행 순서
## 1. Fetch Instruction
- CPU가 메모리에서 명령어를 가져옵니다.
## 2. Increment Instruction Pointer
- CPU가 다음 명령으로 포인터를 업데이트합니다.
## 3. Decode Instruction
- CPU는 명령어의 이진 패턴을 분석합니다.
## 4. Fetch Operands
- CPU는 레지스터와 메모리에서 피연산자를 가져옵니다.
## 5. Execute Instruction
- CPU는 가져온 피연산자를 사용하여 명령을 수행합니다.
## 6. Update Status Flags
- 상태 플래그 업데이트 CPU는 제로, 캐리, 오버플로와 같은 상태 플래그를 업데이트합니다.
## 7. Store Result
- CPU는 결과를 출력 피연산자에 저장합니다.
---
# Instruction Decode Timeline (ex.MOV AX, 1234h = B8 34 12)
## 1. Fetch B8
- IP = 1000 -> 1001
- 첫 바이트(B8) 가져오기
## 2. Decode opcode (B8)
- CPU는 MOV AX, imm16 명령임을 인식
- -> 즉시 2바이트 operand 필요하다는 걸 알게 됨
## 3. Fetch 34
- IP = 1001 -> 1002
- 첫 번째 operand 바이트 가져오기
## 4. Fetch 12
- IP = 1002 -> 1003
- 두 번째 operand 바이트 가져오기
## 5. Instruction complete
- 이제 B8, 34, 12 전체 명령어 해독 완료
- MOV AX, 1234h 라고 확정
## 6. Execute
- AX <- 1234h

