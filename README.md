# Active-directory
All about windows AD Offensive hacking

## Table of content
- [What is active directory](#what-is-active-directory)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## what is active directory
From my perspective, Active Directory is a system that allows to manage a set of computers and users connected in the same network from a central server.

Sure, this definition is far from being totally accurate, but I hope it is simple enough to give you an idea of what AD is.


Active Directory network
Imagine a company with hundreds of employees, where each one works in its own (probably Windows) computer. This company has several different departments, like sales, human resources, IT, etc.

Now imagine that the sales department requires a new program to be installed in their workstations. Or that each day an user in a different office forgets its password and it needs to be restored. Or that the new group of interns are only required to work with a few documents of a file server.

Should the IT team install the program in all the sales workstations, one by one? Should they go to the different offices and restore the user password? Should they create a new user for each intern in the file server that allows only to see files in a directory?

Well, they could do that, though it would be a lot of work (and a waste of money for the company). But since they are smart people, they have all the computers connected in an Active Directory network, so they can perform all these operations from their workstation.

Active Directory allows this by maintaining a centralized database where all the information about users, computers, policies, permissions, etc, is stored. So, for example, the IT team can connect to this database and create the new users for the interns and assign permissions to them to be only allowed to read files in the indicated directories of the specific servers of their departments.

Then, when one of these interns tries to login to a computer inside the Active Directory network, the computer consults the central database in order to check that the intern user exists (and that the password is correct). This way, users can log on to any of the company computers (if they have permissions), by allowing employees to use only a user to do all its work in all the company computers (that can be workstations, database servers, file servers, etc).

Likewise, in case a user forgets is password, she can alert to the IT team, and they can change the user password in this central database (and the user is asked to change this password to a new one that only she knows).

In the case of the sales department, the IT can create a new policy in the database which indicates that computers of that department must install the indicated program, and how they must do it. Then, when sales workstation read the database, they will know that they must execute this policy and the new program will be installed.

I hope this example allows you to understand why Active Directory is so useful and why almost any (medium-big) organization in the world uses it. Probably you have used it, normally from a computer that requires you to press Ctrl+Alt+Del before prompts you for your username and password.

And… what happens if someone can steal the password of an IT user? Could she change the other users passwords? And access to the database?

Now that is clear why Active Directory is so important, let's introduce their items.

## Installation
These are the steps you need to follow to install my project.

## Usage
Here are some examples of how to use my project.

## Contributing
This is how you can contribute to my project.

## License
This is the license that my project is released under.
