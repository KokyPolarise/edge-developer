---
description: Contains information about the completed webview navigation
title: NavigationCompletedEvent object
author: libbymc
ms.author: libbymc
ms.date: 2/12/2018
ms.topic: reference
ms.prod: microsoft-edge
keywords: webview, windows 10 apps, uwp, edge
---

# NavigationCompletedEvent object

An object that represents an event fired when the [webview](../webview.md) has finished loading the current content or if navigation has failed.

## Properties
    
### isSuccess

Gets a value that indicates whether the navigation completed successfully.

This property is read-only

```js
var isSuccess = NavigationCompletedEvent.isSuccess;
```

#### Property value
Type: **Boolean**

### webErrorStatus

If the navigation was unsuccessful, gets a value that indicates why.

This property is read-only

```js
var webErrorStatus = NavigationCompletedEvent.webErrorStatus;
```

#### Property value
Type: **unsigned long**