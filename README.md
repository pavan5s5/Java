# Experiment 1
## title display primitive default data types in Java 
class DefaultValues {

    byte b;
    short s;
    int i;
    long l;
    float f;
    double d;
    char c;
    boolean bool;

    void display() {
        System.out.println("byte    : " + b);
        System.out.println("short   : " + s);
        System.out.println("int     : " + i);
        System.out.println("long    : " + l);
        System.out.println("float   : " + f);
        System.out.println("double  : " + d);
        System.out.println("char    : " + c);
        System.out.println("boolean : " + bool);
    }

    public static void main(String[] args) {
        DefaultValues obj = new DefaultValues();
        obj.display();
    }
}
