# Flipbooks
##Tables

#### Table 1: Books

|s:no|Book_Name|Price|Popularity|NewestFirst|
|----|---------|-----|----------|-----------|
|  1 |  Java   | 300 |    5     |22/08/2019 |
|  2 |   c     | 500 |    2     |21/08/2019 |
|  3 |  c++    | 500 |    4     |20/08/2019 |
|  4 | Python  | 700 |    3     |19/08/2019 |
|  5 |  J2ee   |1000 |    5     |22/08/2019 |

#List All Books_Price Low to High

`
select Book_Name from Books order by price ASC;
`

#List All NewestFirst  High to Low 

`
select NewestFirst from Books order by price DESC;
`

#List All s:no  High to Low 

`
select s:no from Books order by popularity DESC;
`

