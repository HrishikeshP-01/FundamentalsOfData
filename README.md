# Data Nuts & Bolts : Fundamentals of Data
- *Data* – Raw & unstructured facts that convey a message
- *Information* – contextualized, organized & vetted data that conveys some sort of trend or pattern

Data -> Information is one of the most important tasks of IT. The end info answers questions such as who, where, when, what & how

- *Knowledge* – application of information. It’s measured by the ability to do things using the know how gained from Information.
- *Wisdom* - Ability to use knowledge & experience to make good decisions

## Sources of data generation & data formats
Common data collection types
- *Observational* – Obtained from direct observation. Eg: Temp. of a room
- *Experimental* - Obtained from research & investigation. Eg: DNA sequencing results
- *Compiled* – Acquired through manual data gathering, aggregated over time. Eg: Data mining
- *Simulated* – Results of studying certain behaviors & identifying new patterns. Eg:- Customer shopping behavior.

## Common data generation sources
- *Human generated data* – data from phones, emails, calls, web etc.
- *Machine generated data* – IoT, medical equipment, satellites etc.
- *Business generated data* – Banks, stock exchanges, etc.

## Data formats w.r.t storage & processing
- *Structured* – easiest to search & analyze, often stored in rows & cols
- *Unstructured* – not contained in row-col database
- *Semi-structured* – has some defining & consistent characteristics. It doesn’t conform to a structure as rigid as expected with a database. There are some organizational properties called semantic tags or metadata to make it easier to organize but there’s still fluidity in the data. Eg: XML, JSON

You can’t perform analytics on unstructured data. It has to be transformed to structed data.

## Data Terminologies
Data can be classified into 2 groups:
- *Primary data* – data a person collects by themselves
- *Secondary data* – data collected by a third party

- *Database* – repository for data
- *Data analytics* – processes/technologies used to explore data
- *Data aggregation* – procedures used to gather data
- *Metadata* – details about a particular dataset. Data about data
- *Time series* – analysis studying temporal patterns
- *Anonymized data* – data in which individual’s identities are kept secret
- *Augmented reality* – data analytics approach utilizing ML & NLP
- *Data literacy* - ability to understand, read, create and communicate data as information
- *File format* – structure used to identify & encode data
- *Data science* – interdisciplinary field which uses scientific methods to extract knowledge & insight from data
- *Deep learning* – neural network-based ML algorithms

## Data projects are mainly categorized into 3 types:
- Data pipelines & data staging
- Data processing & analysis
- Application development

## Data storage & Backup
3 main methods of backup
- Full backup – 
..* Most comprehensive type of backup
..* Covers backup for all data within the hard drive
..* Requires high storage space
..* Slowest backup speed
..* Contains lots of duplicate data
- Differential backup –
..* Getting a backup of the data that was generated/modified since the last FULL backup
..* Requires medium-high storage space
..* Fast backup speed
..* Contains some duplicate data
- Incremental backup –
..* Storing only modifications that were made to the previous backup regardless of whether the previous backup was  a full backup or any other kind of backup
..* Small storage space
..* Fastest backup speed
..* No duplicate data

## Data migration & ETL
Data migration is one of the most complex & critical parts of every data transformation project. 

Eg: Deciding to use a new CRM or ERP

Data migration involves 6 main steps:
- *Planning* – Identify stakeholders, identify data, determine risk mitigation & backup strategies
- *Analyzing* the data – explore the data, determine the impact of migration cut-off point, create a data dictionary
- *Design* – develop “source to target mapping”, a dependency tree on order of migration is required if multiple data sets are to be migrated, determine ETL transformations required
- *Implementation* – configure tools needed for migration, write migration scripts ensuring best practices
- *Testing* – deploy all required tools, create a test plan with accurate data coverage, design a migration validation engine
- *Final migration* – execute all data migration steps, ensure proper planning & most importantly get stakeholders to sign off on this plan, execute go-live including migration, define decommissioning plan for all systems that previously stored the data





