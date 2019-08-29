---
title: BookableResourceCharacteristic - Common Data Model | Microsoft Docs
description: This describes the BookableResourceCharacteristic entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Bookable Resource Characteristic

Associates resources with their characteristics and specifies the proficiency level of a resource for that characteristic.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/BookableResourceCharacteristic.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/BookableResourceCharacteristic](../../../BookableResourceCharacteristic.md "/core/applicationCommon/foundationCommon/BookableResourceCharacteristic.cdm.json/BookableResourceCharacteristic")  
- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/BookableResourceCharacteristic  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[bookableResourceCharacteristicId](#bookableResourceCharacteristicId)|Unique identifier of the resource characteristic.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[name](#name)|Type the name of the association between the resource and characteristic.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[characteristic](#characteristic)|Choose the characteristic to associate with the resource.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[ratingValue](#ratingValue)|Select a rating value that represents the evaluation of a characteristic for a particular resource.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[resource](#resource)|Shows the resource associated with the characteristic.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[stateCode](#stateCode)|Status of the Bookable Resource Characteristic|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[statusCode](#statusCode)|Reason for the status of the Bookable Resource Characteristic|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the bookableresourcecharacteristic with respect to the base currency.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the BookableResourceCharacteristic with respect to the base currency.|<a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>|
|[approvalStatus](#approvalStatus)||<a href="BookableResourceCharacteristic.md" target="_blank">projectServiceAutomation/BookableResourceCharacteristic</a>|
|[approvalStatus_display](#approvalStatus_display)||<a href="BookableResourceCharacteristic.md" target="_blank">projectServiceAutomation/BookableResourceCharacteristic</a>|
|[supportingRecord](#supportingRecord)||<a href="BookableResourceCharacteristic.md" target="_blank">projectServiceAutomation/BookableResourceCharacteristic</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableResourceCharacteristicId name="bookableResourceCharacteristicId">bookableResourceCharacteristicId</a>

Unique identifier of the resource characteristic.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource Characteristic</td></tr><tr><td>description</td><td>Unique identifier of the resource characteristic.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bookableresourcecharacteristicid</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the association between the resource and characteristic.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the association between the resource and characteristic.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#characteristic name="characteristic">characteristic</a>

Choose the characteristic to associate with the resource.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Characteristic</td></tr><tr><td>description</td><td>Choose the characteristic to associate with the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>characteristic</td></tr></table>

### <a href=#ratingValue name="ratingValue">ratingValue</a>

Select a rating value that represents the evaluation of a characteristic for a particular resource.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating Value</td></tr><tr><td>description</td><td>Select a rating value that represents the evaluation of a characteristic for a particular resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ratingvalue</td></tr></table>

### <a href=#resource name="resource">resource</a>

Shows the resource associated with the characteristic.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Shows the resource associated with the characteristic.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resource</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Bookable Resource Characteristic  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Bookable Resource Characteristic</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Bookable Resource Characteristic  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Bookable Resource Characteristic</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the bookableresourcecharacteristic with respect to the base currency.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the bookableresourcecharacteristic with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the BookableResourceCharacteristic with respect to the base currency.  
First included in: <a href="../../../BookableResourceCharacteristic.md" target="_blank">foundationCommon/BookableResourceCharacteristic</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the BookableResourceCharacteristic with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#approvalStatus name="approvalStatus">approvalStatus</a>

First included in: projectServiceAutomation/BookableResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approval status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_approvalstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Saved</td><td>192350000</td></tr><tr><td>en</td><td>Pending Approval</td><td>192350001</td></tr><tr><td>en</td><td>Rejected</td><td>192350002</td></tr><tr><td>en</td><td>Approved</td><td>192350003</td></tr><tr><td>en</td><td>Recalled</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#approvalStatus_display name="approvalStatus_display">approvalStatus_display</a>

First included in: projectServiceAutomation/BookableResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#supportingRecord name="supportingRecord">supportingRecord</a>

First included in: projectServiceAutomation/BookableResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Supporting Record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_supportingrecord</td></tr></table>