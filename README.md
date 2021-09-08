## Order-Sales-Analysis-with-Athena

 SELECT Customer
   FROM OrderSales
  WHERE Product IN ('Carrot','ArrowRoot')
  GROUP BY Customer
 HAVING COUNT(DISTINCT Product) = 2
 
 Customer
Julie
Valarie
