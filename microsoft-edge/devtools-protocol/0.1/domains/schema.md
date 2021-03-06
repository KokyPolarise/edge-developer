---
description: Reference for the Schema Domain. Provides information about the protocol schema.
title: Schema Domain - Microsoft Edge DevTools Protocol Version 0.1
author: pelavall
ms.author: pelavall
ms.date: 12/15/2017
ms.topic: reference
ms.prod: microsoft-edge
---
# Schema
Provides information about the protocol schema.


|                         |                           |
|-------------------------|---------------------------|
| [**Methods**](#methods) | [getDomains](#getdomains) |
|   [**Types**](#types)   |     [Domain](#domain)     |

## Methods

### getDomains
Returns supported domains.

ble>
    <thead>
        <tr>
            <th>Returns</th>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>domains</td>
            <td><a href="#domain"><code class="flyout">Domain[]</code></a></td>
            <td>List of supported domains.</td>
        </tr>
    </tbody>
</table>


---

## Types

### <a name="domain"></a> Domain `object`

Description of the protocol domain.

ble>
    <thead>
        <tr>
            <th>Properties</th>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>name</td>
            <td><code class="flyout">string</code></td>
            <td>Domain name.</td>
        </tr>
        <tr>
            <td>version</td>
            <td><code class="flyout">string</code></td>
            <td>Domain version.</td>
        </tr>
    </tbody>
</table>


---
