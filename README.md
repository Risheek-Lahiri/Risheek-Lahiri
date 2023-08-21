//👋 Hi, I’m @Risheek-Lahiri

import Random.CSE_Engineer;

class CSEGrad

class CSEGrad
{
    String name, isA, job;
   
    CSEGrad()
    {
        this.name = "Risheek Lahiri";
        this.isA = "student";
        this.job = "exploring";
    }
    public String toString()
    {
        return this.name+"("+this.isA+") is "+this.job+" ...";
    }
    void sayHello()
    {
        System.out.println("Hello, world! 👋");
    }
}

public class Myself
{
    public static void main(String[] args)
    {
       CSEGrad me = new CSEGrad();
        me.sayHello();
        System.out.println(me.toString());
    }
}
