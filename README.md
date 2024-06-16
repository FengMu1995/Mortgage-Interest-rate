# Mortgage-Interest-rate
Recently I am calculate my own mortgage. However， I met an wrong result when I cal it at the first time. So I share the cal formulation here to anyone who need it. 

You will know how to cal your own mortage interest and how many dollars corresponding to different loan peirod and different repayment way. 

The different loan method’s formulation is as follows：

1. average capital plus interest
   loan capital：A, monthly interest：a, repayment period(monthly):n, monthly repayment：X


   after the first-time repayment，the left total loans: Q1

   Q1= A(1+a) -X

   after the second-time repayment，the left total loans: Q2

   Q2 = Q1(1+a) -X = A(1+a)^2 - X(1+a) -X

   ...

   ...

   Equally,

   Qn = Qn-1(1+a) - X= A(1+a)^n - X[(1+a)^n-1 +(1+a)^n-2+ ...+(1+a)+1],And after the nth-month repayment, the left total loan is 0, ie.Qn=0.

   From the proportional sequence, it can be inferred that：

   A(1+a)^n - X*[(1+a)^n -1]/a = 0

   X = a*A(1+a)^n/[(1+a)^n -1]

   The interest you repayed is X*n-A.
   

3. average capital
