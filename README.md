
class Shop extends Comp

{

 static int id=1;

 public void add1()

 {

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    try

    { 

        System.out.print("\nCustomer Id :- "+id);

        add();

    }

    catch(Exception e)

    {

    }

 }

 static int cid=100;

 public void cadd()

 {

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
try

    { 

        System.out.print("\nCustomer Id :- "+cid);

        Computer();

    }

    catch(Exception e)

    {

    }

 }

 static int lid=1000;

 public void ladd()

 {

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    try

    { 

        System.out.print("\nCustomer Id :- "+lid);

        Laptop();

    }

    catch(Exception e)
    {

    }

 }

 public static void main(String arg[ ])

 {

    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

    int ch=1,ch1=1;

    int i=0,j=0,k=0,l,z;

    Shop a[]=new Shop[10];

    Shop b[]=new Shop[10];

    Shop c[]=new Shop[10];

    //l=a.length;

    do 

    {

        try

        {

            System.out.println("\t \t \t Welcome To The Computer Shopee \n");

            System.out.println("\t \t \t          *M*E*N*U* \n");

            System.out.println("\t \t       1.  Add Customer       2.  Edit Customer");

            System.out.println("");

            System.out.println("\t \t         3.  Search Customer    4.  Delete Customer");

            System.out.println("");

            System.out.println("\t \t           5.  Display Customer   6.  Display List of items");

            System.out.println("");

            System.out.println("\t \t             7.  Complaint's        8.  Exit");

            System.out.println("Enter your Choice :- ");

            ch=Integer.parseInt(br.readLine());

            switch (ch)

                        {                                                      

                case 1 :

                    a[i]=new Shop();

                    a[i].add1();

                    System.out.println("Record Created");

                    i=i+1;

                    id=id+1;

                break;

                 

                case 2 :

                    b[j]=new Shop();

                    b[j].cadd();

                    System.out.println("Record Created");

                    j=j+1;

                    cid=cid+1;

                break;

                 

                case 3 :

                    b[k]=new Shop();

                    b[k].ladd();

                    System.out.println("Record Created");

                    k=k+1;

                    lid=lid+1;

                break; 

 

                case 4 :

                    System.out.println("Customer's Details");

                    for(z=0;z<10;z++)

                    {

                    //for(l=0;l<a.length;l++)

                        a[z].add();

                        //System.out.print(a[z]);

                    //}

                    }

 

                /*case 5 :                             

                                        int csearch,ch2=1,found; 

                    found=0;

                                        System.out.println("Enter the Customer ID :- ");

                                        csearch = Integer.parseInt(br.readLine());

                                        //System.out.println("\n Enter your choice:-");

                                        System.out.println("\n 1) Edit Name:- ");

                                        System.out.println("\n 2) Edit Address:- ");

                                        System.out.println("\n 3) Edit Phone:- ");

                                        System.out.println("\n 4) Edit Sex:-  : ");

                    System.out.println("\n 4) Edit Occupation:-  : ");

                    System.out.println("\n 4) Edit E-mail:-  : ");

                    System.out.println("\nselect your Choice :");

                                        ch1=Integer.parseInt(br.readLine());   

                    for(z=0;z<=cid;z++)

                    {

                                        if (a[z].cid==csearch)

                        {

                            found=1;

                            do

                            {

                            try

                            {

                            switch(ch2)

                            {              

                                case 1: 

                                                                System.out.println("\nEnter Customer Name : ");

                                                                    a[z].name=br.readLine();

                                break;

                                 

                                case 2:

                                                                    System.out.println("\n Enter Customer Address  : ");

                                                                    a[z].addr=br.readLine();

                                break;

                                 

                                case 3:

                                                                    System.out.println("\n Enter Customer Phone  : ");

                                                                    a[z].phno=Integer.parseInt(br.readLine());

                                break;

                                 

                                case 4:

                                                                    System.out.println("\n Enter Customer,s Sex:-  : ");

                                                                    a[z].sex=br.readLine();

                                break;

 

                                case 5:

                                                                    System.out.println("\n Enter Customer Occupation:-  : ");

                                                                    a[z].occ=br.readLine();

                                break;

                                 

                                case 6:

                                                                    System.out.println("\n Enter Customer E-mail:-  : ");

                                                                    a[z].email=br.readLine();

                                break;

 

                                default:

                                    System.out.println("invalid choice");

                                break;             

                                                    }

                            }

                            catch(Exception e)

                            {

                                System.out.println("Error");

                            }

                            }while(ch2!=7);  

                                        } 

                                }    

               

                    if(found==0)

                        System.out.println("Record Not Found");

               

            break;*/

                /*case 4 :

                    System.out.println("1.Computers");

                    System.out.println("2.Laptops");

                    System.out.println("3.Exit");

                    System.out.println("Enter your Choice :- ");

                    ch1=Integer.parseInt(br.readLine());

                    switch(ch1)

                    {

                        case 1 :

                            System.out.println("ID\tModelno\t\t\tCompany's Name\t\tPrice");

                        case 2 :

                            System.out.println("Modelno\t\t\tCompany's Name\t\tPrice");
                 }*/

            }

        }

        catch(Exception e)

        {

        }

    }while(ch!=4);

 }

 }


