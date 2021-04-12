# *Eau Claire's Salon*

#### *Eau Claire's Salon, 4/12/2021*

#### By **Chris Ramer**

## Description

Application to help manage a salon's employees and clients.

## Setup/Installation Requirements

Clone this repo.

Download & setup MySQL Workbench if you haven't already.

In MySQL Workbench, in *Navigator -> Administration* window, select *Data Import/Restore*.

In *Import Options* select *Import from Self-Contained File*.

Navigate to this repo's `Chris_Ramer.sql` file.

Enter a custom name for this database and click *Ok*.

Click *Start Import* to import the database.

With the database in your system, run terminal command `dotnet run` from the `HairSalon` directory. Then open `localhost:5000` in your browser.

## Specs

* **Spec:** Adding a new stylist will add that stylist to a list of all stylists
* **Input:** Stylists with names Luna and Joseph
* **Output:** Redirects to a page showing stylists Luna and Joseph

* **Spec:** Adding a new client will store that client to a list of all clients for that stylist
* **Input:** Clients with name Chris and Steve
* **Output:** Redirects to a page showing clients Chris and Steve

* **Spec:** Clicking the link for a stylist shows their details
* **Input:** Stylist with name Luna and a few clients
* **Output:** Redirects to a page showing each of Luna's clients

* **Spec:** Clicking the link for a client shows their details
* **Input:** Client with name Chris
* **Output:** Redirects to a page showing Chris' details

## Technologies Used

* C#
* ASP.NET
* .NET Core

### License

Copyright (c) 2021 **Chris Ramer**
This software is licensed under the MIT license.