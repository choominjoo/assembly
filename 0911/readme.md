# 1.7 Review Questions and Exercises

## 1.7.1 Short Answer

1. In an 8-bit binary number, which is the most significant bit (MSB)?

    맨 왼쪽 비트

    (**MSB는 가장 왼쪽(최상위)비트)

2. What is the decimal representation of each of the following unsigned binary integers?
(부호 없는 8비트 2진수를 10진수로 변환하시오.)
    
    a. 00110101
    
    0*128 + 0*64 + 1*32 + 1*16 + 0*8 + 1*4 + 0*2 + 1*1
    
    = 53
    b. 10010110
    
    1*128 + 0*64 + 0*32 + 1*16 + 0*8 + 1*4 + 1*2 + 0*1
    
    = 150
    c. 11001100
    
    1*128 + 1*64 + 0*32 + 0*16 + 1*8 + 1*4 + 0*2 + 0*1
    
    =204
    

3. What is the sum of each pair of binary integers?
(8비트 이진수 쌍의 합을 구하시오.)
    
    a. 10101111 + 11011011
    
    = 110001010
    b. 10010111 + 11111111
    
    = 110010110
    c. 01110101 + 10101100
    
    = 100100001
    
4. Calculate binary 00001101 minus 00000111.

    00001101 - 00000111

    = 00000110

5. How many bits are used by each of the following data types?
(다음 자료형이 각각 몇 비트를 사용하는지 쓰시오.)
    
    a. word
    
    보통 16비트(= 2바이트)
    
    b. doubleword
    
    word * 2 = 32비트(= 4바이트)
    
    c. quadword
    
    word * 4 = 64비트(= 8바이트)
    
    d. double quadword
    
    word * 8 = 128비트(= 16바이트)
    

6. What is the minimum number of binary bits needed to represent each of the following
unsigned decimal integers?
(부호 없는 10진 정수를 표현하는 데 필요한 최소 비트 수는 얼마인가?)
    
    a. 4095
    
    2^12 - 1 = 4095
    
    → 12비트
    
    b. 65534
    
    2^16 - 1 = 65535
    
    → 16비트
    
    c. 42319
    
    2^15 = 32768 (부족)
    
    2^16 = 65536
    
    → 16비트
    
7. What is the hexadecimal representation of each of the following binary numbers?
(2진수를 16진수로 변환하시오.)
    
    a. 0011 0101 1101 1010
    
    0011 → 3
    
    0101 → 5
    
    1101 → D (13)
    
    1010 → A (10)
    
    → 0x35DA
    
    b. 1100 1110 1010 0011
    
    1100 → C (12)
    
    1110 → E (14)
    
    1010 → A (10)
    
    0011 → 3
    
    → 0xCEA3
    
    c. 1111 1110 1101 1011
    
    1111 → F (15)
    
    1110 → E (14)
    
    1101 → D (13)
    
    1011 → B (11)
    
    → 0xFEDB
    
8. What is the binary representation of the following hexadecimal numbers?
(16진수를 2진수로 변환하시오.)
    
    a. 0126F9D4
    
    0000 0001 0010 0110 1111 1001 1101 0100
    
    b. 6ACDFA95
    
    0110 1010 1100 1101 1111 1010 1001 0101
    
    c. F69BDC2A
    
    1111 0110 1001 1011 1101 1100 0010 1010
    
9. What is the unsigned decimal representation of each of the following hexadecimal integers?
(16진수를 부호 없는 10진수로 변환하시오.)
    
    a. 3A
    
    3*16 + 10*1
    
    = 58
    
    b. 1BF
    
    1*256 + 11*16 + 15*1
    
    = 447
    
    c. 1001
    
    1*4096 + 0*256 + 0*16 + 1*1
    
    = 4097
    
10. What is the unsigned decimal representation of each of the following hexadecimal integers?
(16진수를 부호 없는 10진수로 변환하시오.)
    
    a. 62
    
    6*16 + 2*1
    
    = 98
    
    b. 4B3
    
    4*256 + 11*16 + 3*1
    
    = 1203
    
    c. 29F
    
    2*256 + 9*16 + 15*1
    
    = 671
    

11. What is the 16-bit hexadecimal representation of each of the following signed decimal integers?
(부호 있는 10진수를 16비트 2의 보수로 변환한 16진수 값을 구하시오.)
    
    a. -24
    
    0000 0000 0001 1000
    
    1111 1111 1110 0111
    
    1111 1111 1110 1000
    
    → 0xFFE8
    
    b. -331
    
    0000 0001 0100 1011
    
    1111 1110 1011 0100
    
    1111 1110 1011 0101
    
    → 0xFEB5
    
12. What is the 16-bit hexadecimal representation of each of the following signed decimal integers?
(부호 있는 10진수를 16비트 2의 보수로 변환한 16진수 값을 구하시오.)
    
    a. -21
    
    0000 0000 0001 0101
    
    1111 1111 1110 1010
    
    1111 1111 1110 1011
    
    → 0xFFEB
    
    b. -45
    
    0000 0000 0010 1101
    
    1111 1111 1101 0010
    
    1111 1111 1101 0011
    
    → 0xFFD3
    
13. The following 16-bit hexadecimal numbers represent signed integers. Convert each to
decimal.
(16비트 16진수가 부호 있는 정수로 표현되어 있습니다. 이를 10진수로 변환하시오.)
    
    a. 6BF9
    
    0110 1011 1111 1001 (MSB는 0)
    
    6*4096 + 11*256 + 15*16 + 9*1
    
    = 27641
    
    b. C123
    
    1100 0001 0010 0011 (MSB는 1)
    
    0011 1110 1101 1100
    
    0011 1110 1101 1101
    
    3*4096 + 14*256 + 13*16 + 13*+1
    
    = 16096
    
    → -16096
    
14. The following 16-bit hexadecimal numbers represent signed integers. Convert each to
decimal.
(16비트 16진수가 부호 있는 정수로 표현되어 있습니다. 이를 10진수로 변환하시오.)
    
    a. 4CD2
    
    0100 1100 1101 0010 (MSB는 0)
    
    4*4096 + 12*256 + 13*16 + 2*1
    
    = 19766
    
    b. 8230
    
    1000 0010 0011 0000 (MSB는 1)
    
    0111 1101 1100 1111
    
    0111 1101 1101 0000
    
    7*4096 + 13*256 + 13*16 + 0*1
    
    = 32208
    
    → -32208
    
15. What is the decimal representation of each of the following signed binary numbers?
(8비트 2진수가 부호 있는 정수(2의 보수)로 표현되어 있습니다. 이를 10진수로 변환하시오.)
    
    a. 10110101
    
    MSB는 1
    
    01001010
    
    01001011
    
    → 64 + 8 + 2 + 1
    
    = 75
    
    → -75
    
    b. 00101010
    
    MSB는 0
    
    → 32 + 8 + 2
    
    = 42
    
    c. 11110000
    
    MSB는 1
    
    00001111
    
    00010000
    
    → 16
    
    → -16
    
16. What is the decimal representation of each of the following signed binary numbers?
(8비트 2진수가 부호 있는 정수(2의 보수)로 표현되어 있습니다. 이를 10진수로 변환하시오.)
    
    a. 10000000
    
    MSB는 1
    
    01111111
    
    10000000
    
    → 128
    
    → -128
    
    b. 11001100
    
    MSB는 1
    
    00110011
    
    00110100
    
    → 32 + 16 + 4
    
    = 52
    
    → -52
    
    c. 10110111
    
    MSB는 1
    
    01001000
    
    01001001
    
    → 64 + 8 + 1
    
    = 73
    
    → -73
    
17. What is the 8-bit binary (two’s-complement) representation of each of the following signed
decimal integers?
(부호 있는 10진수를 8비트 2의 보수로 변환하시오.)
    
    a. -5
    
    0000 0101
    
    1111 1010
    
    1111 1011
    
    b. -42
    
    0010 1010
    
    1101 0101
    
    1101 0110
    
    c. -16
    
    0001 0000
    
    1110 1111
    
    1111 0000
    
18. What is the 8-bit binary (two’s-complement) representation of each of the following signed
decimal integers?
(부호 있는 10진수를 8비트 2의 보수로 변환하시오.)
    
    a. -72
    
    0100 1000
    
    1011 0111
    
    1011 1000
    
    b. -98
    
    0110 0010
    
    1001 1101
    
    1001 1110
    
    c. -26
    
    0001 1010
    
    1110 0101
    
    1110 0110
    
19. What is the sum of each pair of hexadecimal integers?
(16진수 쌍의 합을 구하시오.)
    
    a. 6B4 + 3FE
    
    4 + E = 18 → 18 - 16 = 2, carry 1
    
    B + F + 1(carry) = 27 → 27 - 16 = 11(B), carry 1
    
    6 + 3 + 1(carry) = 10(A)
    
    → AB2
    
    b. A49 + 6BD
    
    9 + D = 22 → 22 - 16 = 6, carry 1
    
    4 + B + 1(carry) = 16 → 16 - 16 = 0, carry 1
    
    A + 6 + 1(carry) = 17 → 17 - 16 = 1, carry 1
    
    → 1106
    
20. What is the sum of each pair of hexadecimal integers?
(16진수 쌍의 합을 구하시오.)
    
    a. 7C4 + 3BE
    
    4 + E = 18 → 18 - 16 = 2, carry 1
    
    12 + 11 + 1(carry) = 24 → 24 - 16 = 8, carry 1
    
    7 + 3 + 1(carry) = 11(B)
    
    → B82
    
    b. B69 + 7AD
    
    9 + 13 = 22 → 22 - 16 = 6, carry 1
    
    6 + A + 1 = 17 → 17 - 16 = 1, carry 1
    
    B + 7 + 1 = 19 → 19 - 16 = 3, carry 1
    
    → 1316
    

21. What are the hexadecimal and decimal representations of the ASCII character capital B?
(ASCII 문자 대문자 B를 16진수와 10진수로 나타내면 각각 무엇인가?)
    
    hexadecimal → 0x42
    
    decimal → 66
    

22.  What are the hexadecimal and decimal representations of the ASCII character capital G?
(ASCII 문자 대문자 G를 16진수와 10진수로 나타내면 각각 무엇인가?)
    
    hexadecimal → 0x47
    
    decimal → 71
    

23. Challenge: What is the largest decimal value you can represent, using a 129-bit unsigned
integer?
(129비트 부호 없는 정수(unsigned integer)로 표현할 수 있는 가장 큰 10진수 값은 무엇인가?)
    
    2^129 - 1
    

24. Challenge: What is the largest decimal value you can represent, using a 86-bit signed
integer?
(86비트 부호 있는 정수(signed integer)로 표현할 수 있는 가장 큰 10진수 값은 무엇인가?)
    
    2^85 - 1
    

25. Create a truth table to show all possible inputs and outputs for the boolean function
described by ¬(A∨B).
(불 대수 함수 ¬(A∨B)에 대해 모든 입력과 출력 조합을 나타내는 진리표(truth table)를 작성하시오.)
    
    | A | B | ¬(A∨B) |
    | --- | --- | --- |
    | 0 | 0 | 1 |
    | 0 | 1 | 0 |
    | 1 | 0 | 0 |
    | 1 | 1 | 0 |

26. Create a truth table to show all possible inputs and outputs for the boolean function
described by (¬A∧¬B). How would you describe the rightmost column of this table in
relation to the table from question number 25? Have you heard of De Morgan’s Theorem?
(불 대수 함수 (¬A∧¬B)에 대해 모든 입력과 출력 조합을 나타내는 진리표를 작성하시오.)
    
    | A | B | ¬A  | ¬B | ¬A∧¬B |
    | --- | --- | --- | --- | --- |
    | 0 | 0 | 1 | 1 | 1 |
    | 0 | 1 | 1 | 0 | 0 |
    | 1 | 0 | 0 | 1 | 0 |
    | 1 | 1 | 0 | 0 | 1 |

27. If a boolean function has four inputs, how many rows are required for its truth table?
(불 대수 함수(Boolean function)가 4개의 입력을 가질 때, 이 함수의 진리표(truth table)를 만들려면 몇 개의 행(row)이 필요한가?)
    
    각 입력값은 2가지 값 가능 (0 또는 1)
    
    독립적인 입력 4 → 2^4 = 16
    
    → 16행
    

28. How many selector bits are required for a four-input multiplexer?
(4개의 입력을 가지는 멀티플렉서(Multiplexer)에서, 선택(selector) 비트는 몇 개가 필요한가?)
    
    따라서 4개의 입력을 가지는 멀티플렉서에는 2개의 선택 비트가 필요합니다.
    
    → 2개

### 1.7.2 Algorithm Workbench

Use any high-level programming language you wish for the following programming exercises.
Do not call built-in library functions that accomplish these tasks automatically. (Examples are
sprintf and sscanf from the Standard C library.)

(다음 프로그래밍 연습에서는 원하는 고급 프로그래밍 언어를 사용해도 됩니다. 다만, 해당 작업을 자동으로 수행해주는 내장 라이브러리 함수는 호출하지 마십시오. (예: C 표준 라이브러리의 sprintf, sscanf 등))

1. Write a function that receives a string containing a 16-bit binary integer. The function must
return the string’s integer value.
(16비트 이진수 문자열 → 정수)
<pre>
    <code>
def binary_to_int(binary_str):
    result = 0
    for bit in binary_str:
        result = result * 2 + (1 if bit == '1' else 0)
    return result
    </code>
</pre>
2. Write a function that receives a string containing a 32-bit hexadecimal integer. The function
must return the string’s integer value.
(32비트 16진수 문자열 → 정수)
<pre>
    <code>
def hex_to_int(hex_str):
    hex_digits = '0123456789ABCDEF'
    hex_str = hex_str.upper()
    result = 0
    for ch in hex_str:
        value = hex_digits.index(ch)
        result = result * 16 + value
    return result
    </code>
</pre>
3. Write a function that receives an integer. The function must return a string containing the
binary representation of the integer.
(정수 → 2진수 문자열로 반환)
<pre>
    <code>
def int_to_binary(n):
    if n == 0:
        return "0"
    result = ''
    while n > 0:
        result = str(n % 2) + result
        n = n // 2
    return result
    </code>
</pre>
4. Write a function that receives an integer. The function must return a string containing the
hexadecimal representation of the integer.
(정수 → 16진수 문자열로 반환)
<pre>
    <code>
def int_to_hex(n):
    if n == 0:
        return "0"
    hex_digits = '0123456789ABCDEF'
    result = ''
    while n > 0:
        result = hex_digits[n % 16] + result
        n = n // 16
    return result
    </code>
</pre>
5. Write a function that adds two digit strings in base b, where 2 ≤ b ≤ 10. Each string may
contain as many as 1,000 digits. Return the sum in a string that uses the same number base.
(두 숫자 문자열을 base b (2 ≤ b ≤ 10)에서 더하기)
<pre>
    <code>
def add_base_b(num1, num2, base):
    max_len = max(len(num1), len(num2))
    num1 = num1.zfill(max_len)
    num2 = num2.zfill(max_len)

    result = ''
    carry = 0

    for i in range(max_len - 1, -1, -1):
        digit1 = int(num1[i])
        digit2 = int(num2[i])
        total = digit1 + digit2 + carry
        result = str(total % base) + result
        carry = total // base

    if carry > 0:
        result = str(carry) + result

    return result
    </code>
</pre>
6. Write a function that adds two hexadecimal strings, each as long as 1,000 digits. Return a
hexadecimal string that represents the sum of the inputs.
(16진수 긴 문자열 두 개 더하기 (최대 1000자리))
<pre>
    <code>
def add_hex_strings(hex1, hex2):
    hex_digits = '0123456789ABCDEF'
    hex_to_val = {ch: i for i, ch in enumerate(hex_digits)}
    val_to_hex = {i: ch for i, ch in enumerate(hex_digits)}

    hex1 = hex1.upper().zfill(max(len(hex1), len(hex2)))
    hex2 = hex2.upper().zfill(max(len(hex1), len(hex2)))

    result = ''
    carry = 0

    for i in range(len(hex1) - 1, -1, -1):
        d1 = hex_to_val[hex1[i]]
        d2 = hex_to_val[hex2[i]]
        total = d1 + d2 + carry
        carry = total // 16
        result = val_to_hex[total % 16] + result

    if carry > 0:
        result = val_to_hex[carry] + result

    return result
    </code>
</pre>
7. Write a function that multiplies a single hexadecimal digit by a hexadecimal digit string as
long as 1,000 digits. Return a hexadecimal string that represents the product.
(한 자리 16진수 * 1000자리 16진수 문자열)
<pre>
    <code>
def multiply_hex_digit_by_string(digit, hex_string):
    hex_digits = '0123456789ABCDEF'
    digit = digit.upper()
    hex_string = hex_string.upper()

    hex_to_val = {ch: i for i, ch in enumerate(hex_digits)}
    val_to_hex = {i: ch for i, ch in enumerate(hex_digits)}

    d = hex_to_val[digit]
    carry = 0
    result = ''

    for ch in reversed(hex_string):
        mul = d * hex_to_val[ch] + carry
        carry = mul // 16
        result = val_to_hex[mul % 16] + result

    if carry > 0:
        result = val_to_hex[carry] + result

    return result
    </code>
</pre>
8. Write a Java program that contains the calculation shown below. Then, use the `javap –c` command to disassemble your code. Add comments to each line that provide your best
guess as to its purpose.
int Y;
int X = (Y + 4) * 3;
(Java 프로그램 작성 및 `javap -c` 결과 해석)
<pre>
    <code>
public class Calc {
    public static void main(String[] args) {
        int Y = 2; // 어떤 값이든 OK
        int X = (Y + 4) * 3;
        System.out.println(X);
    }
}
    </code>
</pre>
<pre>
    <code>
// Compiled from "Calc.java"
public class Calc {
  public Calc();
    Code:
       0: aload_0                  // this 객체 로드
       1: invokespecial #1        // Object 클래스의 생성자 호출
       4: return

  public static void main(java.lang.String[]);
    Code:
       0: iconst_2                // 정수 2 (Y의 값) push
       1: istore_1                // 지역 변수 1번(Y)에 저장
       2: iload_1                 // Y 로드
       3: iconst_4                // 정수 4 push
       4: iadd                    // Y + 4 계산
       5: iconst_3                // 정수 3 push
       6: imul                    // 곱셈 (Y+4) * 3
       7: istore_2                // 지역 변수 2번(X)에 저장
       8: getstatic #2            // System.out 불러오기
      11: iload_2                 // X 값 로드
      12: invokevirtual #3        // println(X)
      15: return
}
    </code>
</pre>
9. Devise a way of subtracting unsigned binary integers. Test your technique by subtracting binary 00000101 from binary 10001000, producing 10000011. Test your technique with at least two other sets of integers, in which a smaller value is always subtracted from a larger one.
    
    (이진수 뺄셈 알고리즘 구현)
<pre>
    <code>
def binary_to_int(bin_str):
    """2진수 문자열을 정수로 변환"""
    result = 0
    for bit in bin_str:
        result = result * 2 + int(bit)
    return result

def int_to_8bit_binary(n):
    """정수를 8비트 2진수 문자열로 변환"""
    result = ''
    for i in range(7, -1, -1):
        bit = (n >> i) & 1
        result += str(bit)
    return result

def subtract_unsigned_bin(bin1, bin2):
    """Unsigned 8비트 이진수 뺄셈"""
    a = binary_to_int(bin1)
    b = binary_to_int(bin2)
    if a < b:
        raise ValueError("Cannot subtract a larger number from a smaller one in unsigned binary")
    diff = a - b
    return int_to_8bit_binary(diff)

    </code>
</pre>
