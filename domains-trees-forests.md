# Domains, Trees, and Forests

A **Domain** is the basic unit of Active Directory.
It shares:
- Same database
- Same policies
- Same security boundaries

Example:
company.local

A **Tree** is a collection of related domains
that share a common namespace.

Example:
company.local  
sales.company.local  

A **Forest** is the highest level in Active Directory.
It is a collection of one or more trees.

Important security concept:
The forest is the **ultimate security boundary**.
Trust exists automatically inside a forest.
