# work01
work_2018_09_19

8.
Scanner scn = new Scanner(System.in);
        int v1 = scn.nextInt();
        System.out.println(v1*9/5+32);

11.
Scanner scn = new Scanner(System.in);
        Scanner abc = new Scanner(System.in);
        int v1 = scn.nextInt();
        int v2 = abc.nextInt();
        System.out.println( v1 + v2 );
        System.out.println( v1 - v2 );
        System.out.println( v1 * v2 );

12.
Scanner abc = new Scanner(System.in);
        Scanner def = new Scanner(System.in);
        Scanner ghi = new Scanner(System.in);
        int v1 = abc.nextInt();
        int v2 = def.nextInt();
        int v3 = ghi.nextInt();
        System.out.println( v1 + v2 + v3 );
        System.out.println( (v1 + v2 + v3)/3 );

15.
Scanner cm = new Scanner(System.in);
        Scanner kg = new Scanner(System.in);
        int v1 = cm.nextInt();
        int v2 = kg.nextInt();
        System.out.println( v1/2.54 );
        System.out.println( v2/0.454 );

24.
Scanner a = new Scanner(System.in);
        Scanner b = new Scanner(System.in);
        Scanner c = new Scanner(System.in);
        int v1 = a.nextInt();
        int v2 = b.nextInt();
        int v3 = c.nextInt();
        if ( v1 <= v2 && v2 <= v3)
        {
            System.out.println("True");
        }
        if ( v1 > v2 || v2 > v3 )
        {
            System.out.println("False");
        }

27.
Scanner a = new Scanner(System.in);
        Scanner b = new Scanner(System.in);
        Scanner c = new Scanner(System.in);
        int v1 = a.nextInt();
        int v2 = b.nextInt();
        int v3 = c.nextInt();
        if ( v1 % 4 == 0 && v1 % 100 != 0)
        {
            System.out.println("True");
        }
        if ( v1 % 4 != 0 || v1 % 100 == 0 && v1 % 400 != 0)
        {
            System.out.println("False");
        }
        if ( v2 % 4 == 0 && v2 % 100 != 0)
        {
            System.out.println("True");
        }
        if ( v2 % 4 != 0 || v2 % 100 == 0 && v2 % 400 != 0)
        {
            System.out.println("False");
        }
        if ( v3 % 4 == 0 && v3 % 100 != 0)
        {
            System.out.println("True");
        }
        if ( v3 % 4 != 0 || v3 % 100 == 0 && v3 % 400 != 0)
        {
            System.out.println("False");
        }
