# Lab : Creating and securing a web api with Microsoft Identity

## Create an Azure AD Application
* Go to the activve directory admin center and register a new application
* Once the application is registered copy the         
    * Copy the Application (client) ID and Directory (tenant) ID 
* In the admin center be sure to select **Expose an API** and accept the the proposed Application ID URI as,
``` api://{clientId}``` 
* Add the following scopes for your application
    
### Scope: Product.Read
* **Scope name**: Product.Read
* **Who can consent**: Admins and Users
* **Admin consent display name**: Read Product Information
* **Admin consent description** : Allows the app to read product information
* **User consent display name** : Read Prodcut Information
* **User consent description** : Allows the app to read product information
* **STATE** : Enabled

### Scope: Product.Write
* **Scope name**: Product.Write
* **Who can consent**: Admins and Users
* **Admin consent display name**: Write Product Information
* **Admin consent description** : Allows the app to write product information
* **User consent display name** : Write Prodcut Information
* **User consent description** : Allows the app to write product information
* **STATE** : Enabled

### Scope: Category.Read
* **Scope name**: Category.Read
* **Who can consent**: Admins and Users
* **Admin consent display name**: Read Category Information
* **Admin consent description** : Allows the app to read category information
* **User consent display name** : Read Cateogory Information
* **User consent description** : Allows the app to read category information
* **STATE** : Enabled

### Scope: Category.Write
* **Scope name**: Category.Write
* **Who can consent**: Admins Only
* **Admin consent display name**: Write Product category information
* **Admin consent description** : Allows the app to write product category information
* **STATE** : Enabled


## Running the project 
After creating the Azure AD application. Copy the following values from your application: 
 * Domain 
 * Tenant ID
 * Client ID

