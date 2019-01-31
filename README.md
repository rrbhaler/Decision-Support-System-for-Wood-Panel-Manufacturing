# Decision-Support-System-for-Wood-Panel-Manufacturing

The objective of this project is to build a decision support system for a wood panel manufacturer. This system will allow the company to identify ways to improve their processes and minimize costs of manufacturing. Wood panels are manufactured using small pieces of wood (for example, chips, flakes, splinters, strands, shreds, etc.) that are bound together using an organic binder. There are a number of raw materials that can be used to produce these wood particles. Manufacturers have flexibility in selecting the raw materials. 
There are a variety of wooden panels, and each one has distinguished properties. Depending on their usage, wood panels have different quality requirements. For example, quality requirements for wood panels used in middle layers are different from quality requirements for wood panels used in outer layers. The total production of a wood panel manufacturer depends on the following: (a) the type of raw materials used and (b) the quality requirements for the final product. 
Database Design 
We present below the main entity types of this database. For each entity type, we provide some of the corresponding attributes. Use this information in order to: (a) Build an Enhanced E-R diagram; (b) Transform the Enhanced E-R diagram to a relational database. Identify the primary key(s) and the foreign key(s) for each relation. Draw the relational integrality constraints; (c) Indicate the normal form of each relation created. If the relation is not in the 3NF, decompose it into 3NF relations. 
1.	Raw Material: The main attributes are identification number, name, description, unit cost, expected monthly consumption, inventory level, etc. 
2.	Final Product: The main attributes are identification number, name, description, unit cost, unit price, expected monthly production, current inventory level, list of raw materials and corresponding quantities needed to produce one unit of the final product, density requirements, etc. 
3.	Equipment: The main attributes are identification number, name, location, capacity, etc. 
Note the following: (a) When a raw material is used to produce a particular product, the following information is recorded: transaction identification number, date, amount of final product produced, quality level of the final product, amount of raw material used, cost of raw material, etc; (b) A final product can be produced using different combinations of raw material. Depending on the type of the raw material used and quantity used, the resistance and quality of the final products varies; (c) Particular equipments cannot be used to process all the raw materials and produce all the final products. Also, the yield of a final product depends not only on the type of raw material, but on the equipment used as well. Therefore, the database keeps track of the following: (i) the raw materials that equipment can process; (ii) the final products that equipment can produce; and (iii) the yield of the final products produced on that equipment. 
157 
Access Application Development 
The following are some of the queries, forms, and reports one can create in order to increase the functionality of the database: 
Queries: 
1.	Create a query that prompts for the name of a raw material and lists the name of the final products that can be produced using this raw material. The list should also contain the quantity of raw material needed to produce one unit of final product. 
2.	Create a query that prompts for the name of a final product and presents a list of the raw materials that can be used. Present the quantity needed of each raw material to produce one unit of the final product. 
3.	Create a query that prompts for the name of an equipment and presents a list of the final products that can be produced using this particular equipment. 
4.	Create a query that presents for each final product the total production in the current year. 
5.	Create a query that presents for each raw material the total consumption in the current year. 
6.	Create a query that prompts for the name of a final product, a quality level, and a resistance level and returns the combination (type and quantity) of the raw materials that would produce the required final product. 
Forms: 
1.	Create a user sign-in form together with a registration form for new users. 
2.	Create the following data entry forms that are used for database administrative functions: final products, raw materials, equipments, etc. These forms allow the user to add, update, and delete information about final products, raw materials, equipments, etc. 
3.	Create a form that allows the user to choose the name of a final product from a combo box. Create a subform that presents the name and quantity of the raw materials that can be used to produce one unit of the selected final product. Insert a textbox that presents the cost of producing one unit of the final product. Insert another textbox that presents the price per unit of this final product. 
4.	Create a form that allows the user to choose the name of a raw material from a listbox. Create a subform that presents a list of products that contain this raw material. Present the number of units of the selected raw material needed to produce one unit of each final product. 
5.	Create a form that allows the user to browse through the information about the equipments. Create a subform that lists the name of the final products that can be produced on the selected equipment. For each final product present the corresponding production yield. Create a subform that lists the names of the raw materials that can be processed on the selected equipment. 
Reports 
1.	Create a summary report that presents the production amount for each final product. The report should include the following: unit production cost, total cost, unit price, sales, and earnings from sale. 
2.	Create a summary report about the raw materials used. The report should contain the following information: unit cost and total consumption. Calculate the overall cost of raw materials. 
3.	Create a report that presents for each final product the raw material (name and quantity) combination that gives the highest resistance and quality. Present the cost of producing one unit of the final product and corresponding sale price. 
4.	Create a summary report for the equipments. The report should present the name of the equipments owned by the company. For each equipment, present the amount and name of final products produced in the current year. 
5.	Use the chart wizard to plot the following: 
1.	Production quantity for each final product per year during the last ten years. 
2.	Earnings from sales of each final product per year during the last ten years. 
3.	For each raw material, the amount used per year during the last ten years. 
4.	For each raw material, the unit cost paid per year during the last ten years. 
