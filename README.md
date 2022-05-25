# vagrantstore
My all Vagrant store for
```mermaid
  graph TD;
      Cloud Scheduler CBC-->Cloud pubsub CBC-->Cloud Function CBC;
      Cloud Scheduler CloudAsset-->Cloud pubsub CloudAsset-->Cloud Function CloudAsset;
      Cloud Function CBC-->BigQuery CBC;
      Cloud Function CloudAsset-->BigQuery CloudAsset;
```
