> ⚠️ xxxBREAKING CHANGESxxx

> ❗ xxxImportant upgrade informationXXX

> 💡 xxxMinor upgrade informationXXX

### New feature: xxxx

- xxx

### Stock

- Added a new product picker workflow "External barcode lookup (via plugin)"
  - This executes the configured barcode lookup plugin with the given barcode
  - If the lookup was successful, the product edit page of the created product is displayed, where the product setup can be completed (if required)
  - After that, the transaction is continued with that product
- Fixed that for the product's last price stock transactions with an empty or `0` price weren't ignored
- Fixed that when copying a product, the field "Move on open" wasn't copied along

### Shopping list

- The shopping lists dropdown on the shopping list page now also shows the number of items on the corresponding shopping list

### Recipes

- Optimized that when creating a recipe, the desired serving amount is now initially prefilled by the recipe's base serving amount

### Meal plan

- xxx

### Chores

- xxx

### Calendar

- xxx

### Tasks

- xxx

### Batteries

- xxx

### Equipment

- xxx

### Userfields

- xxx

### General

- Optimized that file uploads are not completely buffered in memory before writing them to disk (thanks @bbx0)

### API

- xxx