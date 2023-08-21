# sample_flipcart

We can implement the filters where we can create Filterable interface which supports filter functionality.
When this interface is implemented by the product catalog class then it starts to support the filter functionality.

1. We can add multiple sellers because they are just the type of user. So, we draw generalization between all the sellers.
2. The product catalog is having one to one composition relationship with the system(myFlipCart).
3. The system(myFlipCart) will have one to many composition relationship with users.

4. Since the product catalog has one to many aggregation with categories.
5. We can have sub-categories and based on the features like color, size, etc., we can create one to one or one to many aggregation between them.
