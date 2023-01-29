# Metabase & Odoo

Playground to build dashboards and questions in Metabase on Odoo's schema

## How to run

1) Install Docker
2) Clone this repository
3) docker-compose up on the root of the repository you just cloned
4) Wait some time till Odoo and Metabase spin up
5) Enter Odoo @ http://localhost:8069/ with admin:admin
6) Enter Metabase @ http://localhost:3000 with a@b.com:metabot1

## What do you have

- Odoo pre-provisioned with stock,account,purchase,sale_management modules (you can add the ones you want in the docker-compose.yml file)
- Metabase pre-initialized with an admin user and with the Odoo database added to play with the data

## Pendings

- Complete all Metabase Data Model to grab all the metadata so Metabase can offer all its power in questions and dashboards (e.g. configuring boolean fields to a boolean in Metabase, a categorical field to a category, etc)
- Build questions and dashboards that make sense