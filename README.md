public class OOPS {

    public static void main(String args[]) {
        Pen p1 = new Pen();
        p1.setColor("Blue");
        System.out.println(p1.color);
        p1.setTip(5);
        System.out.println(p1.tip);
        p1.color = "Yellow";
        System.out.println(p1.color);
        // p1.setTip(7);
        // System.out.println(p1.tip);

        BankAccount myAcc = new BankAccount();
        myAcc.username = "Pratik007";
        myAcc.setpassword("abcdefghi");
    }

}



class BankAccount{
    public String username;
    private String password;
    public void setpassword(String pwd){
        password = pwd;

    }
}

 

class Pen{
    String color;
    int tip;

    void setColor(String newcolor){
        color = newcolor;
    }

    void setTip(int newTip){
        tip = newTip;

    }
}

class Student{
    String name;
    int age;
    float percentage;

    void setname(String newname){
        name = newname;
    }

    void setage(int newage){
        age = newage;
    }

    void calcpercentage(int phy, int math, int chem){
        percentage = (phy + chem + math) / 3;

    }
    }

