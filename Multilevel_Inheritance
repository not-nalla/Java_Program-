class Square{
   int length;

   Square(int l){
    length=l;
   }

   void area(){
    int s_area = length*length;
    System.out.println("Area of Square :"+s_area);
   }
}

class Rectangle extends Square{
    int breadth;

    Rectangle(int l, int b){
        super(l);
        breadth=b;
    }

    void rect_area(){
        int re_area=length*breadth;
        System.out.println("Area of Rectangle:"+re_area);
    }   
}

class Box extends Rectangle{
    int height;

    Box (int l,int b,int h){
        super(l,b);
        height=h;
    }

    void volume(){
        int bo_area=length*breadth*height;
        System.out.println("Area of Box:"+bo_area);
    }
}

class Main{
    public static void main(String[] args) {
        Box b = new Box(7,6,8);
        b.area();
        b.rect_area();
        b.volume();
    }
}
