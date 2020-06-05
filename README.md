Description: Warehouse management, in future extended to online shop

Database structure:

Product: name, description, time add/update, price, amount, amountReserved, userId
User: name, email, role, time add/update, pass
Category: name, parent
Product_Category: productId, categoryId

Endpoints:

/product (crud operations on product)
get all, get one, add one, update one, delete one

/product/:product/category/:category (add product to category)
