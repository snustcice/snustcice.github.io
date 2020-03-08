---
layout: default
category: [Personal Practice, Certification, Craftsman Information Processing]
---

## 정보처리기능사 1과목 핵심 정리

#### 1. 컴퓨터 시스템의 구성
  > 키워드 : 지료, 정보, 호환성, 컴퓨터 세대별 특징, VLSI, 디지털 컴퓨터, IR(명령 레지스터), 신뢰성, PSW, PC(프로그램 카운터)

1. 컴퓨터의 개념
	* 컴퓨터의 정의
	* 컴퓨터의 특징
	* 컴퓨터의 구성
2. 중앙처리장치
	* 중앙처리장치의 정의와 구성
	* 제어장치
	* 연산장치
	* 레지스터
	* 마이크로프로세서
3. 입/출력장치
	* 입력장치
	* 출력장치
	* 보조기억장치
4. 컴퓨터의 발전 과정
	* 컴퓨터의 기원
	* 컴퓨터의 세대별 특징
	* 컴퓨터의 분류

#### 2. 논리회로
> 키워드 : 불 대수, 드모르강, 논리식의 간소화, 논리 게이트, 반가산기, 전가산기, FF(플립플롭), RS-FF, JK-FF, T-FF

1. 불 대수
    * 불 대수의 개요
	* 기본적인 논리함수
	* 불 대수의 기본 공식
	* 논리식의 간소화
2. 논리 게이트
    * 논리 게이트
	* 논리회로의 이해
3. 조합논리회로 - 반가산기, 전가산기
    * 조합논리회로
	* 반가산기(HA; Half Adder)
	* 전가산기(FA; Full Adder)
4. 기타 조합논리회로
    * 디코더(Decoder)
	* 인코더(Encoder)
	* 멀티플렉서(MUX; Multiplexer)
	* 디멀티플렉서(DeMUX; DeMultiplexer)
5. 순서논리회로
    * 순서논리회로의 특징
	* 플립플롭(FF; Flip-Flop)의 특징
	* RS-FF(Reset-Set FF)
	* D-FF
	* JK-FF
	* T-FF

#### 3. 자료의 표현과 연산
> 키워드 : 바이트, Full Word, 2진수, 8진수, 16진수, 1의 보수, EBCDIC, 그레이 코드, 해밍 코드, 2의 보수

1. 자료 구성의 단위
    * 자료 구성의 단위
2. 수의 표현 및 진법 전환
    * 진법의 개념 및 종류
	* 10진수를 2진수, 8진수, 16진수로 변환
	* 2진수, 8진수, 16진수를 10진수로 변환
	* 2진수, 8진수, 16진수 상호 변환
	* 8진수, 16진수 상호 변환
3. 보수
    * 보수
4. 자료의 내부적 표현
    * 자료의 내부적 표현의 개요
	* 10진 연산
	* 2진 연산
	* 부동 소수점 연산
5. 자료의 외부적 표현
    * BCD(Binary Coded Decimal, 2진화 10진 코드)
	* ASCII 코드(American Standard Code for Information Interchange)
	* EBCDIC(Extended BCD Interchange Code, 확장 2진화 10진 코드)
6. 기타 자료의 표현 형식
    * BCD 코드
	* Excess-3 코드(3 초과 코드)
	* Gray 코드
	* 패리티 컴사 코드
	* 해밍 코드
	* 코드의 분류

#### 4. 명령어 및 제어
> 키워드 : 이항 연산, AND 연산, 자료(Operand)부, 연산자(OP-Code)부, 3주소 명령어, 0주소 명령어, 즉시 주소지정방식, 간접 주소지정방식, 2주소 명령어, 연산장치

1. 명령어
    * 명령어의 구성
	* 연산자(OP-Code; Operation Code)의 기능
2. 연산
    * AND(Masking Operation)
	* OR(Selective-Set)
	* XOR(Compare)
	* NOT(Complement)
	* 논리 Shift
	* Rotate
	* MOVE
3. 명령어 형식
    * 명령어 형식의 개요
	* 3주소 명령어
	* 2주소 명령어
	* 1주소 명령어
	* 0주소 명령어
4. 주소지정방식
    * 접근 방식에 따른 분류
	* 계산에 의한 주소지정방식
	* 실제 기억공간 주소에 따른 구분

#### 5. 입/출력 제어 및 기억장치
> 키워드 : 채널, 인터럽트, 외부 인터럽트, ROM, EPROM, 캐시 메모리, 자기 테이프, 블록화 인수, 자기 디스크, 트랙

1. 채널/DMA
    * 채널
	* DMA(Direct Memory Acess)
2. 인터럽트
    * 인터럽트의 정의
	* 인터럽트의 종류 및 발생 원인
3. 주기억장치
    * 주기억장치의 개요
	* ROM
	* RAM
	* 기타 메모리
4. 보조기억장치
    * 보조기억장치의 개요
	* 자기 테이프(Magnetic Tape)
	* 자기 디스크(Magnetic Disk)
	* 하드디스크
	* CD-ROM
	* DVD