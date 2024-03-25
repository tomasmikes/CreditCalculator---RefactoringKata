TODO:

Company
- Static instances should be in repository
- Type as enum?

Customer
- has no id
- should have only company id and not entire object

CustomerRepository
- redundant GetCustomers property

CustomerService
- AddCustomer should accept Customer as parameter
- Customer validation should go in Customer class IsValid method
- Repository should be constructor injected
- 