# mysql-structure

# optica.sql
This SQL file defines the database structure for the "Cul d'Ampolla" optician's management system. It includes tables for:

## Clients:
personal data, address, contact, registration date, and referral source.

## Glasses:
brand, lens gradation, frame type and color, lens color, and price.

## Providers:
complete contact information and tax ID.

## Employees:
who sold each pair of glasses.

The schema reflects the business rules: each brand is associated with a single provider, but one provider can offer many brands. Referrals and seller tracking are also included.

# pizzeria.sql
This SQL file defines the database structure for an online food ordering system for a pizzeria. It includes:

## Clients:
names, contact data, and location info (split into cities and provinces).

## Orders:
date/time, delivery/pickup option, total price, and quantity of each product.

## Products:
pizzas, burgers, and drinks, with descriptions, images, and prices.

## Pizza Categories:
pizzas are assigned to one category.

## Stores:
locations managing orders.

## Employees:
role (cook or delivery), assigned store, and delivery tracking with timestamps.

The schema supports flexible product management, employee roles, and regional hierarchies for addresses.
