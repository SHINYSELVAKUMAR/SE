

import java.io.*;

import java.lang.String;

import java.util.Arrays;

 

class Comp

{

 String name,addr,sex,email,occ,cname,lname;

 int phno,cprize,cmodelno,lprize,lmodelno;

 /*class Comp()

 {

 }*/

 public void add()

 { 

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    try

    { 

        System.out.println("\nEnter Customer Name :-");

        name=br.readLine();

        System.out.println("\n Enter Customer Address  :-");

        addr=br.readLine();

        System.out.println("\n Enter Customer Phone  :-");

        phno=Integer.parseInt(br.readLine());

        System.out.println("\n Enter Customer Sex  :-");

        sex=br.readLine();

        System.out.println("\n Enter Customer Occupation  :-");

        occ=br.readLine();

        System.out.println("\n Enter Customer E-mail  :-");

        email=br.readLine();

    }

    catch (Exception e)

    {

        System.out.println("Error");

    }

 }

 public void Computer()

 {

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    try

    { 

        System.out.println("\nEnter Company,s Name :-");

        cname=br.readLine();

        System.out.println("\nEnter Computer Model Number :-");
        cmodelno=Integer.parseInt(br.readLine());
        System.out.println("\nEnter Prize :-");

        cprize=Integer.parseInt(br.readLine());

    }

    catch (Exception e)

    {

        System.out.println("Error");

    }

 }

 public void Laptop()

 {    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    try

    { 

        System.out.println("\nEnter Laptop Name :-");

        lname=br.readLine();

        System.out.println("\nEnter Laptop Model Number :-");

        lmodelno=Integer.parseInt(br.readLine());

        System.out.println("\nEnter Prize :-");

        lprize=Integer.parseInt(br.readLine());

    }

    catch (Exception e)

    {

        System.out.println("Error");

    }

 }
069
}
