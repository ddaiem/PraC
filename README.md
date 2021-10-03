# PraC
C언어 연습 용
#include <stdio.h>

/*git remote add origin https://github.com/ddaiem/PraC.git
git branch -M main
git push -u origin main*/

int Factorial(int n) {
	if (n == 0) {
		return 1;
	}
	else
		return n * Factorial(n - 1);
}

int main(void) {
	int n;
	scanf("%d", &n);
	printf("%d", Factorial(n));
	return 0;
}
