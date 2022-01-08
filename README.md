# FOOD-MENU
Program to take order and display them
#include<stdio.h>

main()
{
   int order;
   printf(" DESI BAKE HOUSE \n ---------------------\n 1.Pizza :: ₹239.00 \n 2.Burger:: ₹129.00 \n 3.Pasta :: ₹179.00 \n 4.French Fries :: ₹99.00\n 5.Sandwich:: ₹149.00\n \n ENTER ORDER NO:");
   scanf("%d",&order);
   
switch(order)
{

case 1: printf("FOOD ITEM -PIZZA \nPRICE -₹239.00\n ");
        break;
case 2: printf("FOOD ITEM -BURGER \nPRICE -₹129.00\n ");
        break;
case 3: printf("FOOD ITEM -PASTA\nPRICE -₹179.00\n ");
        break;   
case 4: printf("FOOD ITEM -FRENCH FRIES \nPRICE -₹99.00\n ");
        break;
case 5: printf("FOOD ITEM -SANDWICH \nPRICE -₹149.00\n ");
        break;
  
default: printf("Invalid Order!");
}

return 0;
}
