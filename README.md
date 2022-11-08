<div align="justify">
# Odoo: Getting started

Repository for learning Odoo

---

## Chapter 1: Architecture Overview
### Multitier application

Odoo follows a three-tier architecture, separating the presentation, the business logic and the data storage. 

In this image provided by wikipedia we can see a representation: 

<img src="img/three_tier.svg">

Each tier is always implemented using the same tools in order to make different odoo modules compatible with each other. 

* Presentation tier: HTML5, JavaScript, CSS
* Logic tier: Python
* Data tier: PostgreSQL (RelationalDBMS)

### Odoo modules

Definition: "A module is a collection of functions and data that target a single purpose".

The main userfacing modules are refered to as *Apps*.

The majority of modules are refered to as *addons*
and the directories where the Odoo server finds them form the *addons_path*. 

</div>

