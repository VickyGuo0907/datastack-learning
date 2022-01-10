# Basic Concept Knowledge

Below would be all related knowledge you should know related with Modern Data Stack

## ETL vs ELT
### ETL --- Extract, Transforming, Loading

> Reference articles:
> 
> 1. [What's ETL](https://www.talend.com/resources/what-is-etl/)

ETL makes it possible to migrate data between a variety of sources, destinations, and analysis tools. As a result, the ETL process plays a critical role in producing business intelligence and executing broader data management strategies.

### ELT --- Extract, Loading, Transforming

> Reference articles:
> 
> 1. [What's ELT](https://www.talend.com/resources/what-is-elt/)

Extract/load/transform (ELT) similarly extracts data from one or multiple remote sources, but then loads it into the target data warehouse without any other formatting. The transformation of data, in an ELT process, happens within the target database. ELT asks less of remote sources, requiring only their raw and unprepared data.
### When is ELT the right choice?

* When ingestion speed is the number one priority
* When more intel is better intel
* When you know you will need to scale

### ETL vs ELT: Understanding the different 

The primary differences between ETL and ELT are how much data is retained in data warehouses and where data is transformed.

* With ETL, the transformation of data is done before it is loaded into a data warehouse. This enables analysts and business users to get the data they need faster, without building complex transformations or persistent tables in their business intelligence tools.

* Using the ELT approach, data is loaded into the warehouse or data lake as is, with no transformation before loading. This makes jobs easier to configure because it only requires an origin and a destination.

The ETL and ELT approaches to data integration differ in several key ways.

* **Load time** — It takes significantly longer to get data from source systems to the target system with ETL.
* **Transformation time** — ELT performs data transformation on-demand, using the target system's computing power, reducing wait times for transformation.
* **Complexity** — ETL tools typically have an easy-to-use GUI that simplifies the process. ELT requires in-depth knowledge of BI tools, masses of raw data, and a database that can transform it effectively.
* **Data warehouse support** — ETL is a better fit for legacy on-premise data warehouses and structured data. ELT is designed for the scalability of the cloud.
* **Maintenance** — ETL requires significant maintenance for updating data in the data warehouse. With ELT, data is always available in near real-time.

### ELT and Data Lakes: The Future of Data Integration?

Modern, cloud-based infrastructure technologies offer large amounts of data storage and scalable computing power at lower costs, making it possible to keep petabytes of data in large and expandable data lakes, and process it quickly on-demand. The proliferation of data lakes has made it possible for more organizations to move from ETL to ELT.

* Benefits of using ELT in the cloud

    * **Scalability**
    * **(Almost) seamless integration**
    * **Open Source**
    * **Lower cost of ownership**

## OLTP and OLAP

> Reference Articles:
>
> 1. [OLTP and OLAP: a practical comparison](https://www.stitchdata.com/resources/oltp-vs-olap/)

### OLTP --- Online Transaction Processing


### OLAP --- Online Aanytical Processing


## Data Lake vs Data WareHouse

### Data Lake 

> Reference articles:
> 
> 1. [What's a Data Lake?](https://www.talend.com/resources/what-is-data-lake/)

A data lake is a central storage repository that holds big data from many sources in a raw, granular format.