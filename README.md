STELMAKH_CORP — Enterprise Business  
Core for PostgreSQL  
  
Corporate‑grade data architecture for ERP, CRM, HRM, FinTech and GovTech systems    
Perpetual License: 10 000 USD per installation  
  
STELMAKH_CORP is a unified enterprise data architecture designed for companies, holdings and multi‑unit organisations.  
It provides a complete, production‑ready PostgreSQL business core covering legal entities, finance, documents, employees, assets, units and administrative domains.  
  
This architecture eliminates months of design work and serves as a ready‑to‑use foundation for software companies, integrators, startups and enterprise development teams.  
  
Key Advantages  
  
•	Enterprise‑grade architecture validated in real ERP usage  
•	Fully normalised 3NF+ model with strict referential integrity  
•	Modular domain structure (logical domains inside unified public schema)  
•	Hundreds of ready business entities with complete FK mapping  
•	Scalable multi‑unit business model (holding → company → branch →  
unit)  
•	Optimised for PostgreSQL 15–18+  
•	Ideal  foundation  for  	corporate  	data  systems  (ERP/CRM/DMS/HR/Finance)  
  
Domain Architecture (Logical Model)  
  
Legal Entities  t_legal_entity 
t_legal_entity_bank_account  
t_legal_entity_activity  
  
Documents & Workflow  
t_document  t_document_type 
t_document_subtype  
t_document_workflow  
  
Finance & Capital  t_bank_account t_temporary_account  
t_unit_payment  
t_bill t_bill_item  
  
Business Units  t_unit 
t_unit_employee t_unit_address t_unit_activity  
t_unit_process  
  
Sales & Expenses  t_unit_sales 
t_unit_sales_summary t_unit_expense 
t_unit_expense_summary  
  
Assets & Licensing  t_instrument  t_instrument_type t_instrument_subtype  
t_product_license  
    
What You Get  
  
Full PostgreSQL schema (SQL dump)  
This product provides a data architecture only. Application‑level ERP logic is not included.  
  
ERD diagram (grouped by domains)  
Domain documentation  
Installation guide  
Commercial license  
Production‑ready architecture  
  
  
Installation  
CREATE DATABASE stelmakh_corp;  
  
Import the schema:  
psql -U postgres -d stelmakh_corp -f stelmakh_corp_core.sql  
  
System Requirements  
  
Database Engine  
•	PostgreSQL 18+  
•	Fully tested on PostgreSQL 18.4.2  
  
Hardware  
•	Minimum: 2 GB RAM, 50 MB disk  
•	Recommended: 4 GB RAM, SSD storage  
  
Supported OS  
•	Windows 10/11  
•	Linux (Ubuntu, Debian, CentOS, RedHat)  
•	macOS (Intel & Apple Silicon)  
  
Client Tools  
•	psql  
•	pgAdmin 4  
•	DBeaver  
•	DataGrip  
•	TablePlus  
  
Deployment Environments  
  
•	Local development  
•	On‑premise servers  
  
Use Cases  
  
•	Enterprise software development  
•	Corporate system integration  
•	Startup platforms  
•	Internal tools  
•	Financial & administrative systems  
•	Document management  
•	Multi‑unit business operations  
  
Licensing  
  
Commercial Single‑Server License  
•	Perpetual  
•	Non‑transferable  
•	Internal use only  
•	No redistribution or SaaS usage  
•	Additional servers require additional licenses  
•	Full license text included in /Docs/Stelmakh© Corp™  LICENSE.pdf.  
  
Integration, adaptation and ERP implementation are not part of this product and are not permitted under the Commercial Single‑Server License.  
 
Modification Rights (Internal Use Only) 
 
The Licensee may: 
•	extend the database schema 
•	add new tables, fields, indexes or domains 
•	integrate the architecture into internal corporate systems 
•	adapt the structure for internal business processes 
 
All modifications are permitted only within the Licensee’s own infrastructure   (one physical or virtual server per license). 
 
The STELMAKH_CORP Business Core may be installed, used and modified only on a single physical or virtual machine per license. 
Any use outside this single machine — including cloud deployment, SaaS integration, redistribution or embedding into commercial products — is strictly prohibited. 
 
The Licensee is strictly prohibited from: 
•	incorporating the architecture into any commercial product 
•	using it in SaaS, cloud or multi‑tenant services 
•	redistributing modified or original versions 
•	creating derivative or competing database products 
 
All usage is limited to internal, non‑commercial distribution within the Licensee’s organization. 
  
Pricing  
  
 	Package  	                                      Price  
 	Perpetual License (1 server)  	    10 000 USD  
  
Project Structure  
  
stelmakh_corp_core/  
│  
├── stelmakh_corp_core.sql      # Main PostgreSQL schema  
├── README.md                   # Documentation  
└── ERD.png                     # Entity Relationship Diagram  
  
Author  
  
Nikolai Stelmakh  
Brand Manager & Owner  
Stelmakh© Corp™  
Corporate Business Architecture for SQL  
Email: StelmakhCorp@gmail.com  
