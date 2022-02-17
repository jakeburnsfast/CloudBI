## Business Intelligence Implementations | by Jake Burns
<details><summary>About Jake</summary>
<p>
I have 10+ years of report development experience, including forecasting, digital marketing analysis, geo-applications, healthcare, commercial services, and manufacturing.  I currently work full time as a data warehouse developer at Blue Margin, Inc. where I am blessed to be constantly learning from new clients and BI applications in the Microsoft cloud infrastructures.
<p></p>
I offer consulting services on the side and am able to work with clients M-F prior to 10AM EST, and Saturdays as needed.  An initial implementation of a BI system (detailed below) can be 100 or 1,000 hours (and anything in between) so I am only able to take on "right-size" work that makes sense for the client.
</p>
<a href="https://www.linkedin.com/in/jakeburnsoh/">LinkedIn Profile</a>
</details>

---
### Source data extraction through report delivery 
##### Simple | Durable | Transferrable
<br>

#### <u>Principles</u>
##### Development work is calibrated to be:
* **Simple**: Clean, refined code and processes mean less technical debt, shorter time to fix, and less overall cost
* **Durable**: Solutions written on proven standards, best practices, and widely used technologies will break less over time
* **Transferrable**: Thorough, consistent documentation means solutions can be passed to other developers will less time lost or risk for a full rebuild

#### <u>Pricing</u>
##### Fixed price based on:
* Number / nature of source systems
* Landscape of desired reporting
* Complexity of transforms

#### <u>Platform</u>
##### Microsoft Azure family of resources:
* Full toolset available (extraction, staging, modeling, reporting)
* Integration friendly  (data sources / non native languages)
* Flexible pricing 

#### <u>Process</u>
##### Eight phases of development:

<img src="https://raw.githubusercontent.com/jakeburnsfast/CloudBI/main/Process.png" alt="Process" style="zoom:70%" />

1. Assimilate (business areas, current report authorship)
2. Design (define metrics needed, source systems, infrastructure)
3. Extract (attach applications / pipelines to source data) (**AS NEEDED**)
4. Load (replicate source data in data lake) (**AS NEEDED**)
5. Stabilize (optimize performance/cost, ensure daily synchronization) (**AS NEEDED**)
6. Transform (construct star schema data models to enable reporting)
7. Validate (ensure the data models provide accurate intelligence)
8. Present (deliver intelligence through reports)
   <br><br>

# Phase Details
### 1. Assimilate

<img src="https://raw.githubusercontent.com/jakeburnsfast/CloudBI/main/1_Assimilate.png" alt="Assimilate" style="zoom:30%" align=left />

>* Meet with project sponsors to grasp their vision
>* Review current reporting assets / environment
>* Meet with developers / analysts / report consumers
>* Clearly grasp how the organization currently uses data
>* Gauge in-house technical skill and capacity to support the project
>* Simple (N/A), Durable (N/A), Transferrable (N/A)

### 2. Design
>* Identify desired metrics / KPIs
>* Review source systems needed to produce the metrics
>* Align with client on what constitutes a reasonable Phase 1
>* Produce a high level roadmap
>* Simple (text and diagrams), Durable (should keep relevance for ~2 years), Transferrable (well-documented)

### 3. Extract
>* Obtain access to client networks / source data
>* Author applications required to extract data into the pipeline(s)
>* Set up pipeline(s) to move the data from source into a data lake
>* Reformat data (if necessary) into common format (CSV/JSON/SQL)
>* Simple (control tables, low code pipelines), Durable (use core Azure tools), Transferable (best practice used and well-documented)

### 4. Load
>* Identify the newly staged data necessary to drive reporting
>* Load extracted data into cloud data lake
>* Convert extracted data to SQL friendly format as required
>* Ensure source data replicates daily
>* Simple (minimize custom code), Durable (Microsoft leading cloud technologies), Transferable (Microsoft technologies)

### 5. Stabilize
>* Study performance and cost of the extract and load processes
>* Optimize storage / processing technologies if necessary
>* Set up delta loading logic if necessary (for larger datasets)
>* Set up performance monitoring
>* Simple (match client source row for row), Durable (alerts and results stored in easily accessible tables), Transferrable (well documented)

### 6. Transform
>* Design star schema data models to support desired reporting areas
>* Transform staged data into required dimension SQL objects
>* Transform staged data in required fact SQL objects
>* Test the integrity of the final reporting dataset (duplication, granularity)
>* Simple (1 star schema per reporting area), Durable (clean, organized code), Transferable (star schema is widely understood)

### 7. Validate
>* Match the output of the new data model to existing reports
>* Meet with client several times to discuss discrepancies
>* Obtain formal client sign off on accuracy of the data models
>* Simple (spreadsheet based comparisons), Durable (repeatable process established at start of validation), Transferrable (discrepancies well-documented)

### 8. Present
>* Build reporting environment (licensing, workspaces, client access)
>* Agree on a design standard (colors, slicers, visuals, etc.)
>* Attach to data model(s) and author final calculations and KPIs
>* Meet with the client 2-3 to collaborate
>* Validate the reports
>* Obtain sign off
>* Release reports and documentation