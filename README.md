# AES
- Python을 이용한 AES 암/복호화 알고리즘 구현 (key 길이는 128bit로 고정)  - 데이터의 길이는 임의의 128bit 평문 (패딩고려 x)  - 라운드 키 생성은 라이브러리 사용 가능  - Subbyte, InvSubbyte 연산은 lookup table 로 구현 가능  - GF(2^8) 상에서의 덧셈, 곱셈 연산은 반드시 bitwise operator (AND, OR, XOR, NOT, SHIFT) 로 구현 해야함  - 기약 다항식: x^8 + x^4 + x^3 + x^1 + 1 (수정)  - 검증결과 포함 (라이브러리 출력결과와 일치여부)
