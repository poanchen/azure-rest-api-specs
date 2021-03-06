## CLI

These settings don't need to apply `--cli` on the command line.

``` yaml
cli:
  cli-name: cosmosdb
  package-name: azure-mgmt-cosmosdb
  namespace: azure.mgmt.cosmosdb
  test-scenario:
    - name: /DatabaseAccounts/put/CosmosDBDatabaseAccountCreateMin
    - name: /DatabaseAccounts/put/CosmosDBDatabaseAccountCreateMax
    - name: /TableResources/put/CosmosDBTableReplace
    - name: /SqlResources/put/CosmosDBSqlDatabaseCreateUpdate
    - name: /MongoDBResources/put/CosmosDBMongoDBDatabaseCreateUpdate
    - name: /GremlinResources/put/CosmosDBGremlinDatabaseCreateUpdate
    - name: /CassandraResources/put/CosmosDBCassandraKeyspaceCreateUpdate
    - name: /NotebookWorkspaces/put/CosmosDBNotebookWorkspaceCreate
    - name: /GremlinResources/put/CosmosDBGremlinGraphCreateUpdate
    - name: /CassandraResources/put/CosmosDBCassandraTableCreateUpdate
    - name: /SqlResources/put/CosmosDBSqlContainerCreateUpdate
    - name: /PrivateEndpointConnections/put/Approve or reject a private endpoint connection with a given name.
    - name: /MongoDBResources/put/CosmosDBMongoDBCollectionCreateUpdate
    - name: /TableResources/put/CosmosDBTableThroughputUpdate
    - name: /SqlResources/put/CosmosDBSqlDatabaseThroughputUpdate
    - name: /MongoDBResources/put/CosmosDBMongoDBDatabaseThroughputUpdate
    - name: /GremlinResources/put/CosmosDBGremlinDatabaseThroughputUpdate
    - name: /CassandraResources/put/CosmosDBCassandraKeyspaceThroughputUpdate
    - name: /SqlResources/put/CosmosDBSqlTriggerCreateUpdate
    - name: /GremlinResources/put/CosmosDBGremlinGraphThroughputUpdate
    - name: /SqlResources/put/CosmosDBSqlStoredProcedureCreateUpdate
    - name: /CassandraResources/put/CosmosDBCassandraTableThroughputUpdate
    - name: /SqlResources/put/CosmosDBSqlContainerThroughputUpdate
    - name: /SqlResources/put/CosmosDBSqlUserDefinedFunctionCreateUpdate
    - name: /MongoDBResources/put/CosmosDBMongoDBCollectionThroughputUpdate
    - name: /PartitionKeyRangeIdRegion/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /MongoDBResources/get/CosmosDBMongoDBCollectionThroughputGet
    - name: /SqlResources/get/CosmosDBSqlUserDefinedFunctionGet
    - name: /PartitionKeyRangeId/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /CollectionPartitionRegion/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /SqlResources/get/CosmosDBSqlContainerThroughputGet
    - name: /CassandraResources/get/CosmosDBCassandraTableThroughputGet
    - name: /SqlResources/get/CosmosDBSqlStoredProcedureGet
    - name: /GremlinResources/get/CosmosDBGremlinGraphThroughputGet
    - name: /PercentileSourceTarget/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /CollectionPartition/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /CollectionPartition/get/CosmosDBCollectionGetUsages
    - name: /SqlResources/get/CosmosDBSqlTriggerGet
    - name: /CollectionRegion/get/CosmosDBRegionCollectionGetMetrics
    - name: /CassandraResources/get/CosmosDBCassandraKeyspaceThroughputGet
    - name: /GremlinResources/get/CosmosDBGremlinDatabaseThroughputGet
    - name: /SqlResources/get/CosmosDBSqlUserDefinedFunctionList
    - name: /MongoDBResources/get/CosmosDBMongoDBDatabaseThroughputGet
    - name: /SqlResources/get/CosmosDBSqlStoredProcedureList
    - name: /SqlResources/get/CosmosDBSqlDatabaseThroughputGet
    - name: /Collection/get/CosmosDBCollectionGetMetricDefinitions
    - name: /SqlResources/get/CosmosDBSqlTriggerList
    - name: /TableResources/get/CosmosDBTableThroughputGet
    - name: /MongoDBResources/get/CosmosDBMongoDBCollectionGet
    - name: /Collection/get/CosmosDBCollectionGetMetrics
    - name: /Collection/get/CosmosDBCollectionGetUsages
    - name: /PercentileTarget/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /PrivateEndpointConnections/get/Gets private endpoint connection.
    - name: /SqlResources/get/CosmosDBSqlContainerGet
    - name: /CassandraResources/get/CosmosDBCassandraTableGet
    - name: /GremlinResources/get/CosmosDBGremlinGraphGet
    - name: /MongoDBResources/get/CosmosDBMongoDBCollectionList
    - name: /NotebookWorkspaces/get/CosmosDBNotebookWorkspaceGet
    - name: /Database/get/CosmosDBDatabaseGetMetricDefinitions
    - name: /CassandraResources/get/CosmosDBCassandraTableList
    - name: /GremlinResources/get/CosmosDBGremlinGraphList
    - name: /SqlResources/get/CosmosDBSqlContainerList
    - name: /CassandraResources/get/CosmosDBCassandraKeyspaceGet
    - name: /PrivateLinkResources/get/Gets private endpoint connection.
    - name: /Database/get/CosmosDBDatabaseGetMetrics
    - name: /GremlinResources/get/CosmosDBGremlinDatabaseGet
    - name: /MongoDBResources/get/CosmosDBMongoDBDatabaseGet
    - name: /Database/get/CosmosDBDatabaseGetUsages
    - name: /Percentile/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /SqlResources/get/CosmosDBSqlDatabaseGet
    - name: /DatabaseAccountRegion/get/CosmosDBDatabaseAccountRegionGetMetrics
    - name: /PrivateEndpointConnections/get/Gets private endpoint connection.
    - name: /TableResources/get/CosmosDBTableGet
    - name: /PrivateLinkResources/get/Gets private endpoint connection.
    - name: /CassandraResources/get/CosmosDBCassandraKeyspaceList
    - name: /NotebookWorkspaces/get/CosmosDBNotebookWorkspaceList
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountGetMetricDefinitions
    - name: /MongoDBResources/get/CosmosDBMongoDBDatabaseList
    - name: /GremlinResources/get/CosmosDBGremlinDatabaseList
    - name: /SqlResources/get/CosmosDBSqlDatabaseList
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountListReadOnlyKeys
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountGetMetrics
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountGetUsages
    - name: /TableResources/get/CosmosDBTableList
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountGet
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountListByResourceGroup
    - name: /DatabaseAccounts/get/CosmosDBDatabaseAccountList
    - name: /Operations/get/CosmosDBOperationsList
    - name: /MongoDBResources/post/CosmosDBMongoDBCollectionMigrateToManualThroughput
    - name: /SqlResources/post/CosmosDBSqlContainerMigrateToManualThroughput
    - name: /MongoDBResources/post/CosmosDBMongoDBCollectionMigrateToAutoscale
    - name: /CassandraResources/post/CosmosDBCassandraTableMigrateToManualThroughput
    - name: /GremlinResources/post/CosmosDBGremlinGraphMigrateToManualThroughput
    - name: /SqlResources/post/CosmosDBSqlContainerMigrateToAutoscale
    - name: /CassandraResources/post/CosmosDBCassandraTableMigrateToAutoscale
    - name: /GremlinResources/post/CosmosDBGremlinGraphMigrateToAutoscale
    - name: /CassandraResources/post/CosmosDBCassandraKeyspaceMigrateToManualThroughput
    - name: /MongoDBResources/post/CosmosDBMongoDBDatabaseMigrateToManualThroughput
    - name: /GremlinResources/post/CosmosDBGremlinDatabaseMigrateToManualThroughput
    - name: /SqlResources/post/CosmosDBSqlDatabaseMigrateToManualThroughput
    - name: /CassandraResources/post/CosmosDBCassandraKeyspaceMigrateToAutoscale
    - name: /MongoDBResources/post/CosmosDBMongoDBDatabaseMigrateToAutoscale
    - name: /GremlinResources/post/CosmosDBGremlinDatabaseMigrateToAutoscale
    - name: /SqlResources/post/CosmosDBSqlDatabaseMigrateToAutoscale
    - name: /TableResources/post/CosmosDBTableMigrateToManualThroughput
    - name: /TableResources/post/CosmosDBTableMigrateToAutoscale
    - name: /NotebookWorkspaces/post/CosmosDBNotebookWorkspaceRegenerateAuthToken
    - name: /NotebookWorkspaces/post/CosmosDBNotebookWorkspaceListConnectionInfo
    - name: /NotebookWorkspaces/post/CosmosDBNotebookWorkspaceStart
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountFailoverPriorityChange
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountListConnectionStrings
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountListConnectionStringsMongo
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountOfflineRegion
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountRegenerateKey
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountListReadOnlyKeys
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountOnlineRegion
    - name: /DatabaseAccounts/post/CosmosDBDatabaseAccountListKeys
    - name: /DatabaseAccounts/patch/CosmosDBDatabaseAccountPatch
    - name: /DatabaseAccounts/head/CosmosDBDatabaseAccountCheckNameExists
    - name: /SqlResources/delete/CosmosDBSqlUserDefinedFunctionDelete
    - name: /SqlResources/delete/CosmosDBSqlStoredProcedureDelete
    - name: /SqlResources/delete/CosmosDBSqlTriggerDelete
    - name: /MongoDBResources/delete/CosmosDBMongoDBCollectionDelete
    - name: /PrivateEndpointConnections/delete/Deletes a private endpoint connection with a given name.
    - name: /SqlResources/delete/CosmosDBSqlContainerDelete
    - name: /CassandraResources/delete/CosmosDBCassandraTableDelete
    - name: /GremlinResources/delete/CosmosDBGremlinGraphDelete
    - name: /NotebookWorkspaces/delete/CosmosDBNotebookWorkspaceDelete
    - name: /CassandraResources/delete/CosmosDBCassandraKeyspaceDelete
    - name: /MongoDBResources/delete/CosmosDBMongoDBDatabaseDelete
    - name: /GremlinResources/delete/CosmosDBGremlinDatabaseDelete
    - name: /SqlResources/delete/CosmosDBSqlDatabaseDelete
    - name: /TableResources/delete/CosmosDBTableDelete
    - name: /DatabaseAccounts/delete/CosmosDBDatabaseAccountDelete
```
