# 수학 I 문제 풀이 및 상세 분석

## 📝 총평

총 13개의 수학 I 문제에 대한 매우 상세한 풀이 및 채점 결과입니다.
분석 결과, **총 13문제 중 10문제는 정답**이었지만, **3문제(1번, 3번, 8번)에서 오답**이 발견되었습니다. 각 풀이 과정에서 생략되었던 기본 원리까지 상세히 설명하여, 풀이 과정을 완벽하게 이해할 수 있도록 돕는 데 초점을 맞췄습니다.

---

## 📸 첫 번째 이미지 풀이 (1번 ~ 7번)

### 1번 문제: 삼각함수 값

* **문제:** $sin\frac{11}{6}\pi$ 의 값은?
* **상세 풀이 과정:**
    1.  **각도 분해:** $\frac{11}{6}\pi$ 는 한 바퀴($2\pi$)를 기준으로 표현하면, $2\pi - \frac{1}{6}\pi$ 와 같습니다. 이 각의 동경은 **제4사분면**에 위치합니다.
    2.  **부호 결정:** `sin` 값은 단위 원의 **y좌표**에 해당합니다. 제4사분면에서 y좌표는 음수(-)이므로, $sin(\frac{11}{6}\pi)$ 의 값은 음수가 됩니다.
    3.  **값 변환:** 각 변환 공식 $sin(2\pi - \theta) = -sin(\theta)$ 에 따라, $sin(2\pi - \frac{\pi}{6}) = -sin(\frac{\pi}{6})$ 로 변환됩니다.
    4.  **최종 계산:** $sin(\frac{\pi}{6})$ 는 $sin(30^\circ)$ 이고 그 값은 $\frac{1}{2}$ 입니다. 따라서 최종 답은 $-\frac{1}{2}$ 입니다.
* **검증:** ❌ **오답**. 정답은 **$-\frac{1}{2}$** 입니다.

### 2번 문제: 삼각함수 곱셈 공식 활용

* **문제:** $sin\theta+cos\theta = \frac{1}{4}$ 일 때, $|sin\theta-cos\theta|$ 의 값은?
* **상세 풀이 과정:**
    1.  **양변 제곱:** 주어진 식의 양변을 제곱합니다: $(sin\theta + cos\theta)^2 = (\frac{1}{4})^2$
    2.  **곱셈 공식 전개:** $(a+b)^2 = a^2 + 2ab + b^2$ 공식을 이용하면, $sin^2\theta + 2sin\theta cos\theta + cos^2\theta = \frac{1}{16}$ 입니다.
    3.  **피타고라스 정리 적용:** $sin^2\theta + cos^2\theta = 1$ 이므로, 식은 $1 + 2sin\theta cos\theta = \frac{1}{16}$ 이 됩니다.
    4.  **$sin\theta cos\theta$ 값 구하기:** $2sin\theta cos\theta = \frac{1}{16} - 1 = -\frac{15}{16}$ 입니다.
    5.  **구하려는 식 제곱:** $(sin\theta - cos\theta)^2 = sin^2\theta - 2sin\theta cos\theta + cos^2\theta = 1 - 2sin\theta cos\theta$ 입니다.
    6.  **최종 계산:** 위 식에 4단계의 값을 대입하면 $1 - (-\frac{15}{16}) = \frac{31}{16}$ 입니다.
    7.  **제곱근 계산:** 따라서 $|sin\theta - cos\theta| = \sqrt{\frac{31}{16}} = \frac{\sqrt{31}}{4}$ 입니다.
* **검증:** ✅ **정답**.

### 3번 문제: 탄젠트 함수 주기

* **문제:** $y=tan(\pi x)$ 의 주기는?
* **상세 풀이 과정:**
    1.  **기본 주기:** $y = tan(x)$ 함수의 기본 주기는 $\pi$ 입니다.
    2.  **주기 변화 원리:** 함수 $y=tan(bx)$ 에서 $x$ 앞의 계수 $b$ 는 주기를 $\frac{1}{|b|}$ 배 합니다.
    3.  **공식 적용 및 계산:** 주기 공식은 $\frac{\text{기본 주기}}{|b|}$ 입니다. 이 문제에서는 $b=\pi$ 이므로, 주기는 $\frac{\pi}{|\pi|} = 1$ 입니다.
* **검증:** ❌ **오답**. 정답은 **$1$** 입니다.

### 4번 문제: 사인 함수 최솟값

* **문제:** $y=-3sin(x)$ 의 최솟값은?
* **상세 풀이 과정:**
    1.  **핵심 함수 범위:** $sin(x)$ 값의 범위는 항상 $-1 \le sin(x) \le 1$ 입니다.
    2.  **상수배 적용:** 이 부등식의 모든 변에 $-3$ 을 곱하면, 음수를 곱했으므로 부등호 방향이 바뀝니다.
        > $3 \ge -3sin(x) \ge -3$
    3.  **최솟값 결정:** 따라서 $y=-3sin(x)$ 의 최솟값은 $-3$ 입니다.
* **검증:** ✅ **정답**.

### 5번 문제: 사인 법칙

* **문제:** 삼각형 ABC에서 $A=60^\circ, B=30^\circ, a=4$ 일 때, $b$ 의 값은?
* **상세 풀이 과정:**
    1.  **법칙 선택:** '각과 마주보는 변'의 관계를 다루므로 사인 법칙($\frac{a}{\sin A} = \frac{b}{\sin B}$)을 사용합니다.
    2.  **값 대입:** $\frac{4}{\sin(60^\circ)} = \frac{b}{\sin(30^\circ)}$
    3.  **$b$ 에 대해 정리:** 양변에 $\sin(30^\circ)$ 를 곱하면 $b = \frac{4 \cdot \sin(30^\circ)}{\sin(60^\circ)}$ 입니다.
    4.  **특수각 값 대입 및 계산:** $b = \frac{4 \cdot (1/2)}{(\sqrt{3}/2)} = \frac{2}{(\sqrt{3}/2)} = 2 \cdot \frac{2}{\sqrt{3}} = \frac{4}{\sqrt{3}}$
    5.  **유리화:** 분모를 유리화하면 $b = \frac{4\sqrt{3}}{3}$ 입니다.
* **검증:** ✅ **정답**.

### 6번 문제: 코사인 법칙

* **문제:** 삼각형 ABC에서 $a=8, b=2, C=60^\circ$ 일 때, $c$ 의 값은?
* **상세 풀이 과정:**
    1.  **법칙 선택:** '두 변과 그 끼인 각'이 주어졌을 때 나머지 변을 구하므로 코사인 법칙($c^2 = a^2 + b^2 - 2ab \cos C$)을 사용합니다.
    2.  **값 대입:** $c^2 = 8^2 + 2^2 - 2(8)(2)\cos(60^\circ)$
    3.  **단계별 계산:** $c^2 = 64 + 4 - (32 \cdot \frac{1}{2}) = 68 - 16 = 52$
    4.  **제곱근 계산:** 변의 길이는 양수이므로 $c = \sqrt{52} = \sqrt{4 \times 13} = 2\sqrt{13}$ 입니다.
* **검증:** ✅ **정답**.

### 7번 문제: 삼각형 넓이

* **문제:** 삼각형 ABC에서 $a=1, b=9, C=45^\circ$ 일 때, 삼각형 ABC의 넓이는?
* **상세 풀이 과정:**
    1.  **공식 선택:** '두 변과 그 끼인 각'을 알 때의 넓이 공식 $S = \frac{1}{2}ab \sin C$ 를 사용합니다.
    2.  **값 대입:** $S = \frac{1}{2}(1)(9)\sin(45^\circ)$
    3.  **계산:** $S = \frac{9}{2} \cdot \frac{\sqrt{2}}{2} = \frac{9\sqrt{2}}{4}$
* **검증:** ✅ **정답**.

---

## 📸 두 번째 이미지 풀이 (8번 ~ 13번)

### 8번 문제: 수열의 항

* **문제:** 수열 $1.7, 2, -5, 10, \dots$ 에서 제3항의 값은?
* **상세 풀이 과정:**
    1.  **용어 이해:** '제n항'은 수열에서 n번째에 나열된 수를 의미합니다.
    2.  **항 확인:** 첫 번째 항은 1.7, 두 번째 항은 2, **세 번째 항은 -5** 입니다.
    3.  **답 찾기:** 문제는 제3항의 값을 묻고 있으므로, 답은 -5입니다.
* **검증:** ❌ **오답**. 학생 답 2는 제2항입니다. 정답은 **$-5$** 입니다.

### 9번 문제: 등차수열 일반항

* **문제:** 제2항이 2이고 제4항이 -2인 등차수열의 일반항은?
* **상세 풀이 과정:**
    1.  **연립방정식 세우기:** 일반항 $a_n = a_1 + (n-1)d$ 를 이용하여 식을 세웁니다.
        * $a_2 = a_1 + d = 2$
        * $a_4 = a_1 + 3d = -2$
    2.  **공차(d) 구하기:** 두 번째 식에서 첫 번째 식을 빼면 $(a_1 + 3d) - (a_1 + d) = -2 - 2 \implies 2d = -4 \implies d = -2$ 입니다.
    3.  **첫째항(a₁) 구하기:** $d=-2$ 를 첫 번째 식에 대입하면 $a_1 - 2 = 2 \implies a_1 = 4$ 입니다.
    4.  **일반항 완성:** $a_n = 4 + (n-1)(-2) = 4 - 2n + 2 = 6-2n$ 입니다.
* **검증:** ✅ **정답**.

### 10번 문제: 등비수열 일반항

* **문제:** 첫째항이 5이고 공비가 2인 등비수열의 일반항은?
* **상세 풀이 과정:**
    1.  **일반항 공식:** 등비수열의 일반항은 $a_n = a_1 \cdot r^{n-1}$ 입니다.
    2.  **값 대입:** 첫째항 $a_1=5$ 와 공비 $r=2$ 를 공식에 그대로 대입하면 $a_n = 5 \cdot 2^{n-1}$ 입니다.
* **검증:** ✅ **정답**.

### 11번 문제: 시그마(∑)의 성질

* **문제:** $\sum_{k=1}^{10} a_k = 1, \sum_{k=1}^{10} b_k = 6$ 일 때, $\sum_{k=1}^{10} (2a_k - b_k)$ 의 값은?
* **상세 풀이 과정:**
    1.  **선형성(분리):** 시그마는 덧셈, 뺄셈, 상수배에 대해 분리가 가능합니다.
        > $\sum_{k=1}^{10} (2a_k - b_k) = \sum_{k=1}^{10} 2a_k - \sum_{k=1}^{10} b_k = 2\sum_{k=1}^{10} a_k - \sum_{k=1}^{10} b_k$
    2.  **값 대입:** 문제에 주어진 값을 대입합니다.
        > $2(1) - 6 = 2 - 6 = -4$
* **검증:** ✅ **정답**.

### 12번 문제: 거듭제곱의 합

* **문제:** $\sum_{k=1}^{5} k^3$ 의 값은?
* **상세 풀이 과정:**
    1.  **공식 선택:** 자연수 세제곱의 합 공식 $\sum_{k=1}^{n} k^3 = \left( \frac{n(n+1)}{2} \right)^2$ 을 사용합니다.
    2.  **n=5 대입:** 공식에 $n=5$ 를 대입하면 $\left( \frac{5(5+1)}{2} \right)^2$ 입니다.
    3.  **계산:** $\left( \frac{5 \cdot 6}{2} \right)^2 = \left( \frac{30}{2} \right)^2 = 15^2 = 225$ 입니다.
* **검증:** ✅ **정답**.

### 13번 문제: 수학적 귀납법 (점화식)

* **문제:** 처음 풍선의 부피가 100cm³일 때, 부피의 절반을 덜어내고 60cm³를 추가한다. n번째 후 남아있는 용량을 $a_n$ 이라 할 때, $a_n$ 과 $a_{n+1}$ 사이의 관계는?
* **상세 풀이 과정:**
    1.  **관계식 목표:** n번째 항($a_n$)과 n+1번째 항($a_{n+1}$) 사이의 관계식을 찾는 것이 목표입니다.
    2.  **과정의 수학적 표현:**
        * n번째 상태의 부피는 $a_n$ 입니다.
        * '절반을 덜어내면' 남는 양은 $\frac{1}{2}a_n$ 입니다.
        * 여기에 '60을 추가하면' 최종 양은 $\frac{1}{2}a_n + 60$ 이 됩니다.
    3.  **관계식 완성:** 이 결과가 n+1번째 상태의 부피($a_{n+1}$)이므로, $a_{n+1} = \frac{1}{2}a_n + 60$ 입니다.
* **검증:** ✅ **정답**.
