---
title: Overview of Cloud for Sustainability water data model (Preview) - Common Data Model | Microsoft Docs
description: SustainabilityWater is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 10/5/2022
ms.author: cdmditeam
---

# Overview of Cloud for Sustainability water data model (Preview)

The Cloud for Sustainability water data model (Preview) empowers organizations to unify, store and prepare water measurement data from their facilities into a single data model to help meet water sustainability goals. The Cloud for Sustainability water data model (Preview) provides the schema required for storing and linking water quality and quantity measurement data and water sustainability reference data. The schema makes water sustainability data available for use cases such as water sustainability disclosures and regulatory water quality reporting.

For more information, see the [Microsoft Cloud for Sustainability water data model](/industry/sustainability/water-data-model-intro) documentation. The documentation includes [introductory information](/industry/sustainability/water-data-model-intro) about the data model, as well as information about the [required attributes](/industry/sustainability/water-data-model-required-attributes).

## Entities

|Name|Description|
|---|---|
|[WaterInstrument](WaterInstrument.md)|Stores the information related to the devices or instruments tracking water in the organization.|
|[WaterInstrumentConfiguration](WaterInstrumentConfiguration.md)|Entity to describe the configuration of the water flow through each water instrument present in the organization.|
|[WaterQualityAnalysis](WaterQualityAnalysis.md)|Describes the analysis performed to test a water sample for a certain characteristic.|
|[WaterQualityCharacteristic](WaterQualityCharacteristic.md)|Describes the property being evaluated during the analysis of the water sample collected.|
|[WaterQualityTestResult](WaterQualityTestResult.md)|Describes the results coming from the laboratory water quality test for a characteristic in the water sample.|
|[WaterQuantity](WaterQuantity.md)|Stores the actual quantity information from water transactions within the organization.|
|[WaterSample](WaterSample.md)|Stores the attributes of the water samples collected for testing water quality.|
|[WaterSource](WaterSource.md)|Entity to store details of sources from/to which water gets withdrawn/discharged.|

## Common entities shared with Cloud for Sustainability data model

|Name|Description|
|---|---|
|[Facility](Facility.md)|Base-level location to attribute activity data. May contain multiple buildings and organizational units.|
|[IndustrialProcessType](IndustrialProcessType.md)|Entity to store process classifications for various industrial processes, such as extraction and manufacturing processes.|
|[OrganizationalUnit](OrganizationalUnit.md)|A structural division of a company or organization.|
|[Unit](Unit.md)|Unit of measure.|
|[UnitGroup](UnitGroup.md)|Grouping of units.|