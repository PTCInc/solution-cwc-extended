# Disclaimer

To broaden collaboration and facilitate the adoption and expansion of customer solutions, PTC is sharing several field-developed IoT components. 

These artifacts are built using ThingWorx best practices, including the Building Block structure where appropriate, and are available to PTC Customers, Partners, and Customer Success for incorporation and enhancement as needed for specific use cases.

Please note, these components are not covered by PTC Technical Support and are not subject to any Technical Support Service Level Agreements (SLAs). 

However, PTC Customer Success teams and resources will, on a best-effort basis:

* Maintain and manage functionality across ThingWorx platform version releases.
* Actively address reported bugs.
* Continue to enhance functionality opportunistically and by request where possible.

ThingWorx subscription users can continue to log technical support tickets. ThingWorx Platform Technical Support will assist in isolating root causes and addressing platform-related product issues through standard ThingWorx platform maintenance. 

If the issue pertains to this specific component offered via PTC GitHub, PTC Support will direct inquiries to the appropriate internal PTC teams for further assistance.

These shared components are provided "as is," without any warranty, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

# Overview

CWC-eDHR / Extended offers adopters a widely expanded set of CWC functionality to better model their plant floor use cases. For Medical Device customers, specifically, it offers the ability to generate eDHR records on an easily validated GxP environment. The following are flagship features of CWC-eDHR / Extended: 

* Promotion Between Servers - Develop CWC work instructions and routes on one environment, then seamlessly push them to another for execution. Critical for building an optimized QA / Production instance stack. 

* QA Report (eDHR) - View all the details of a product's execution (route) focused on the quality test results gathered throughout. See operator notes and attachments, allow QA to leave comments. Be automatically alerted of exceptions in the product's manufacturing process. In Med Dev use cases, generates your Device History Record. 

* Printable QA Report & Route - Render all the results of the QA Report as a printable PDF for cold storage or distribution to other parties. Concerned about how to operate during an internet outage? Pre-print your entire instructional route to maintain operations during digital outages. 

* Rework / Child Order Mechanism - Model rework scenarios through a parent / child order framework that lets you invoke new instructions built to model rework scenarios. Combine both into one QA Report automatically to see the entire history of a product. Also critical in modeling parent / child lot scenarios where the history of a batch must trace from the parent lot through to all its children. 

* Parallel Work Instruction Execution - Model routes where multiple operations must occur on a single product or batch at the same time. Enables the ability to create routes capturing large scale batch manufacturing and also covers scenarios like guiding line changeover. 

* Fabrication Log Sheets as an Assembly Step Type - The Fabrication module of CWC can now be used as a step type in Assembly execution mode. Provide operators with a  log sheet where they can measure repeat samples. Includes numerous new abilities like datetime grading for calibration checks, e-signature items for sign-in sheets, and mandatory attributes - the ability to vary which measurements are required sample-to-sample. 

* End Point Step Type - Framework to include custom communication with a third-party system (MES, ERP, etc.) as a step in CWC work instructions. Ensure operators are guided to when to sync with an external system, or send results to an external system at a certain point in your process. 

* Per-Step E-Signatures - For validated environments, gather an e-signature with every step to ensure you know who-did-what during the manufacturing process. 

* Four-Eye Approval for Routes & Work Instructions - Want to ensure changes to work instructions and routes are well reviewed before entering production? Enforce two unique signatures per approval with this configurable feature. 

* Audit Report  - One stop shop front end report to see who-did-what-when of actions across the system. Easily searchable and exportable, removes the need to traverse system logs. 

* Pre-Built GxP Document Set - CWC Extended comes prepared with a full document set to accelerate your GxP validation event. Includes URS, FDS, TDS, IQ, Trace Matrix, UAT Scripts and System Manual.

* MPMLink integration to automate work instructions from Windchill process plan and Creo CAD data

This is not a comprehensive list, CWC-eDHR / Extended contains many more quality of life, authoring, reporting, and auditability functionality. 

# License

## PTC Proprietary Freeware License

I accept the PTC End User License Agreement (https://www.ptc.com/en/documents/legal-agreements/on-premise-license-agreements) and agree that any software downloaded/utilized will be in compliance with that Agreement.  However, despite anything to the contrary in the License Agreement, I agree as follows:

I acknowledge that I am not entitled to support assistance with respect to the software, and PTC will have no obligation to maintain the software or provide bug fixes or security patches or new releases.

The software is provided “As Is” and with no warranty, indemnitees or guarantees whatsoever, and PTC will have no liability whatsoever with respect to the software, including with respect to any intellectual property infringement claims or security incidents or data loss.
