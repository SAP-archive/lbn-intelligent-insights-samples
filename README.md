# Sample for Using SAP Logistics Business Network, Intelligent Insights Option

## Description
This repository contains a sample that helps you get started with the intelligent insights option for SAP Logistics Business Network. The sample contains an anlytic story and its dependent models that were predefined in SAP Analytics Cloud. You can import the sample into your SAC tenant and start using it for the intelligent insights option.

To use the sample, complete the steps in the following order:

In your SAC tenant:
- Import the sample .tgz file.
- Modify the sample connection by replacing the tenant ID in the Host URL with the tenant ID for your intelligent insights option.
- Modify each sample model file by selecting the data source with the name **P_CV_<model_name>**.

In the SAP Fiori Launchpad window for your intelligent insights option:
- Open the **Manage Analytic Stories** app and import the sample story by choosing **Create > Add existing story**.
- Open the **Logistics Execution Insights** app. Click the settings icon, switch on **Display Story**, and select the story you just imported. You can then monitor your own logistics execution data in the dashboard.

## Requirements
The sample will run if you have the following authorizations:
- System Owner, BI Admin, or Application Creator roles in your SAC tenant
- ExecutionInsightsProcessTemplate and ManageAnalyticStoriesEditTemplate roles in your LBN tenant for intelligent insights option

## Download and Installation
The sample codes supplied in this repository are for reference use.  

To get the sample codes:

- [Clone the Git repository](https://help.github.com/articles/cloning-a-repository/) using this command:
  
  `git clone https://github.com/SAP-samples/lbn-intelligent-insights-samples`
  
- or [download the files](https://github.com/SAP-samples/lbn-intelligent-insights-samples/archive/main.zip) as a zip file.

## Known Issues
There are no known issues related to the resources included in this repository.

## How to obtain support
This project is provided "as-is" with no expected changes or support.

## Contributing
This project is only updated by SAP employees.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
