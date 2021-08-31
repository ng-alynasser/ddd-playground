## Big Picture
A domain, in the broad sense, is what organization does and the world it does it in.
Businesses identify a market and sell products and services. Each kind of organization
has its own unique realm of know-how and way of doing things. That realm of understanding
and its methods for carrying out its operations is its domain. When you develop software
for an organization, you are working in its domain. It should be pretty obvious to you
what your domain is. You work in it.

Domain can refer to both the entire domain of the business, as well as just one core
or supporting area of it. When referring to just one area of the business, I will
generally qualify it with the use of Core Domain, Subdomain, and the like.

Almost every software domain has multiple subdomains. It really doesn't matter whether
the organization is huge and extremely complex or consists of just a few people and
the software they use. There are different functions that make any business successfull,
so it's advantageous to think about each of those business functions separately.

### Subdomains and Bounded Contexts At Work:
Here's a fairly simple example to introduce how Subdomains can be used. Think of a retail
company that sells products online. To do business in this domain, the company must present
a catalog of products to shoppers, it must allow orders to be placed, it must collect
payment for the products sold, and it must ship products to buyers. This online retailer's
domain seems to be composed of these four primary subdomains: Product Catalog, Orders,
Invoices, and Shipping.

Notice that at this time just three physical systems exist to realize this retailer's
domain, only two of which are hosted internally (E-Commerce System and Inventory System).
Those two internal systems represent what we might think of as two Bounded Contexts.
Inside the e-Commerce Bounded Context there are really multiple implicit domain models
at play, even though they are not clearly separated as such.
