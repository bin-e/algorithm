- Elapsed time: ???

# A+B - 8
출처: https://www.acmicpc.net/problem/11022

## :question: Problem
두 정수 A와 B를 입력받은 다음, A+B를 출력하는 프로그램을 작성하시오.

## Input/Output example
### Input
첫째 줄에 테스트 케이스의 개수 T가 주어진다.

각 테스트 케이스는 한 줄로 이루어져 있으며, 각 줄에 A와 B가 주어진다. (0 < A, B < 10)

### Output
각 테스트 케이스마다 "Case #x: A + B = C" 형식으로 출력한다. x는 테스트 케이스 번호이고 1부터 시작하며, C는 A+B이다.

## :exclamation: Submit
### Solved code
(Important part only)
``` java
import java.util.Scanner;

public class Main
{
	public static void main( String[] args )
	{
		Scanner in = new Scanner( System.in );

		int T = in.nextInt();
		for( int i = 0; i < T; )
		{
			int A = in.nextInt();
			int B = in.nextInt();

			System.out.println( String.format( "Case #%d: %d + %d = %d", ++i, A, B, (A + B) ) );
		}
	}
}
```

### Commentary
- 풀이 필요 x

### Discussion
- [ ] x

### References
- (If there is any reference)