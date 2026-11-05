# Executive Financial Performance Dashboard

This repository contains a fully interactive Power BI application designed to transform raw transaction records into strategic business insights for corporate stakeholders. 

## The Project Journey (Data to Design)

This dashboard began with a massive, unorganized CSV dataset containing over 5,000 rows of raw transaction data spread across 39 unfiltered columns. To turn this raw data into an executive-ready asset, I systematically executed an end-to-end analytics workflow:

1. Data Cleaning and Normalization: I imported the messy source file, stripped out redundant variables, and split the flat columns into distinct logical groupings. 
2. Relational Architecture: I built a formalized database framework by connecting our transaction ledger with dimension tables for Dates, Products, Regions, and Segments.
3. Star Schema Implementation: To guarantee performance and clean filtering, I locked in an optimized Star Schema model. Relationships are strictly mapped as 1-to-many single-direction filtering contexts.
4. Calculated Core Metrics: I separated my business logic from the raw data fields by creating an isolated measures table. Inside, I programmed and formatted base financial metrics like Net Revenue, Total COGS, and Gross Profit, along with custom dynamic text overrides.
5. Interactive UI Visualization: Finally, I mapped out the visual canvas using an intentional Emerald Growth and Sage Mint design theme. The dashboard features localized interactive filter panels, dynamic text elements, and smooth visual grids built specifically to accommodate executive decision-making.

---

## Repository Contents and Deliverables

This repository functions as a complete digital project package. The items included in this workspace are detailed below:

### Core Application Asset
* Executive_Financial_Dashboard.pbix
  The primary Power BI project file containing the active data model, complete calculations, and the live interactive report layout.

### Project Visual Proofs (Screenshots)
Three high-resolution snapshots are provided to demonstrate the layout and system backend without needing to open the raw workspace file locally:

1. dashboard_global.png
  The Global Summary View: Displays the entire structural canvas grid operating at its macro layer with no interactive filters selected.

2. dashboard_filtered.png
  The Interactive Cross-Filter Test: Showcases the dashboard in an active state, slicing into specific regional markets to visually prove that the interactive maps, text overrides, and calculation engines adapt instantaneously.

3. data_model_schema.png
  The Blueprint View: A complete snapshot taken directly from the Power BI Model Workspace, showcasing the fully verified, clean Star Schema relationship network.
