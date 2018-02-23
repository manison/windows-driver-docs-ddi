---
UID: NN:wdtfinterfaces.IWDTFSimpleIOStressActions2
title: IWDTFSimpleIOStressActions2
author: windows-driver-content
description: Defines operations for a collection of simple asynchronous I/O functionality tests.
old-location: dtf\iwdtfsimpleiostressactions2.htm
old-project: dtf
ms.assetid: d50bf1d1-fa36-4ab1-9173-bdaf2f5a9f28
ms.author: windowsdriverdev
ms.date: 2/20/2018
ms.keywords: dtf.iwdtfsimpleiostressactions2, IWDTFSimpleIOStressActions2 interface [Windows Device Testing Framework], IWDTFSimpleIOStressActions2 interface [Windows Device Testing Framework], described, IWDTFSimpleIOStressActions2, wdtfinterfaces/IWDTFSimpleIOStressActions2
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: interface
req.header: wdtfinterfaces.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WDTFInterfaces.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: wdtfinterfaces.h
req.dll: 
req.irql: 
topictype:
-	APIRef
-	kbSyntax
apitype:
-	COM
apilocation:
-	wdtfinterfaces.h
apiname:
-	IWDTFSimpleIOStressActions2
product: Windows
targetos: Windows
req.typenames: TTraceLevel
req.product: Windows 10 or later.
---

# IWDTFSimpleIOStressActions2 interface


## -description


Defines operations for a collection of simple asynchronous I/O functionality tests.


## -members

The <b>IWDTFSimpleIOStressActions2</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh451185">Continue</a>
</td>
<td align="left" width="63%">
Continues the I/O.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh451187">ContinueAsync</a>
</td>
<td align="left" width="63%">
Asynchronously signals the I/O to continue.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh451189">Pause</a>
</td>
<td align="left" width="63%">
Pauses the I/O.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh973223">Start</a>
</td>
<td align="left" width="63%">
Opens the device.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh451171">StartAsync</a>
</td>
<td align="left" width="63%">
Asynchronously signals a start event to occur.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/dn927275">Stop</a>
</td>
<td align="left" width="63%">
Stops the device.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh439268">StopAsync</a>
</td>
<td align="left" width="63%">
Asynchronously signals the stop event to occur.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/library/windows/hardware/hh439271">WaitAsyncCompletion</a>
</td>
<td align="left" width="63%">
Waits for the completion of any of the asynchronous events.

</td>
</tr>
</table>Continues the I/O.

Asynchronously signals the I/O to continue.

Pauses the I/O.

Opens the device.

Asynchronously signals a start event to occur.

Stops the device.

Asynchronously signals the stop event to occur.

Waits for the completion of any of the asynchronous events.

 
