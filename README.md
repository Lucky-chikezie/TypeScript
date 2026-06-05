# TypeScript
People Filter Utility
This little TypeScript project is a demo for working with union types and filtering objects. It defines two kinds of people — users and admins — and lets you filter them by type and criteria (like age). Nothing fancy, just a neat example of how to combine type safety with simple data handling.

##What’s Inside

*Types
  -RegularUser: has a name, age, and occupation.
  -SuperAdmin: has a name, age, and role.
  -Person: union of the two.

*Data
  -A sample people array with a mix of users and admins.

*Functions
  -showPerson: prints a person’s details in a clean format.
  -filterPeople: filters by type (user or admin) and any matching criteria.

##How to Run
-Clone or copy the code.
-Make sure you’ve got TypeScript set up (npm install -g ts-node if you don’t).
-Run it with:
-> ts-node index.ts
#Example Output
Code
Users aged 23:
 -> Ade Solomon, 23, Accountant
 -> Wilson Harrison, 23, Footballer
Admins aged 23:
 -> Agent Smith, 23, Electrical Engineer

#Why It’s Useful
-Shows off union types and type narrowing in practice.
-Demonstrates filtering with dynamic criteria.
-Easy to extend — you could add more properties, or build a CLI around it.

#Ideas for Extensions
-Add fuzzy matching (e.g., occupation contains “Teacher”).
-Sort results by age or name.
-Hook it up to a database or API.

###That’s pretty much it — I hope this makes the code easier to follow. 
