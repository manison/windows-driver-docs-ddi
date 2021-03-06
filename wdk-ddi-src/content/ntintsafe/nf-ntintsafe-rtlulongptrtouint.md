---
UID: NF:ntintsafe.RtlULongPtrToUInt
title: RtlULongPtrToUInt function
description: Converts a value of type ULONG_PTR to a value of type UINT.
old-location: kernel\rtlulongptrtouint.htm
tech.root: kernel
ms.assetid: 0AD17F2A-8681-4C30-979A-D7DBBA21AD08
ms.date: 04/30/2018
ms.keywords: RtlULongPtrToUInt, RtlULongPtrToUInt function [Kernel-Mode Driver Architecture], kernel.rtlulongptrtouint, ntintsafe/RtlULongPtrToUInt
ms.topic: function
req.header: ntintsafe.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	HeaderDef
api_location:
-	Ntintsafe.h
api_name:
-	RtlULongPtrToUInt
product:
- Windows
targetos: Windows
req.typenames: 
---

# RtlULongPtrToUInt function


## -description


Converts a value of type <b>ULONG_PTR</b> to a value of type <b>UINT</b>.


## -parameters




### -param ulOperand [in]

The value to be converted.


### -param puResult [out]

A pointer to the converted value. In the case where the conversion causes a truncation of the original value, the function returns STATUS_INTEGER_OVERFLOW and this parameter is not valid.


## -remarks



This is one of a set of inline functions designed to provide type conversions and perform validity checks with minimal impact on performance.



