---
Description: UserLogonCred
MS-HAID: CarrierControlSchema\_v2.element\_UserLogonCred
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: UserLogonCred
ms.assetid: 0d8748d5-a1e7-4535-a5cc-9c9f380eed32
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# UserLogonCred


Defines the user login credentials for a context in the Packet Data Protocol (PDP) context policy.

## Element hierarchy

<dl>
<dt><a href="element-extensions-v2.md">&lt;Extensions_v2&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-additionalpdpcontexts.md">&lt;AdditionalPDPContexts&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-multiplepdpcontextpolicies.md">&lt;MultiplePDPContextPolicies&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-pdpcontextpolicy.md">&lt;PDPContextPolicy&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-context.md">&lt;Context&gt;</a></dt>
<dd><b>&lt;UserLogonCred&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>
<dl>
<dt><a href="element-tetheringsettings.md">&lt;TetheringSettings&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-tetheringprofile.md">&lt;TetheringProfile&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-1-context.md">&lt;Context&gt;</a></dt>
<dd><b>&lt;UserLogonCred&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<UserLogonCred>

  <!-- Child elements -->
  UserName,
  Password?

</UserLogonCred>
```

### Key

`?`   optional (zero or one)

## Attributes and Elements


### Attributes

None.

### Child Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Child Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Password](element-password.md)</td>
<td><p>Defines the password used for the Packet Data Protocol (PDP) context activation.</p></td>
</tr>
<tr class="even">
<td>[UserName](element-username.md)</td>
<td><p>Defines the username used for the Packet Data Protocol (PDP) context activation.</p></td>
</tr>
</tbody>
</table>

 

### Parent Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parent Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Context](element-context.md)</td>
<td><p>Defines the context of a Packet Data Protocol (PDP) context policy in a subscriber's carrier provisioning file.</p></td>
</tr>
</tbody>
</table>

 

## See also


[**AdditionalPDPContexts**](element-additionalpdpcontexts.md)

[CarrierControlSchema schema](https://msdn.microsoft.com/library/windows/apps/hh868312)

[CarrierControlSchema\_v2 schema](schema-root.md)

[**Context**](element-context.md)

[**MultiplePDPContextPolicies**](element-multiplepdpcontextpolicies.md)

[**PDPContextPolicy**](element-pdpcontextpolicy.md)

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/v2</p></td>
</tr>
</tbody>
</table>

 

 


