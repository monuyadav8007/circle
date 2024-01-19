#include<graphics.h>
#include<math.h>
#include<conio.h>
main()
{
int
gd=DETCET,gm,x=200,y=300,redius=23;
initgraph(&gd,&gm,"c:\\turboc3\\bgi");
circle(x,y,redius);
getch();
closegraph();
return 0;
}
