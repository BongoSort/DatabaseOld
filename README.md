# Description

From the course Database Systems

Authored by Rune Schuster, except for the Data itself, listed under "-- Just filling in data --".

This project creates a database schema called NGOs4 to manage data related to non-governmental organizations (NGOs), their supporters, and donations. It consists of four main tables:

* NGO: Stores details about each NGO, including name, location, cause, director, contact information, and revenue.
* Supporter: Contains information about supporters, such as their name, email, phone, address, birthday, and other personal details.
* Supports: Tracks the relationship between NGOs and supporters, including whether the supporter is a volunteer and their involvement level.
* Donations: Records the donations made by supporters to NGOs, including the amount, activity, and date of the donation.

The schema also includes various data validation checks (e.g., email format, phone number format) and foreign key relationships to ensure data integrity. Sample data is inserted to illustrate the structure, including details of several NGOs and supporters.
