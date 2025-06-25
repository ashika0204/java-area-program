# java-area-program
class Area
{
    float a,b,c,d,l,s,r;
    double area1,area2,area3;
    void area(float r)
    {
        area1=3.14*r*r;
        System.out.println("area of circle is "+area1);
    }
    void area(float l,float b)
    {
        area2=l*b;
        System.out.println("area of rectangle is "+area2);
    }
    void area(float a,float d,float c)
    {
        s=(a+d+c)/2;
        area3=Math.sqrt(s*(s-a)*(s-d)*(s-c));
System.out.println("area of triangle is "+area2);
}
}
class Main
{
    public static void main(String args[])
    {
        float r,l,b,a,d,c;
        Scanner sc=new Scanner(System.in);
        System.out.println("enter the radius ");
        r=sc.nextFloat();
    System.out.println("enter the length and breadth of rectangle");
        l=sc.nextFloat();
        b=sc.nextFloat();
        System.out.println("enter the sides of triangle ");
        a=sc.nextFloat();
        d=sc.nextFloat();
        c=sc.nextFloat();
        Area ob =new Area();
        ob.area(r);
        ob.area(l,b);
        ob.area(a,d,c);
    }}
