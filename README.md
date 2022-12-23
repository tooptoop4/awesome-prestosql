# awesome-prestosql
A list of PrestoSQL/Trino resources

# Connectors

**Unmerged Connectors (data sources):**

Generic JDBC (so far has been tested successfully on sqlite, sybase ASE, oracle, impala, presto, dremio, sparksqlthrift, hiveserver2, postgres, mysql, db2, sqlserver, cockroachdb, derby, h2, hsqldb (ie hypersql), firebird) https://github.com/prestosql/presto/pull/3105

Flexible (csv/excel/txt/raw/html/json/xml/word doc/powerpoint/pdf/outlook email/zip/gzip/bzip2 file from websites or local disk) https://github.com/snowlift/trino-storage/pull/25

HTTP Rest API sources https://github.com/prestosql-rocks/presto-rest / https://github.com/cecoppinger/presto-rest / https://github.com/nineinchnick/trino-rest / https://github.com/andreclaudino/trino-http-requester / https://github.com/vjain143/trino-http

Sybase (SAP) ASE & IQ https://github.com/prestosql/presto/pull/3462 / https://github.com/prestosql/presto/pull/2976

Teradata https://github.com/prestodb/presto/pull/12078 / https://github.com/jmrozanec/trino-teradata-connector / https://github.com/jmrozanec/presto-teradata-connector / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-teradata / https://github.com/prestodb/presto/pull/15675

DB2 https://github.com/IBM/presto-db2

Snowflake https://github.com/trinodb/trino/pull/10387 / https://github.com/prestosql/presto/pull/2551 / https://github.com/rahulbsw/trino-snowflake/tree/main/src/main/java/io/trino/snowflake / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-snowflake/src/main/java/com/amazonaws/athena/connectors/snowflake

Hbase https://github.com/harbby/presto-connectors/tree/master/presto-hbase / https://github.com/analysys/presto-hbase-connector / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-hbase / https://github.com/openlookeng/hetu-core/tree/master/hetu-hbase/src/main/java/io/hetu/core/plugin/hbase

Riak https://github.com/kuenishi/presto-riak

Vertica https://github.com/prestosql/presto/pull/6134 / https://github.com/alexsumin/presto-vertica-connector / https://github.com/lev4ik/presto-vertica-connector / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-vertica

Carbondata https://github.com/apache/carbondata/tree/master/integration/presto / https://github.com/openlookeng/hetu-core/tree/master/hetu-carbondata/src/main/java/io/hetu/core/plugin/carbondata

SAP Hana https://github.com/qq5132834/presto-0.233-hana-connector / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-saphana / https://github.com/openlookeng/hetu-core/tree/master/hetu-hana/src/main/java/io/hetu/core/plugin/hana

Salesforce https://github.com/prestosql/presto/pull/2548

DynamoDB https://github.com/buremba/presto-dynamodb / https://github.com/Teradata/presto/tree/c125c3413c19bc6bb69e5f16e4c6f769062ff1cf/presto-dynamo / https://github.com/mugglmenzel/presto/tree/master/presto-dynamo / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-dynamodb

Athena https://github.com/kutny/presto-athena/tree/master/src/main/java/com/facebook/presto/plugin/athena

DocumentDB https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-docdb

Timestream https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-timestream

Neptune https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-neptune

Sagemaker https://github.com/aws-samples/amazon-athena-train-amazon-sagemaker

S3 without Hive https://github.com/EMCECS/presto-s3-connector

Azure CosmosDB (supported by Mongo connector)

Azure SQL DB (supported by SQLServer connector)

Netezza https://github.com/aakashnand/trino-netezza / https://github.com/combineads/plugin-presto-netezza

Lucene/Solr https://github.com/totticarter/presto-lucene / https://github.com/photogamerun/weiwodb/tree/master/presto-lucene/src/main/java/com/facebook/presto/lucene

Ignite https://github.com/trinodb/trino/pull/8323 / https://github.com/prabhuom1/presto-ignite-connector-plugin / https://github.com/emhlbmc/presto-ignite

Azure Synapse https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-synapse

Pulsar https://github.com/trinodb/trino/pull/8020 / https://github.com/apache/pulsar/tree/master/pulsar-sql/presto-pulsar/src/main/java/org/apache/pulsar/sql/presto (inc. protobuf - https://github.com/apache/pulsar/pull/9841/files) / https://github.com/prestodb/presto/pull/11154

Ethereum https://github.com/xiaoyao1991/presto-ethereum

Cockroach https://github.com/trinodb/trino/pull/8317

Excel https://github.com/phillip2019/trino-plugins/tree/main/spreadsheet-storage-handler

Zookeeper https://github.com/phillip2019/trino-plugins/tree/9df3cdd40a15da6415fd0d0d83f6e1576674b0d6/zookeeper-storage-handler/src/main/java/com/fortitudetec/presto/zookeeper

MapD https://github.com/NVIDIA/presto-mapd-connector

Arrow https://github.com/Praveen2112/presto/tree/arrow_connector/presto-arrow-flight/src/main/java/io/prestosql/plugin/arrow / https://github.com/Parth-Brahmbhatt/presto-1/tree/arrow-flight/presto-arrowflight/src/main/java/io/prestosql/plugin/arrowflight / https://github.com/koralium/Koralium/tree/master/presto/trino-connector-arrowflight

kdb https://github.com/sand-stone/dataswitch/tree/master/presto-kdb/src/main/java/kdb/presto / https://github.com/tuor713/trino-kdb

Kylin https://github.com/poiyyq/presto-kylin/tree/master/src/main/java/com/facebook/presto/plugin/kylin / https://github.com/openlookeng/hetu-core/tree/master/hetu-kylin/src/main/java/io/hetu/core/plugin/kylin

Exasol https://github.com/blunghamer/presto-plugins/tree/master/presto-exasol/src/main/java/io/prestosql/plugin/exasol

Influx https://github.com/prestosql/presto/pull/2397

SnappyData https://github.com/dawsongzhao/snappydata-presto-connector

Greenplum https://github.com/openlookeng/hetu-core/tree/master/hetu-greenplum/src/main/java/io/hetu/core/plugin/greenplum

HiveServer2 https://github.com/WeilerWebServices/Eventbrite/tree/master/presto/presto-hive-jdbc / https://github.com/leolorenzoluis/presto-csv-jdbc / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-cloudera-hive / https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-hortonworks-hive

Cloudwatch Logs https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-cloudwatch

Cloudwatch Metrics https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-cloudwatch-metrics

AWS Resource inventory CMDB https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-aws-cmdb

Obiba and REST  https://github.com/obiba/presto-obiba

Manta https://github.com/joyent/presto-manta

Hazelcast https://github.com/ajermakovics/presto-hazelcast

TileDB https://github.com/TileDB-Inc/TileDB-Presto

Template https://github.com/jmrozanec/presto-template-connector

BioSamples https://github.com/EBIBioSamples/biosamples-presto-connector

FPGA https://github.com/supermt/presto-fpga-connector

Vitess https://github.com/vitessio/contrib/tree/master/presto-vitess-connector / https://github.com/yuokada/presto-vitess

Loki https://github.com/sdojjy/presto-loki/tree/master/src/main/java/io/prestosql/plugin/loki

LocalCSV https://github.com/dongqianwei/presto-localcsv

Splunk https://docs.starburst.io/latest/connector/starburst-splunk.html

ScyllaDB https://github.com/trinodb/trino/pull/10336

Alibaba Cloud's MaxCompute https://github.com/aliyun/aliyun-maxcompute-data-collectors/tree/master/trino-connector / https://github.com/prestodb/presto/pull/16599

Alibaba Cloud's Tablestore https://github.com/prestodb/presto/pull/16151

OmniData (Huawei Kunpeng) https://github.com/kunpengcompute/omnidata-openlookeng-connector/tree/main/connector/src

Spreadsheets https://github.com/fortitudetec/presto-plugins/tree/master/spreadsheet-storage-handler

AWS metadata? https://github.com/haitaoyao/presto-aws-plugin

Cloudata? https://github.com/justinsb/cloudata/tree/master/cloudata-structured/src/main/java/com/cloudata/structured/sql/provider

Extract/Memory? https://github.com/yoloz/prestoSamples

MD5? https://github.com/Bongss/MD5PasswordCracker/tree/master/presto-cracker/src/main/java/PasswordCracker

Weiwodb/bytecode? https://github.com/photogamerun/weiwodb

Kubernetes https://github.com/xuxinkun/kubesql

TiDB/tikv https://github.com/zhihu/presto-connectors / https://github.com/tidb-incubator/TiBigData/tree/2051840321bd8fe12b90ddc5397e9af49951b397/trino

OpenGauss https://github.com/openlookeng/hetu-core/tree/master/hetu-opengauss/src/main/java/io/hetu/core/plugin/opengauss

Victoria Metrics https://github.com/prestodb/presto/pull/13777

Pravega https://github.com/pravega/presto-connector/pull/7

Twitter https://github.com/bitsondatadev/presto/tree/twitter-hacks / https://github.com/kokosing/trino-rest/tree/master/trino-rest-twitter/src/main/java/rocks/trino/rest/twitter

Apache DataSketches https://github.com/trinodb/trino/pull/6643

RocketMQ https://github.com/sunxiaojian/trino-rocketmq

Slack https://github.com/kokosing/trino-rest/tree/master/trino-rest-slack/src/main/java/rocks/trino/rest/slack / https://aws.amazon.com/blogs/big-data/create-a-custom-data-connector-to-slacks-member-analytics-api-in-amazon-quicksight-with-amazon-athena-federated-query/

Github https://github.com/kokosing/trino-rest/tree/master/trino-rest-github/src/main/java/rocks/trino/rest/github

Monarch Ampool https://github.com/davinash/monarch/tree/21ac4f538fe695fd7481003084fd2f0a8982cd32/Connectors/monarch-presto/src/main/java/io/ampool/presto/connector

Huawei Heti OpenLookEng (DataCenter/VDM) https://github.com/openlookeng/hetu-core

Yugabyte-db https://github.com/trinodb/trino/pull/5708 / https://docs.yugabyte.com/latest/develop/ecosystem-integrations/presto/

recordstore https://github.com/PierreZ/record-store/tree/04b399325aeb020eb9816aeb9a18c876a6a7ee27/presto-connector/src/main/java/fr/pierrezemb/recordstore/presto

Pixelsdb https://github.com/pixelsdb/pixels/tree/master/pixels-presto

Kairosdb https://github.com/xuhang1458/presto-kairosdb-connector

Apache IoTDB (Internet of Things) https://github.com/xuhang1458/presto-iotdb-connector

Git https://github.com/nineinchnick/trino-git

Rapid7 Armor https://github.com/rapid7/presto-armor-connector/tree/master/src/main/java/com/rapid7/presto/armor

Aerospike https://www.aerospike.com/docs/connect/access/presto/index.html

Hyena messaging daemon https://github.com/FCG-LLC/presto/tree/master/presto-hyena/src/main/java/co/llective/presto/hyena

Python https://github.com/tooptoop4/presto-python/blob/master/src/test/java/rocks/prestodb/python/TestPythonFunctions.java

Javascript https://github.com/mdesmet/trino-javascript

EC2 instance https://github.com/haitaoyao/presto-aws-plugin/tree/master/src/main/java/presto/aws

AWS data (like EC2 instances or S3 buckets) https://github.com/nineinchnick/trino-cloud

Kinetica https://github.com/kineticadb/kinetica-connector-presto

ADLS Gen2 https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-datalakegen2

Lark Sheets https://prestodb.io/docs/current/connector/larksheets.html

Embedded HiveMetastore https://github.com/aws-samples/amazon-athena-serverless-ehms-connector

Elasticsearch via Glue https://github.com/your2fat/glue-connector

Palantir Foundry https://github.com/palantir/foundry-athena-query-federation-connector

Slack Member Analytics REST API https://github.com/aws-pablito/aws-quicksight-slackanalytics-app/tree/main/athena-slack-member-analytics

Cloudera Impala https://github.com/awslabs/aws-athena-query-federation/tree/master/athena-cloudera-impala

FactorialHR https://github.com/margon8/athena-connector

NetEase arctic https://github.com/NetEase/arctic/tree/master/trino/src/main/java/com/netease/arctic/trino

Cyberagent valor https://github.com/CyberAgent/valor/tree/develop/valor-trino/src/main/java/jp/co/cyberagent/valor/trino

Flink Table Store https://github.com/JingsongLi/flink-table-store-trino

Honeycomb https://github.com/rkennedy-mode/trino-honeycomb

Raptor https://github.com/prestodb/presto/tree/master/presto-raptor/src/main/java/com/facebook/presto/raptor

Cratedb https://community.crate.io/t/connecting-to-cratedb-using-trino/993

GeoSpock https://docs.geospock.com/query/connectorGuidelines/

Twilio Segment (write only) https://github.com/tikikun/trino-segment-connector

Hashicorp Consul Connect https://github.com/Skatteetaten/terraform-nomad-trino/tree/94113f26e1d53208cbf92433854e995f5be7d9f9/java/src/main/java/io/github/fredrikhgrelland/trino/plugin/consulconnect / https://github.com/gugalnikov/trino-consul-connect

Wrike REST API https://github.com/alekkol/wrike-sql

Tezos Blockchain https://github.com/NijeboerFrank/presto-tezos/tree/master

DBIIR ParaFlow https://github.com/dbiir/paraflow/tree/master/paraflow-connector/src/main/java/cn/edu/ruc/iir/paraflow/connector

Katta (distributed Lucene) https://github.com/zhenqin/katta/tree/master/katta-presto/src/main/java/com/ivyft/katta/presto

SPARQL/Apache Jena syntax https://github.com/ddd332/presto-0.54/tree/a7572ab607512cf084b22b06c871657d3185495e/presto-cli/src/main/java/com/facebook/presto/cli/sparql2sql

Resurface binaries https://github.com/resurfaceio/trino-connector

Apache ShardingSphere https://github.com/openlookeng/hetu-core/tree/master/hetu-singledata/src/main/java/io/hetu/core/plugin/singledata/shardingsphere

**Plugins:**

OpenLineage https://github.com/takezoe/trino-openlineage

LDAP/AD group provider https://github.com/arghya18/trino-group-provider-ldap-ad

Github group provider https://github.com/os-climate/trino-github-group-provider

File group provider https://github.com/hassanahmadkhani/PrestoSQLFileBaseGroupProvider

Open Policy Agent (OPA) https://github.com/stackabletech/trino-opa-authorizer/tree/main

EventListener to Kafka https://github.com/7c00/presto-event-producer

**Merged connectors (data sources):**

Microsoft SQL Server

Oracle

Hive

PostgreSQL

MySQL

MariaDB

Amazon Redshift

MongoDB

Cassandra

BigQuery (Google)

Elasticsearch

Apache Kafka

Clickhouse

Druid

JMX

Hudi (Uber)

Iceberg (Netflix)

Delta Lake (Databricks Spark)

Kinesis

Phoenix

Google Sheets

Kudu

Redis

Thrift

Prometheus

Linkedin Pinot

Black Hole

Accumulo

Local File

Memory

MemSQL (SingleStore)

Atop

System

TPCDS

TPCH

see https://trino.io/resources.html for up to date list



**Supported file types in Hive Connector:**

ORC

Parquet

Avro

JSON (using org.apache.hive.hcatalog.data.JsonSerDe)

CSV (using org.apache.hadoop.hive.serde2.OpenCSVSerde)

TextFile

RCText (RCFile using ColumnarSerDe)

RCBinary (RCFile using LazyBinaryColumnarSerDe)

SequenceFile

XML (https://github.com/trinodb/trino/pull/9219)



**Supported filesystem storage for Hive Connector:**

AWS S3 ("s3", "s3a")

Google Cloud Storage aka GCS ("gs")

Hadoop File System ("hdfs")

Windows Azure Storage Blob (WASB) ("wasb", "wasbs")

Azure Data Lake Storage (ADLS) ("adl")

Azure ADLS Gen2 - Azure Blob File System ("abfs", "abfss")

Aliyun Object Storage Service (OSS) - https://hadoop.apache.org/docs/current/hadoop-aliyun/tools/hadoop-aliyun/index.html

Tencent Cloud Object Storage (COSN) - https://github.com/prestosql/presto/pull/4978

IBM Cloud Object Storage (COS) - https://github.com/CODAIT/stocator/issues/218#issuecomment-531110300 / https://docs.starburstdata.com/latest/connector/starburst-hive-ibm-cos.html

??? Oracle Cloud Infrastructure Object Storage (OCI) - https://github.com/oracle/oci-hdfs-connector/issues/51

MinIO

Ceph

Dell EMC

Cloudian?

OpenIO?

SwiftStack / Stackpath / OpenStack?

Alibaba Cloud Object Storage Service?

DigitalOcean Spaces?

Huawei FusionStorage?

Baidu afs?

Qiniu Kodo?

Huawei Cloud OBS?

RackSpace Cloud files?

Vultr?

Pure Storage Flashblade?

Databricks file system?

viewfs?

Apache Ignite FS?

maprfs?



**Clients**

C#/.NET: https://github.com/koralium/EntityFrameworkCore.Presto

Perl: https://github.com/spiritloose/Net-Presto

PHP: https://github.com/360d-io-labs/PhpPrestoClient

Elixir: https://github.com/bbalser/ex_prestodb

Scala: https://github.com/nezihyigitbasi/presto-scala-client

C: https://github.com/easydatawarehousing/prestoclient/tree/master/C

Rust: https://github.com/nooberfsh/prusto

Clojure: https://github.com/metabase/metabase/blob/6a6327646964559e735c3557d8c39f5ceff5dcd8/modules/drivers/presto/src/metabase/driver/presto.clj

ODBC: Simba

Trino JDBC driver for Java/JVM

trino-go-client for Go

presto-client-node for Node.js

lento for Node.js

PyHive for Python

RPresto for R

trino-client-ruby for Ruby



**Used in:**

GUI: Hue, Sqlpad..etc

Google Cloud: Dataproc

Alibaba Cloud: Data Lake Analytics, E-MapReduce

Tencent Cloud: Elastic MapReduce

Huawei Cloud: MapReduce Service



**Caching:**

Data: Alluxio or Qubole Rubix

Directory/file listing

Metastore partitions



**Performance tips:**

Partitioning on VARCHAR columns (not high cardinality) that are included in WHERE of SELECTs

ANALYZE to gather statistics: https://prestosql.io/docs/current/optimizer/statistics.html

Compressed ORC/Parquet files with size between 64MB-1GB and the columns inside the files sorted so min/max ranges don't overlap for reduced network IO and better predicate pushdown (https://www.slideshare.net/databricks/the-parquet-format-and-performance-optimization-opportunities)

https://aws.amazon.com/blogs/big-data/top-10-performance-tuning-tips-for-amazon-athena/

High CPU important for parallelism/concurrency

High Memory important for joins/group by/distinct

task.max-worker-threads

task.concurrency



**Security:**

LDAP/Kerberos/JWT/Cert/OAuth

TLS

Apache Ranger for column/table/schema/catalog level authorisation, column masking and row level filtering fine grained access



**Notes:**

Rarely achieve <400ms performance even for single table SELECTs/simple filters

Most useful feature is joining between data from any of the connectors (although if u want to create a view across them you need Hive Metastore).

Disclaimer: while Hive sources are suitable for data of large size (ie Petabytes) provided you have a lot of compute workers, JDBC sources are only performant on small tables. For example:

you have a 8 billion row txns table that is indexed/partitioned in Oracle.

Below query takes 38 seconds run in Oracle directly but 70 minutes when run in Presto -->
```
select custid, count(1) numtxns from oracle.txns
where txnmonth in (to_date('202002','YYYYMM'),to_date('201902','YYYYMM'))
group by custid
having count(1) > 4
```



**Why Presto (hive connector) slower than pure MySQL (without presto) for small (ie <5GB) datasets?**

remote storage ie s3 instead of local disk

limited caching - no data retained in memory for serving multiple clients running the same query

gathered stats like rowcount/# unique vals are not used to answer queries, just contribute to query plan decision

no indexes or primary keys, foreign keys

no histogram stats

too many small files

json rather than binary result format

query optimiser not as advanced, especially for OR conditions, functions or subqueries

partition pushdown might not work on timestamp/numeric columns

columnar, not row based. ie parquet is not suited to retrieving all columns for a few rows as it has to pivot the column reads into rows and scan a lot since rows are not stored contiguously



**Missing in all JDBC connectors:**

Complex filter pushdown https://github.com/trinodb/trino/issues/18 / https://github.com/trinodb/trino/issues/9506 / https://github.com/trinodb/trino/pull/11522 / https://github.com/trinodb/trino/pull/11045 (for other connectors missing) / https://github.com/trinodb/trino/issues/11699

ORDER BY pushdown https://github.com/trinodb/trino/issues/8093

Aggregate pushdown https://github.com/trinodb/trino/issues/6613

Join pushdown https://github.com/trinodb/trino/issues/6620

DISTINCT pushdown https://github.com/trinodb/trino/issues/4324

