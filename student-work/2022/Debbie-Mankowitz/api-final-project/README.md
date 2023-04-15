# Hamburger API DOC
This is the new APP for customers for online orders for General Putnam Motel Diner (GPMD). 

This App is intended for customers as a preliminary version for take-out hamburger meals.
If the App becomes popular and easy to use then GPMD will extend their APP to include other offerings on their menu.
This App is the interface between the customers and the restaurant.
Via this App the restaurant is able to seamlessly pass on the orders to the chefs in the GPMD kitchen.
The GPMD Chefs then prepare the meals for delivery.

REST APIs are used to transfer data and are preferred as REST is flexible and its reusability is preferred 
when modules as in this instance of the GPMD menu are added, substituted, or adjusted.
It uses HTTP protocol to fetch data or carry out operations in several data formats, in this instance, JSON which allows for quicker processesing.

These methods are used by the Hamburger API:
* [GET] (get.md)-data is retrieved from the server; GET the bill.
* [POST] (post.md)-data is sent to the service; customer's order which is then printed for the chef in the kitchen.

## Workflow

```mermaid
Flowchart TD;




