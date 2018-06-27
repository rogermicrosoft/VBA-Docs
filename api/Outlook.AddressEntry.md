---
title: AddressEntry Object (Outlook)
keywords: vbaol11.chm2037
f1_keywords:
- vbaol11.chm2037
ms.prod: outlook
api_name:
- Outlook.AddressEntry
ms.assetid: d4a0a85e-8bab-bc56-57bc-d70c3c570c8e
ms.date: 06/08/2017
---


# AddressEntry Object (Outlook)

Represents a person, group, or public folder to which the messaging system can deliver messages.


## Remarks

The  **AddressEntry** object is an address in an **[AddressEntries](Outlook.AddressEntries.md)** object. Each **AddressEntry** object in the **AddressEntries** object holds information that represents a person, group, or public folder to which the messaging system can deliver messages.

Use  **AddressEntries** ( _index_ ), where _index_ is the index number of an address entry or a value used to match the default property of an address entry, to return a single **AddressEntry** object.


## Example

The following example sets a reference to an  **AddressEntry** object.


```vb
Set myAddressEntry = myRecipient.AddressEntry 
 

```


## Methods



|**Name**|
|:-----|
|[Delete](./Outlook.AddressEntry.Delete.md)|
|[Details](./Outlook.AddressEntry.Details.md)|
|[GetContact](./Outlook.AddressEntry.GetContact.md)|
|[GetExchangeDistributionList](./Outlook.AddressEntry.GetExchangeDistributionList.md)|
|[GetExchangeUser](./Outlook.AddressEntry.GetExchangeUser.md)|
|[GetFreeBusy](./Outlook.AddressEntry.GetFreeBusy.md)|
|[Update](./Outlook.AddressEntry.Update.md)|

## Properties



|**Name**|
|:-----|
|[Address](./Outlook.AddressEntry.Address.md)|
|[AddressEntryUserType](./Outlook.AddressEntry.AddressEntryUserType.md)|
|[Application](./Outlook.AddressEntry.Application.md)|
|[Class](./Outlook.AddressEntry.Class.md)|
|[DisplayType](./Outlook.AddressEntry.DisplayType.md)|
|[ID](./Outlook.AddressEntry.ID.md)|
|[Name](./Outlook.AddressEntry.Name.md)|
|[Parent](./Outlook.AddressEntry.Parent.md)|
|[PropertyAccessor](./Outlook.AddressEntry.PropertyAccessor.md)|
|[Session](./Outlook.AddressEntry.Session.md)|
|[Type](./Outlook.AddressEntry.Type.md)|

## See also


[Outlook Object Model Reference](./overview/object-model-outlook-vba-reference.md)
[AddressEntry Object Members](http://msdn.microsoft.com/library/74c88069-aec4-952b-556f-03873fbb488b%28Office.15%29.aspx)