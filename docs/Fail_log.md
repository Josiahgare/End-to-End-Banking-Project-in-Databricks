
## Master Job Run
1.  Ingestion from source through Azure sql server failed because the client IP address was not alowed to access the Azure server. This was corrected by adding the IP address to the 
firewall exception rule to allow Databricks communicate with the Azure Database server.
