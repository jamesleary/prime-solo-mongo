
Open mongo shell
[] Type use antares to create your database (or use an existing database)
GitHub repo

Create a GitHub repo named “prime-solo-mongo”.
[x]Create a file called “mongo.txt”. You will store your responses to the exercise questions here.


For each of the following questions

Write a comment that specifies which question you are answering. Use JavaScript comment syntax.
Write the Mongo query that answers the question, below that comment.

Example question and answer

// 0. Create a collection named orders
db.createCollection('orders')
Tasks

[]Create a collection named orders.
[]Insert at least 3 documents that represent an order. IMPORTANT: See section below for fields. Order dates should be: 2017-02-03, 2017-04-04, 2017-01-02
[][Find all orders and make them look pretty.
[]Find all orders with an orderDate that is after 1/31/2017.
[]Change the orderTotal from 2/3/2017 to 63 dollars (you do NOT have to ensure the lineItems' unitPrice * quantity add up to the orderTotal)
[]Add another lineItem to the order from 4/4/2017
[]Change the first lineItem in the order from 1/2/2017 to be for 2 'transistor radio's
[]Find orders with lineItems that have a quantity that is less than 10, but greater than 2. You will have to research $and
order fields

Your orders need to have the following fields:

orderDate -- see https://docs.mongodb.org/manual/reference/method/Date/
orderTotal
lineItems -- a sub-document (array) that can accommodate many line items with fields: unitPrice, quantity, productName
