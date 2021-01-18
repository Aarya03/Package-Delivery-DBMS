# Package-Delivery-DBMS
This is a Dtabase application that can be useful for a package delivery company (similar to FedEx, UPS, DHL, the USPS, etc.)

# Diagrams
<b>ER(Entity Relationship) - Diagram</b>
<p align="center">
  <img src="Diagrams/ERD.png" width="720" title="ER(Entity Relationship) - Diagram">
</p>
<p> <b>Description of ERD:</b></br>
● 1-1, 1-N and N-N lines depicts One-to-One, One-to-Many and Many-to-Many respectively.</br>
● Green Color Rectangles are Entities and Double Walled Rectangles are Weak Entities.</br>
● Grey Color Diamonds are Rectangles.</br>
● Maroon colored Circles are attributes and Double Walled Circles are Multivalued.</br>
</p>

<b>Relational Model</b>
<p align="center">
  <img src="Diagrams/RM.png" width="720" title="Relational Model">
</p>
<p><b>Description of Relational Model:</b></br>
● Green colored tables are Relational Tables(PackageDelivery and Tracking)</br>
● Customer to PackageDelivery is a One-to-Many relationship since one Customer
can ship multiple Packages.</br>
● Customer to Transaction is a One-to-Many relationship since one Customer can do
multiple Transactions.</br>
● Package to PackageDelivery is a One-to-One relationship since one Package can
have only one Receiver.</br>
● Package to Tracking is a One-to-Many relationship since one Package can have
multiple Locations at different times.</br>
● Package to International is a Weak One-to-One relationship.</br>
● Service to Transaction is a One-to-Many relationship since the same service can be
used by multiple transactions.</br>
● Vehicle_Warehouse to Tracking is One-to-Many relationship since the same vehicle
or warehouse can have multiple packages.</br>
● Package to Transaction is a One-to-One relationship since one package can have
only one transaction.</br></br>

<b>Description of Main Tables:</b></br>
● Customer table contains all the details like address, phoneNo, etc of each Customer.</br>
● Service table contains all the details like ServiceType (like Prepaid, Postpaid, etc) ,
PackageType, etc.</br>
● Transaction table contains details of all transactions for each PkgID.</br>
● Package contains description of Package, its categories etc</br>

</p>
Links for Video Presentation, PDF and CSV Files -> https://drive.google.com/drive/folders/1hbA60C8pDK4Yrs8OClDGCUKH-RwI6ONf?usp=sharing
