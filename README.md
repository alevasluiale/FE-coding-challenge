# Frontend Challenge 

Create a small application with data obtained from API:
  - Get data from the API https://dummyjson.com/products?limit=100 . Handle the loading state with some indicator or text.
    Once when you get data, **sort** all products by **price** from the **most expensive** and take the **20** most expensive       and present them in the small table.
  - Table should contain the following cells: **title**, **price**, **discountPercentage**, and **category**.
  - Present **discountPercentage** with different colors in the following cases:
      * In case that discountPercentage is **less** than 15 -> green
      * In case that discountPercentage is **bigger** than 15 -> orange
  - By clicking each row you should get a single page of the clicked product. You should call the API https://dummyjson.com/products/{id} and get the single product. Once when you receive data, list all items from the response except images.
