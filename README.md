# A GUIDE TO CREATING A VIRTUAL COFFEE SHOP ON AWS
FOLLOW THE BELOW GUIDE ON HOW TO CREATE AN AUTO SCALING FOR A VIRTUAL COFFEE SHOP

## STEP ONE
Login to aws,navigate to vpc and create a vpc with a name e.g <virtual-coffee-shop>

## STEP TWO
Create two subnets and name them as follows;
<coffee-shop-public>
<coffee-shop-private>

## STEP THREE
Launch an instance in the <coffee-shop-public> and 
another instance in the <coffee-shop-private>

## STEP FOUR
Add a security group for each instance to contol inbound and outbound traffic.

## STEP FIVE
Add an Internet gateway for the <coffee-shop-vpc> for access to the public internet and a NAT gateway for the private subnet for access from the private subnet to teh outside but not the other way around. And add neccesary public and private route tables associated with custom vpc for routing within the existing vpc.
