# sulipySQL

1.Feladat
  Írj SQL utasítást amely az online tesztadatbázis 'Categories' táblájából lekérdezi

a, az összes adatot:
  
  SELECT * FROM Categories;

b, a 'CategoryName' oszlopba tartozó adatokat,: 
  
  SELECT CategoryName FROM Categories;

c, a 'CategoryName' és 'Description' oszlopba tartozó adatokat! :
  
  SELECT CategoryName, Description FROM Categories;
  
2. Feladat
Írj SQL utasítást amely az online tesztadatbázis 'Products' táblájából lekérdezi 

a, a 'ProductName', 'Unit' és 'Price' oszlopba tartozó adatokat,:

  SELECT Productname, Unit, Price FROM Products;
  
b, azon termékek nevét és árát, amelyek ára 20-nál kevesebb,:

  SELECT ProductName, Price FROM Products WHERE Price < 20;
  
c, azon termékek nevét és árát, amelyek ára 20 és 30 közé esik,:

  SELECT ProductName, Price FROM Products WHERE Price BETWEEN 20 AND 30;
  
d, azon termékek nevét és árát, amelyek ára nem 10:

  SELECT ProductName, Price FROM Products 
  WHERE NOT Price=10;

e, a 'T' betűvel kezdődő temékek nevét, :

  SELECT ProductName FROM Products WHERE ProductName LIKE 't%';
  
f, azon termékek nevét, amelynek neve a 'Louisiana' szóval kezdődik! 

  SELECT ProductName FROM Products WHERE ProductName LIKE 'Louisiana%'
  
3. Feladat
Írj SQL utasítást amely az online tesztadatbázis 'Suppliers' táblájából lekérdezi az országokat ismétlődés nélkül!

  SELECT DISTINCT City FROM Suppliers;

    






























































