# C_Switch-Case
Example 1
```sh
#include<stdio.h>

void main(){
	int gun;
	printf("Haftanin kacinci gunundeyiz ?\n");
	scanf("%d",&gun);
	
	switch(gun){
		case 1:
			printf("Bugun pazartesi (today is monday) ");
			break;
		case 2:
			printf("Bugun sali (today is tuesday) ");
			break;
		case 3:
			printf("Bugun carsamba (today is wednesday) ");
			break;
		case 4:
			printf("Bugun persembe (today is thursday) ");
			break;
		case 5:
			printf("Bugun cuma (today is friday) ");
			break;
		case 6:
			printf("Bugun cumartesi (today is saturday) ");
			break;
		case 7:
			printf("Bugun pazar (today is sunday) ");
			break;
	}
}
```
