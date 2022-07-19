# CPU

![CPU1](./img/CPU1.png)

Arithmetic : 연산

logic : 큰지 작은지 같은지 비교

control : 메모리 포함 기타 컨트롤

accumulator : CPU의 저장장치(산술 논리 장치 결과 저장)

## To run the program:

Assembler => OS => CPU


### Assembler

convert these instructions into numbers

어셈블리를 어셈블러로 변환 = 어셈블리어를 기계어로 변환

assembly language => assembler

쉽게 말해서 명령어를 숫자로 변환

### OS(Operating System)

put them into RAM starting at first lcation
Tell CPU to start processing instructions at first location

OS는 메모리(RAM)의 첫번째 위치에서부터 명령을 시작함

### CPU

![CPU2](./img/CPU2.png)

Fetches GET , decodes it , executes it
Fetches PRINT , decodes it , executes it
Fetches STOP , decodes it , executes it

ex) <br/>
GET   Get a number from keyboard  <br/>
STORE Fst   Store it at memory location named "Fst" <br/>
GET   Get another number from keyboard  <br/>
STORE Snd   Store it at memory location named "Snd" <br/>
SUB Fst   Accumulator <= Accumulator - Fst  <br/>
IFPOS Zwei    If Accumulator <= Accumulator - Fst <br/>
LOAD Fst    Accumulator <= Fst  <br/>
GOTO Show   Jump to "show"  <br/>
Zwei LOAD Snd   Accumulator <= Snd  <br/>
Show PRINT    Print accumulator <br/>
STOP  <br/>
Fst   0 <br/>
Snd   0 <br/>

https://www.cs.princeton.edu/courses/archive/fall14/cos109/toysim
