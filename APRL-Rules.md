## Azure Databricks Summary of Recommendations

| Recommendation                                                                                                                                                                                                                     | Impact |  State   | ARG Query Available |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: | :-----:  | :-----------------: |
| [DBW-1 - Databricks runtime version is not latest and/or is not LTS version](#dbw-1---databricks-runtime-version-is-not-latest-or-is-not-lts-version)                                                                              | Medium | Verified |         No         |
| [DBW-2 - Use Databricks Pools](#dbw-2---use-databricks-pools)                                                                                                                                                                      |  High  | Verified |         No         |
| [DBW-3 - Use SSD backed VMs for Worker VM Type and Driver type](#dbw-3---use-ssd-backed-vms-for-worker-vm-type-and-driver-type)                                                                                                    | Medium | Verified |         No         |
| [DBW-4 - Enable autoscaling for batch workloads](#dbw-4---enable-autoscaling-for-batch-workloads)                                                                                                                                  |  High  | Verified |         No         |
| [DBW-5 - Enable autoscaling for SQL warehouse](#dbw-5---enable-autoscaling-for-sql-warehouse)                                                                                                                                      |  High  | Verified |         No         |
| [DBW-6 - Use Delta Live Tables enhanced autoscaling](#dbw-6---use-delta-live-tables-enhanced-autoscaling)                                                                                                                          | Medium | Verified |         No         |
| [DBW-7 - Automatic Job Termination is enabled, ensure there are no user-defined local processes](#dbw-7---automatic-job-termination-is-enabled-ensure-there-are-no-user-defined-local-processes)                                   | Medium | Verified |         No         |
| [DBW-8 - Enable Logging-Cluster log delivery](#dbw-8---enable-logging-cluster-log-delivery)                                                                                                                                        | Medium | Verified |         No         |
| [DBW-9 - Use Delta Lake for higher reliability](#dbw-9---use-delta-lake-for-higher-reliability)                                                                                                                                    |  High  | Verified |         No         |
| [DBW-10 - Use Photon Acceleration](#dbw-10---use-photon-acceleration)                                                                                                                                                              |  Low   | Verified |         No         |
| [DBW-11 - Automatically rescue invalid or nonconforming data with Databricks Auto Loader or Delta Live Tables](#dbw-11---automatically-rescue-invalid-or-nonconforming-data-with-databricks-auto-loader-or-delta-live-tables)      |  Low   | Verified |         No         |
| [DBW-12 - Configure jobs for automatic retries and termination](#dbw-12---configure-jobs-for-automatic-retries-and-termination)                                                                                                    |  High  | Verified |         No         |
| [DBW-13 - Use a scalable and production-grade model serving infrastructure](#dbw-13---use-a-scalable-and-production-grade-model-serving-infrastructure)                                                                            |  High  | Verified |         No         |
| [DBW-14 - Use a layered storage architecture](#dbw-14---use-a-layered-storage-architecture)                                                                                                                                        | Medium | Verified |         No         |
| [DBW-15 - Improve data integrity by reducing data redundancy](#dbw-15---improve-data-integrity-by-reducing-data-redundancy)                                                                                                        |  Low   | Verified |         No         |
| [DBW-16 - Actively manage schemas](#dbw-16---actively-manage-schemas)                                                                                                                                                              | Medium | Verified |         No         |
| [DBW-17 - Use constraints and data expectations](#dbw-17---use-constraints-and-data-expectations)                                                                                                                                  |  Low   | Verified |         No         |
| [DBW-18 - Create regular backups](#dbw-18---create-regular-backups)                                                                                                                                                                |  Low   | Verified |         No         |
| [DBW-19 - Recover from Structured Streaming query failures](#dbw-19---recover-from-structured-streaming-query-failures)                                                                                                            |  High  | Verified |         No         |
| [DBW-20 - Recover ETL jobs based on Delta time travel](#dbw-20---recover-etl-jobs-based-on-delta-time-travel)                                                                                                                      | Medium | Verified |         No         |
| [DBW-21 - Use Databricks Workflows and built-in recovery](#dbw-21---use-databricks-workflows-and-built-in-recovery)                                                                                                                |  Low   | Verified |         No         |
| [DBW-22 - Configure a disaster recovery pattern](#dbw-22---configure-a-disaster-recovery-pattern)                                                                                                                                  |  High  | Preview  |         No         |
| [DBW-23 - Automate deployments and workloads](#dbw-23---automate-deployments-and-workloads)                                                                                                                                        |  High  | Preview  |         No         |
| [DBW-24 - Set up monitoring, alerting, and logging](#dbw-24---set-up-monitoring-alerting-and-logging)                                                                                                                              |  High  | Preview  |         No         |
| [DBW-25 - Deploy workspaces in separate Subscriptions](#dbw-25---deploy-workspaces-in-separate-subscriptions)                                                                                                                      |  High  | Preview  |         No         |
| [DBW-26 - Isolate each workspace in its own Vnet](#dbw-26---isolate-each-workspace-in-its-own-vnet)                                                                                                                                |  High  | Preview  |         No         |
| [DBW-27 - Do not Store any Production Data in Default DBFS Folders](#dbw-27---do-not-store-any-production-data-in-default-dbfs-folders)                                                                                            |  High  | Preview  |         No         |
| [DBW-28 - Do not use Azure Sport VMs for critical Production workloads](#dbw-28---do-not-use-azure-sport-vms-for-critical-production-workloads)                                                                                    |  High  | Preview  |         No         |


## Compute Gallery Summary of Recommendations

{{< table style="table-striped" >}}
| Recommendation                                                                                                                                                                                                                     | Impact |  State  | ARG Query Available |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: | :-----: | :-----------------: |
| [CG-1 - A minimum of three replicas should be kept for production image versions](#cg-1---a-minimum-of-three-replicas-should-be-kept-for-production-image-versions)                                                                                                                          |  Medium  | Preview |         Yes         |
| [CG-2 - Zone redundant storage should be used for image versions](#cg-2---zone-redundant-storage-should-be-used-for-image-versions)                                                                                                                          |  Medium  | Preview |         Yes         |
| [CG-3 - Consider using hyper-V generation version 2 images where possible](#cg-3---consider-using-hyper-v-generation-version-2-images-where-possible)         

## Image Templates Summary of Recommendations

{{< table style="table-striped" >}}
| Recommendation                                                                                                                                                                                                                     | Impact |  State  | ARG Query Available |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: | :-----: | :-----------------: |
| [IT-1 - Use Generation 2 virtual machine source image](#it-1---use-generation-2-virtual-machine-source-image)                                                                                                                          |  Low  | Preview |         No         |
| [IT-2 - Replicate your Image Templates to a secondary region](#it-2---replicate-your-image-templates-to-a-secondary-region)  

## Azure Site Recovery Summary of Recommendations

{{< table style="table-striped" >}}
| Recommendation                                                                                                                                                                                                                     | Impact |  State  | ARG Query Available |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: | :-----: | :-----------------: |
| [ASR-1 - Ensure static IP addresses configured in VM failover settings are available in the failover subnet](#asr-1---ensure-static-ip-addresses-configured-in-vm-failover-settings-are-available-in-the-failover-subnet)                                                                                                                          |  High  | Preview |         No         |