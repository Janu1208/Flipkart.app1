# Online Book Shop Portal


## Tables

###Table1: Books

| S.No | Name | Reviews | Price | Current_Date
| ---- |-------|---------|-------|-------------
| 1   | Java  |   3     |   500 | 20/08/2019
| 2   | C     |   5     |  400  | 22/08/2019
| 3   | DBMS  |   4     |  600  | 19/08/2019
| 4   | Python|   5     |  350  | 21/08/2019



########    Price Low to High;

Set S.No,Name,Reviews,Price,Current_Date from Books Order by S.No,Name,Reviews,Price,Current_Date asc;



####### Price High to Low;

Set S.No,Name,Reviews,Price,Current_Date from Books Order by S.No,Name,Reviews,Price,Current_Date desc;



######## Newest First:

Select *from Books order by Current_Date desc;



####### Popularity:

Select *from Books order by Reviews asc;
