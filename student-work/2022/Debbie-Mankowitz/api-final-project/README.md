# Hamburger API DOC
This API is for creating a new APP for General Putnam Motel Diner (GPMD).  Customers of GPMD can use the app to order food. This initial offering is a Proof of Concept (PoC). 

It is limited in scope and the preliminary version only supports creating a take-out hamburger meal order.
If the PoC is accepted, the App can be expanded so that GPMD can extend their APP to include other offerings on their menu.
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




