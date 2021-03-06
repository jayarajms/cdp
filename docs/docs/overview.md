# Overview

The SkyPoint Customer Data Platform enables one-to-one marketing personalization. Learn how to unify and enrich your customer data, build audiences, create cross-channel journeys, and activate customer experiences.

## Terminologies Used in the Application

- Tenants -> You can consider them as clients.

- Instance -> You can consider them as subsidiaries of a single client.

- Dataflows -> It allows you to ingest data from all your sources, transform and load into the data lake in Common Data Model (CDM) schema. You can club common data sources into single dataflow.

- Channels -> They are the visitor touchpoints that you want to monitor with SkyPointCloud.

- Entities -> Individual data sources that are present in the dataflows.

- Stitch -> It consists of 3 steps: Map, Match & Merge. 

  - Map -> It defines the profile data in your entities by choosing the profile attributes, primary key, and types (datatypes defined by SkyPoint Cloud).

  -  Match -> It identifies the unique profiles in your entities by matching records based on certain rules.
 
  - Merge -> It creates an entity of profile records by combining duplicate attributes and removing attributes you don’t need.

- Profiles -> It is generated after the entire stitch process is complete. It contains unified unique records from various entities.

- Timelines -> It shows your customer's timeline in their profiles by defining timeline data in your entities.

- Associations -> It can be used to create associations/relationships between various entities.

- Models -> It integrates your artificial intelligence and machine learning models deployed as web service endpoints to utilizing unified entities (e.g. predictions on unified customer profile and activities). 

- Export -> It exports the entities to a cloud storage account.

- Audiences -> It is a group of profiles characterized by a defined set of attributes based filters. You can schedule audiences to be auto-updated every day or update them manually for onetime use.

- Metrics -> It creates parameters to check the different insights to see if you are on track.

- Orchestrations ->

- Platform -> It consists of notifications, schedule, instance, product, activity stream.

  - Notifications -> It shows the notifications about dataflows and background processes.

  - Schedule -> It allows you to set a schedule to refresh all dataflows and autorun platform processes for the selected instance.

  - Instance -> It displays the various details of the instance such as Tenant Name, Tenant website URL, Tenant identifier, Instance name, Instance identifier, Geographical region, and Timezone.

  - Product -> It allows you to change the language.

  - Activity Stream -> It displays all the activity which was performed in the application.
