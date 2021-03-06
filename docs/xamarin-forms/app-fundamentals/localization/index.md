---
title: "Xamarin.Forms Localization"
description: "The built-in .NET localization framework can be used to build cross-platform multilingual applications with Xamarin.Forms."
ms.prod: xamarin
ms.assetid: 97BF843B-BDAA-4CEA-8189-6DB54B291D7F
ms.technology: xamarin-forms
author: davidbritch
ms.author: dabritch
ms.date: 04/13/2018
---

# Localization

_The built-in .NET localization framework can be used to build cross-platform multilingual applications with Xamarin.Forms._

## [String and Image Localization](text.md)

The built-in mechanism for localizing .NET applications uses [RESX files](http://msdn.microsoft.com/library/ekyft91f(v=vs.90).aspx) and the classes in the `System.Resources` and `System.Globalization` namespaces. The RESX files containing translated strings are embedded in the Xamarin.Forms assembly, along with a compiler-generated class that provides strongly-typed access to the translations. The translated text can then be retrieved in code.

## [Right-to-Left Localization](right-to-left.md)

Flow direction is the direction in which the UI elements on the page are scanned by the eye. Right-to-left localization adds support for right-to-left flow direction to Xamarin.Forms applications.
