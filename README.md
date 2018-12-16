# #include<iostream>
using namespace std;

int main()
{
float diet_category,total_food,total_drink,A,B,C,D,X,Y;
cout<<"please enter your diet category number:";cin>>diet_category;
if (diet_category<1|| diet_category>2 )
{
  cout<<"invalid diet category number";
}
else if (diet_category=1)
{
    cout<<"enter amount per food category:"<<endl;
    cout<<"A:";cin>>A;
    cout<<"B:";cin>>B;
    cout<<"C:";cin>>C;
    cout<<"D:";cin>>D;
    cout<<"enter amount per drink category:"<<endl;
    cout<<"X:";cin>>X;
    cout<<"Y:";cin>>Y;
    total_food=(A+B+C+D);
    total_drink=(X+Y);
}
    if (total_food<=500)
    {
        if(total_drink<=3)
        {
           cout<<"total food amount:"<<total_food<<endl;
           cout<<"total drink amount:"<<total_drink;
        }
        else if(total_drink>3)
        {
            cout<<"total drink amount has been exceeded";
        }
     else if (total_food>500)
     {
         cout<<"total food amount has been exceeded";
     }
   }
else if (diet_category=2)
{
    cout<<"enter amount per food category:"<<endl;
    cout<<"A:";cin>>A;
    cout<<"B:";cin>>B;
    cout<<"C:";cin>>C;
    cout<<"D:";cin>>D;
    cout<<"enter amount per drink category:"<<endl;
    cout<<"X:";cin>>X;
    cout<<"Y:";cin>>Y;
    total_food=(A+B+C+D);
    total_drink=(X+Y);
    if (total_food<=550)
    {
        if(total_drink<=2.5)
        {
           cout<<"total food amount:"<<total_food<<endl;
           cout<<"total drink amount:"<<total_drink;
        }
        else if(total_drink>2.5)
        {
            cout<<"total drink amount has been exceeded";
        }
     else if (total_food>550)
     {
         cout<<"total food amount has been exceeded";
     }
    }
}
return 0;
 }
