# date
class date
{
byte dd, mm, yy;
public date(byte d, byte m, byte y)
{
dd= d;
mm= m;
yy= y;
}
void display()
{
System.out.println(""+dd+"/"+mm+"/"+yy);
}
date DOB = new date("13/2/1990");
}
