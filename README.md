# SQLDay 2022
Below you can find resources/ad-ons to our workshop and presentation delivered during SQLDay 2022

<ul>
 <li>
<a href="https://github.com/DataInsiders/SQLDay2022/blob/main/README.md#sql-day-2022-workshop--presentation-resources"> SQL Day 2022 Workshop: Agile & secure analytics architecture in Azure </a> </li>
  <li> <a href="https://github.com/DataInsiders/SQLDay2022/edit/main/README.md#the-bad-and-the-ugly---10-steps-to-cure-your-synapse-serverless-performance-and-optimize-costs"> The Bad and The Ugly - 10 steps to cure your Synapse Serverless performance and optimize costs </a> </li>
  
 </ul>

# SQL Day 2022 Workshop  Agile & secure analytics architecture in Azure 

Analytics end-to-end with Azure Synapse 

This example scenario demonstrates how to use Azure Synapse Analytics with the extensive family of Azure Data Services to build a modern data platform that's capable of handling the most common data challenges in an organization.

The solution described in this article combines a range of Azure services that will ingest, store, process, enrich, and serve data and insights from different sources (structured, semi-structured, unstructured, and streaming).

Source: https://docs.microsoft.com/en-us/azure/architecture/example-scenario/dataplate2e/data-platform-end-to-end?tabs=portal<br>
Deployment accelerator: https://github.com/Azure/azure-synapse-analytics-end2end

The source architecture was modified a little bit (Databricks included)

![image](https://user-images.githubusercontent.com/104371605/165725636-5ea58ff5-eb9e-477b-ad6a-9ee8ef5b3329.png)

Visio file download link: https://github.com/DataInsiders/SQLDay2022/blob/main/analytics-with-azuresynapse-updated.vsdx

<B>Security whitepapers:</B><br>
Azure Synapse Analytics whitepaper: https://docs.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-introduction<br>
Power BI Security whitepaper: https://docs.microsoft.com/en-us/power-bi/guidance/whitepaper-powerbi-security<br>

Some addiotnal useful links:<br>
<B>Few words about identification, authentication & authorization</B><br>
<ul>
 <br>
 <B>Azure Active Directory:</B>
  <li> <a href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-security-defaults">Azure Active Directory Security Defaults</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/location-condition">Using the location condition in a Conditional Access policy</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-location"> Conditional Access: Block access by location</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-compliant-device">Conditional Access: Require compliant or hybrid Azure AD joined device</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/databricks/administration-guide/access-control/conditional-access">Conditional access for Databricks</a> </li>
<br>
 <B>Azure Data Lake Storage Gen2:</B>
 <li> <a href="https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/data-management/best-practices/data-lake-access">Access control and data lake configurations in Azure Data Lake Storage Gen2 - Cloud Adoption Framework | Microsoft Docs </a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control">Access control lists (ACLs) in Azure Data Lake Storage Gen2</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control-model#how-permissions-are-evaluated">How permissions are evaluated</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/data-management/best-practices/data-lake-access">Access control and data lake configurations in Azure Data Lake Storage Gen2 - Cloud Adoption Framework | Microsoft Docs </a> </li>
<br>
 <B>SQLDB / SQLMI :</B>
 <li> <a href="https://techcommunity.microsoft.com/t5/azure-sql/azure-active-directory-only-authentication-for-azure-sql/ba-p/2417673"> Azure Active Directory only authentication for Azure SQL - Microsoft Tech Community</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-azure-ad-only-authentication-create-server?tabs=azure-powershell&view=azuresql">Create server with Azure AD-only authentication enabled in Azure SQL</a> </li>
<br>
 <B>Databricks:</B>
 <li> <a href="https://databricks.com/blog/2019/10/24/simplify-data-lake-access-with-azure-ad-credential-passthrough.html#:~:text=Azure%20Databricks%20brings%20together%20the%20best%20of%20the,Azure%E2%80%99s%20cloud%20storage%20Azure%20Data%20Lake%20Storage%20%28ADLS%29">Simplify Data Lake Access with Azure AD Credential Passthrough (databricks.com)</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/azure/databricks/security/credential-passthrough/adls-passthrough#adls-aad-credentials">Access Azure Data Lake Storage using Azure Active Directory credential passthrough</a> </li>
<br>
 <B>Power BI:</B>
 <li> <a href="https://powerbi.microsoft.com/en-us/blog/announcing-data-gateway-support-for-single-sign-on-sso-with-azure-active-directory/">Announcing data gateway support for Single Sign-On (SSO) with Azure Active Directory | Microsoft Power BI Blog | Microsoft Power BI</a> </li>
 <li> <a href="https://docs.microsoft.com/en-us/power-bi/connect-data/service-gateway-sso-test-configuration">Test single sign-on (SSO) configuration</a> </li>
 <li> <a href="https://www.youtube.com/watch?v=6gDZBC-UV_w">Using Single Sign-on with the Power BI Gateway</a> </li>
 </ul>

<B>Is my data safe…- the one about secure data store</B><br>
<ul>
 <B>Storage account:</B><br>
 <li><a href="https://docs.microsoft.com/en-us/azure/azure-government/azure-secure-isolation-guidance">Azure guidance for secure isolation</a></li>
 <li><a href="https://docs.microsoft.com/en-us/azure/storage/common/storage-service-encryption">Azure Storage encryption for data at rest</a></li>
 <li><a href="https://docs.microsoft.com/en-us/azure/storage/common/customer-managed-keys-overview?toc=/azure/storage/blobs/toc.json">Customer-managed keys for Azure Storage encryption</a></li>
<br>
  <B>Power BI:</B>
  <li><a href="https://docs.microsoft.com/en-us/power-bi/enterprise/service-encryption-byok#:~:text=Power%20BI%20encrypts%20data%20at-rest%20and%20in%20process.,Data%20source%20and%20storage%20considerations%20for%20more%20information%29">Bring your own encryption keys for Power BI</a></li>
 <li><a href="https://www.youtube.com/watch?v=vLdm95YglZ0">Power BI Security Best Practices</a></li>
 <li><a href="https://docs.microsoft.com/en-us/power-bi/guidance/whitepaper-powerbi-security">Power BI security white paper</a></li>
 <li><a href="https://docs.microsoft.com/en-us/power-bi/enterprise/service-security-apply-data-sensitivity-labels#:~:text=In%20the%20Power%20BI%20service%2C%20you%20can%20apply,Sensitivity%20labels%20must%20be%20enabled%20for%20your%20organization">How to apply sensitivity labels in Power BI</a></li>
 <br>
 <B>SQL Server/SQLDB </B>
  <li><a href="https://docs.microsoft.com/en-us/sql/relational-databases/security/sql-data-discovery-and-classification?view=sql-server-ver15&tabs=t-sql"> SQL Data Discovery and Classification</a></li>
 <li><a href="https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/sql-server-encryption?view=sql-server-ver15 ">SQL Server Encryption</a></li>
 <li><a href="https://docs.microsoft.com/en-us/azure/azure-sql/database/transparent-data-encryption-tde-overview?view=azuresql&tabs=azure-portal">Transparent data encryption for SQL Database, SQL Managed Instance, and Azure Synapse Analytics</a></li>
 </ul>
 
<B>Secure data interaction…- how to work with data in a secure way</B><br>
<ul>
 <B> Azure Synapse Analytics / SQLDB</B>
 <li><a href="https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/how-to-implement-row-level-security-in-serverless-sql-pools/ba-p/2354759">How to implement row-level security in serverless SQL pools</li>
 <li><a href="https://www.youtube.com/watch?v=XqaU-4ASF38">Azure Synapse Dynamic Data Masking and Row-Level Security | Grab's Practical Use Case</a></li>
 <BR> 
 <B>Power BI</B>
  <li><a href="https://powerbi.microsoft.com/en-us/blog/object-level-security-ols-now-available-for-public-preview-in-power-bi-premium/">Object-Level Security (OLS) i in Power BI Premium and Pro</li>
   <li><a href="https://docs.microsoft.com/en-us/power-bi/enterprise/service-security-dlp-policies-for-power-bi">Data loss prevention policies for Power BI (preview)</li>
    <li><a href="https://docs.microsoft.com/en-us/power-bi/guidance/report-separate-from-model">Separation of reports and data model</a></li>
    <li><a href="https://guyinacube.com/2021/09/09/power-bi-xmla-endpoint-why-you-should-care/">Power BI XMLA Endpoint: Why you should care - Guy in a Cube </a></li>
    <li><a href="https://data-marc.com/2019/11/12/versioning-and-ci-cd-for-power-bi-with-azure-devops/">Versioning and CI/CD for Power BI with Azure DevOps – Data – Marc (data-marc.com)</a></li>
  <li><a href="https://www.youtube.com/watch?v=8NHVFuvHwoI">Power BI Dataset CI/CD Pipeline (Azure Dev Ops, XMLA Endpoint, Tabular Editor & Service Connection</a></li>
 <br>
 <B> Common</B>
 <li><a href="https://docs.microsoft.com/en-us/azure/architecture/example-scenario/data-warehouse/dataops-mdw">DataOps for the modern data warehouse</a></li>
 <li><a href="https://github.com/kevchant/AzureDevOps-AzureSynapseSQLPool/wiki">AzureDevOps-AzureSynapseSQLPool</a></li>
 </ul>
 
 <B>Make it private…- Isolated environment</B>
 <BR>
   
 <ul>
  <B>Azure Synapse Analytics</B>
 <li><a href="https://techcommunity.microsoft.com/t5/azure-architecture-blog/understanding-azure-synapse-private-endpoints/ba-p/2281463">Understanding Azure Synapse Private Endpoints - Microsoft Tech Community</a></li>
 <li><a href="https://docs.microsoft.com/en-us/azure/synapse-analytics/security/how-to-connect-to-workspace-from-restricted-network">Connect to workspace resources from a restricted network</a></li>
 <br>
 <B>Power BI</B>
 <li><a href="https://docs.microsoft.com/en-us/data-integration/gateway/service-gateway-onprem-indepth">On-premises data gateway architecture</a></li>
 <li><a href="https://docs.microsoft.com/en-us/data-integration/vnet/overview">What is a virtual network (VNet) data gateway (Preview) | Microsoft Docs </a></li>
 <li><a href="https://docs.microsoft.com/en-us/data-integration/vnet/data-gateway-architecture">Virtual network data gateway architecture</a></li>
 <li><a href="https://docs.microsoft.com/en-us/power-bi/enterprise/service-security-private-links#:~:text=Private%20endpoints%20guarantee%20that%20traffic%20going%20into%20your,artifacts%20must%20come%20from%20the%20established%20private%20link">Private endpoints for accessing Power BI</a></li>
 </ul>
 <B>I know what you did…- monitoring & auditing</B>
 <BR>
   
 <ul>
  <B>Azure SQL Audit </B>
 <li><a href="https://docs.microsoft.com/en-us/azure/azure-sql/database/auditing-overview?view=azuresql">Auditing for Azure SQL Database and Azure Synapse Analytics</a></li>
 <li><a href="https://docs.microsoft.com/en-us/azure/azure-sql/database/azure-defender-for-sql?view=azuresql">Microsoft Defender for SQL</a></li>
  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/insights/azure-sql#:~:text=Azure%20SQL%20Analytics%20is%20a%20cloud-only%20monitoring%20solution,or%20in%20virtual%20machines.%20Azure%20SQL%20Analytics%20options">Monitor Azure SQL Database using Azure SQL Analytics</a></li>
   <li><a href="https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/optimize-database-schema-in-serverless-sql-pools-using-qpi/ba-p/3252140">Optimize database schema in serverless SQL pools using QPI library</a></li>
 <br>
 <B>Power BI</B>
 <li><a href="https://docs.microsoft.com/en-us/power-bi/transform-model/log-analytics/desktop-log-analytics-overview">Using Azure Log Analytics in Power BI</a></li>
 <li><a href="https://docs.microsoft.com/en-us/power-bi/admin/service-admin-auditing">Track user activities in Power BI</a></li>
 <li><a href="https://radacad.com/export-power-bi-audit-log-in-a-few-simple-steps-with-no-code#:~:text=The%20Audit%20log%20of%20Power%20BI%20is%20all,Analyze%20in%20Excel%2C%20and%20much%20more%20useful%20information.">Export Power BI Audit log in a few Simple Steps with No Code</a></li>
  </ul>

  
  <B>Other links:</B><br>
  Introduction to Azure Purview  https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-purview/ <BR>
  Azure Purview Workshop https://github.com/tayganr/purviewlab<BR><BR>
   
    
# The Bad and The Ugly - 10 steps to cure your Synapse Serverless performance and optimize costs
