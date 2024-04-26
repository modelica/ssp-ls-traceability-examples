**Administrative Information**

Every company or even divisions in a company have specific ID, names. To support this mapping there are several possibilities. One possibility is the use of the derivation chain of the STMD format. From the exporting tool (data management system) the mapping of the specific ID, name is made. This also has the advantage that the identifiers between the companies do not have to be transparent.

* **(Overall) Product, Project** (recommended)
    * **ID, URI**
        ID, URL of overall product, project
        * P987658
    * **Name, Description**
        The product/project information expresses the in-house description of a product. The description can consist of a (not necessarily self-explaining) name or an acronym (e.g. EHAV3.4). The entry is supported by a classifier which also allows free text input.
        * Electro Motor window lifter Variant AAA-55
    * **Selfexplaining name**
        The meta data provides a self-explaining name which allows a natural mapping to the product/project (e.g compressor and injection valve). The meta data may be identical with the product/project name if this is suitable for a meta data search.
        * Window lifter, variant ddp, platform xx
* **Ordering Project, corresponding (Sub-) product** (mandatory)
    * **ID** (mandatory)
        A number identifying an order placed by a customer in the parent system This is essential for a seamless traceability.
        * E98765834
    * **Name** (optional)
        description of the commissioning project
        * Electro Motor window lifter Variant AAA-55
    * **Selfexplaining name** (optional)
        The meta data provides a self-explaining name which allows a natural mapping to the parent product/project
        * Electro Motor, window lifter, Variant AAA-55
* **Version No of Request** (optional)
    Associated with life cycle information. Order clarification is usually iterative process Engineering order reflects status.
    * Version 42
* **Simulation Request** (mandatory)
    * **ID** (mandatory)
        The unique number for the simulation task to identify the simulation order (e.g. SPDM ID).
        * R424242
    * **Name** (optional)
        Name can be Simulation Request xxx (Number or name)
        * Simulation Request for Electro Motor window lifter Variant AAA-55
    * **Selfexplaining name** (optional)
        The meta data provides a self-explaining name which allows a natural mapping
        * Simulation Request, Electro Motor, window lifter Variant AAA-55, Variant
* **Inserted by** (optional)
    The person who processes the simulation order and submits it to the system.
    * FG/SIM P. Bauer
* **Date**\* (mandatory)
    The date at which the simulation order is submitted to the system. This must be generated automatically in the system.
    * 2024.02.01 14.25.30
* **Customer** (mandatory)
    The company and entity with person who placed the simulation order to obtain a simulation service. This person acts as the counterpart to the consignee.
    For Usage with internal and external customers separates field for company and person with entity name, abbreviation for easier evaluation of the metadata
    * Company A Dep X Carla Miller
* **Consignee/Contractor** (mandatory)
    The company and person with entity who accepts the simulation order and acts as the technical contact person.
    * Company B Dep SIM A. Huber
* **Order Date** (optional)
    The order date represents the date at which the simulation service shall start.
    * 2024.01.30 12.30
* **Requested Delivery Date** (optional)
    The date at which the simulation service shall be completed.
    * 2024.03.30 12.30
* **Life Cycle Information of Order** (optional)Typically drafted, defined, accepted, in progress, fulfilled, archived, rejected,
    * in progress
* **connected process** (mandatory)
    * **ID** (mandatory)
        * SIM123456
    * **Name** (optional)
        * SimTask Electro Motor window lifter Variant AAA-55
    * **Selfexplaining name** (optional)
        * SimTask, DC-Motor, Electro Motor window lifter, Variant AAA-55