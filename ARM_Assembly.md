ARM Assembly 기초



RISC - Reduced Instruction Set Compiler ( 명령어 체계가 적음 )

임베디드나 IOT 쪽으로 사용하는 사람이 늘어나고 있음



ARM Architecture의 레지스터는 R0부터 R15까지 존재합니다.

레지스터는 CPU내부에 있는 물리적인 초고속 메모리이고 해당 레지스터를 통해서 빠른 연산이 가능합니다.

 

바이트 단위로 사용이 가능하며

2가지의 모드가 존재합니다. (PC의 업데이트)

ARM - 4-byte instructions

THUMB - 2-byte instructions



Arm Assembly어는 큰 3가지의 틀을 따르고 있습니다. 

operator : 명령어

dst : 목적지

src : 소스

immediate는 숫자를 의미하는 형식으로 작성됩니다.

[ ] -> 해당 레지스터의 메모리 위치

<operator> <dst> <src>

<operator> <dst> <immediate>

<operator> <dst> [address]



