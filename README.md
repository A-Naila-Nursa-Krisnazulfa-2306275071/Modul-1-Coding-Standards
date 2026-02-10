# Modul-1-Coding-Standards

Refkections on what I did for the Eshop Project:
* Clear and Precise Naming: I used simple method names like create, findAll, and deleteProductById. This makes it easy for anyone to read and understand what the code does.

* Organised Layers: I kept the logic in the Service layer, this means I separated it from the Controller and Repository so the code stays organised.

* Security: By handling all data changes in the Service layer, I added a layer of protection where I prevented the Controller from having any impact with the database directly.

what could be improved from the code I have made:
* Redundancy Code: In Java, methods inside an interface are already public by default and it was already declared to be a public Interface. I can remove the word public from those methods to make the code shorter.
