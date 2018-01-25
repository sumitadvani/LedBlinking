#include<iostream.h>
#include<conio.h>
#include<dos.h>
void main()
{
clrscr();
 char intr[]="#Created By:-";
 char name[]="SUMIT ADVANI";
 textcolor(15);
 gotoxy(29,11);

	for(int i=0;intr[i]!='\0';i++)
	{
		cout<<intr[i]<<" ";
		delay(300);
	}
 gotoxy(29,14);

	for(i=0;name[i]!='\0';i++)
	{
		textcolor(i+2);
		cprintf("%c",name[i]);
		cout<<" ";
		delay(300);
	}
 textcolor(15);
 clrscr();
 cout<<"\n\n\n\n\n\n\n";

	for(i=0;i<80;i++)
	{
		textcolor(1);
		cprintf("*");
	}
 textcolor(15);
 clrscr();
for(i=1;i<=55;i++)
{
clrscr();
gotoxy(1,10);
textcolor(10);
cprintf("Please wait loading ");
for(int
j=1;j<=i;j++)
{
textcolor(9);
cprintf("*");
textcolor(15);
}
cout<<"\n "<<(i*100)/55<<"%";
delay(100);
}
clrscr();
int x=0,y=0,n;
char ch,ch1,ch2='y';
while(ch2=='y' || ch2=='Y')
{
clrscr();
textcolor(15);
cout<<" * * * * *";
cout<<"\n";
cout<<" **  *  **";
cout<<"\n";
cout<<" * * * * *";
cout<<"\n";
cout<<" *  ***  *";
cout<<"\n";
cout<<" * * * * *";
cout<<"\n";
cout<<" *  ***  *";
cout<<"\n";
cout<<" * * * * *";
cout<<"\n";
cout<<" **  *  **";
cout<<"\n";
cout<<" * * * * *";
cout<<"\n\nwhat to print: DIGIT or CHARACTER (c/d) : ";
cin>>ch;
if(ch=='d' || ch=='D')
{
cout<<"\nenter the digit to be printed: \n";
cin>>n;
gotoxy(1,1);
for(x=2;x<=10;x++)
{
for(y=1;y<=9;y++)
{
if(n==1)
{
if(x==10)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==2)
{
if(y==1||y==5||y==9||(x==10 && y<=5)||(x==2 && y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==3)
{
if(y==1||y==5||y==9||x==10)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==4)
{
if(x==10 || y==5 || (x==2 && y<=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==5)
{
if(y==1||y==5||y==9||(x==2 && y<=5)||(x==10 && y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==6)
{
if(y==1||y==5||y==9|| x==2 || (x==10 && y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==7)
{
if(y==1||x==10)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==8)
{
if(x==2||x==10||y==1||y==5|| y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==9)
{
if(y==1||y==5||y==9||x==10||(x==2 && y<=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(n==0)
{
if(x==2||x==10||y==1||y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else
{
gotoxy(1,15);
cout<<"enter no. between 0-9 only !!!";
getch();
}
}
}
}
else if(ch=='C'||ch=='c')
{
cout<<"\n\nenter the char. u want to print on display : \n";
cin>>ch1;
gotoxy(1,1);
for(x=2;x<=10;x++)
{
for(y=1;y<10;y++)
{
if(ch1=='A'||ch1=='a')
{
if(x==2 || x==10 || y==1 || y==5)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='B'||ch1=='b')
{
if(x==2||x==10||y==1||y==5|| y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='C'||ch1=='c')
{
if(y==1||y==9||x==2)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='D'||ch1=='d')
{
if(y==1||x==2||x==10||y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='E'||ch1=='e')
{
if(y==1||y==5||y==9||x==2)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='F'||ch1=='f')
{
if(y==1||y==5||x==2)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='G'||ch1=='g')
{
if(y==1||x==2||y==9||(x==10 && y>=5)||(y==5 && x>=6))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='H'||ch1=='h')
{
if(x==2||x==10||y==5)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='I'||ch1=='i')
{
if(y==1||y==9||x==6)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='J'||ch1=='j')
{
if(x==6||y==1||(y==9 && x<=6)||(x==2 && y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='K'||ch1=='k')
{
if(x==2||(y==5 && x<=6)||(x+y==11 && y<=5 && x>=6)||(x+y==2*y+1 && y>=5 && x>=6))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='L'||ch1=='l')
{
if(x==2||y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='M'||ch1=='m')
{
if(x==2||x==10||(x+y==2*y+1 && y<=5)||(x+y==11 && y<=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='N'||ch1=='n')
{
if(x==2||x==10||(x+y==2*y+1))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='O'||ch1=='o')
{
if(x==2||x==10||y==9||y==1)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='P'||ch1=='p')
{
if(x==2||y==1||y==5||(x==10 && y<=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='Q'||ch1=='q')
{
if(y==8||((x==2||x==10||y==9||y==1) && y<=8)||(x+y==2*y+1 && y>=5 && x>=6))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='R'||ch1=='r')
{
if(x==2||y==1||y==5||(x==10 && y<=5)||(x+y==2*y+1 && y>=5 && x>=6))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='S'||ch1=='s')
{
if(y==1||y==5||y==9||(x==2 && y<=5)||(x==10 && y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='T'||ch1=='t')
{
if(x==6||y==1)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='U'||ch1=='u')
{
if(x==2||x==10||y==9)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='V'||ch1=='v')
{
if(((x==2||x==10)&&y<=6)||(x+y==3*y-10&&y>=5&&x<=6)||(y==7&&x==8))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='W'||ch1=='w')
{
if(x==2||x==10||(x+y==11&&x<=6&&y>=5)||(x+y==2*y+1&&y>=5&&x>=6))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='X'||ch1=='x')
{
if(x+y==2*y+1 || x+y==11)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='Y'||ch1=='y')
{
if((x+y==2*y+1&&x<=6&&y<=5)||(x+y==11&&x>=6&&y<=5)||(x==6&&y>=5))
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else if(ch1=='Z'||ch1=='z')
{
if(y==1||y==9||(y==9 && x<=6)||x+y==11)
{
gotoxy(x,y);
textcolor(4+BLINK);
cprintf("*");
cout<<" ";
textcolor(15);
}
}
else
{
gotoxy(1,15);
cout<<"enter no. between 0-9 only !!!";
getch();
}
}
}
}
gotoxy(1,20);
cout<<"want to enter more ";
cin>>ch2;
}
getch();
}