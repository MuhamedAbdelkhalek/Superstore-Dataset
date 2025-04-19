SELECT 
  "Product Name",
  Category,
  Sales,
  SUM(Sales) OVER (PARTITION BY Category) AS TotalCategorySales
FROM Sample; -- In order to know total sales for each category



HON 5400 Series Task Chairs for Big and Tall	Furniture	4416.174	1
GBC Ibimaster 500 Manual ProClick Binding System	Office Supplies	9892.74	1
Cisco TelePresence System EX90 Videoconferencing Unit	Technology	22638.481   1