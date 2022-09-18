# Car Dealerships Simple OOP Project
Python Basics & Oriented Objects (Project Deadline 19/09/2022)

For the simplicity of the project, there are only two Entities:
- Car
- Dealership

### Car
- Make
- Model
- Year Manufactured
- Price

### Dealership
- Name
- Address
- **Car list**
- Car storage capacity
- Daily Sales
- Post Code

### Actions
We have two performing actions, one is to store a car in the inventory of one of the dealearships. If the dealership's capacity allows another car to be stored, it allows you to do so, other wise returns an error message that there is no more room left.
Second is to sell a car. If that car is available at the said dealership, it returns a "Sold Car" message and increases the daily sale of that dealership by the price of the car. If the car is not available anymore, it returns an error message stating the car is not available at said dealership.
