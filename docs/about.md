---
sidebar_position: 1000
---

# About Ed

My entire software development career has been at [one amazing company](https://www.logos.com/), where I have worked for over 30 years. I've never written a résumé, and hopefully I'll never need to, but read on for the highlights of my career thus far.

## Logos Career Highlights

### 1994

* Participated in an eight-week summer internship at [Logos Research Systems](https://web.archive.org/web/19970111004712/http://www.logos.com/), a two-year-old company working on the second generation of their flagship product, a Windows app called [Logos Bible Software](https://youtu.be/fxju12fyebU).
* Wrote a Windows 3.1 app in [C](https://en.wikipedia.org/wiki/C_(programming_language)) to transform files from a dictionary publisher into Logos [RTF](https://en.wikipedia.org/wiki/Rich_Text_Format), the format used to compile Logos Bible Software books.

### 1995

* Started full time at Logos in June. Logos 2.0 was close to shipping, so I was assigned other projects.
* Worked on a [C++](https://en.wikipedia.org/wiki/C%2B%2B)/[MFC](https://en.wikipedia.org/wiki/Microsoft_Foundation_Class_Library) Windows application for displaying timelines, which was ultimately abandoned.
* Began a long tradition of writing utility code, starting with `CBoolArray` and `WindowPlacement` and quickly growing to a large library of C++ classes and functions.

### 1996

* Wrote Logos Send Mail, a C++/MFC Windows application that sent email to many recipients one at a time.
* Wrote [Logos Lesson Builder](https://web.archive.org/web/20001109224500/http://www.logos.com/products/bstudy.asp), a C++/MFC Windows application that allowed users to print Bible study booklets and make their own, with support for rich text and dynamic style switching.
* Wrote a C++ library implementing the [DIESEL](https://www.fourmilab.ch/diesel/) text transformation language (with some modifications), used first by Logos Lesson Builder and eventually to help convert books to the Logos format, to render data type references, and to define citation formats.

### 1997

* Wrote the Logos Perl Debugger, a C++/MFC Windows application for debugging [Perl](https://en.wikipedia.org/wiki/Perl) scripts, which was soon sold to [ActiveState](https://web.archive.org/web/19981206194258/http://www.activestate.com/pldb/) and licensed back from them for our continued use.
* Invented LGM, an [SGML](https://en.wikipedia.org/wiki/Standard_Generalized_Markup_Language) markup language inspired by [TEI](https://en.wikipedia.org/wiki/Text_Encoding_Initiative), to enable a two-stage process for converting books from publisher files into the Logos RTF format used to compile books.
* Wrote Shadrach, which leveraged declarative rules and DIESEL to transform SGML to other formats.
* Wrote Ezra—a Perl script, Visual Studio macros, and Shadrach rules—for extracting specially-formatted C++ code comments and converting them to documentation.

### 1998

* Led the architectural design of the [Libronix Digital Library System](https://web.archive.org/web/20011211125211/http://www.logos.com/products/ldls/) (LDLS), a rewrite of the Logos Bible Software Windows app, released in 2001.
* Started building the [COM](https://en.wikipedia.org/wiki/Component_Object_Model) libraries upon which the LDLS would be built, using the [ATL](https://en.wikipedia.org/wiki/Active_Template_Library) C++ library.
* Established, documented, and enforced coding guidelines for our C++ applications.
* Created Rachel (a stylesheet builder) and Michael (a project manager). Combined with Shadrach and Gabriel (the book compiler), they formed the Libronix Publisher's Toolkit.
* Wrote C++ libraries and tools for processing [MARC](https://en.wikipedia.org/wiki/MARC_standards) records.

### 1999

* Made significant contributions to LDLS, using C++/[WTL](https://en.wikipedia.org/wiki/Windows_Template_Library) for the main window and book display, [HTML](https://en.wikipedia.org/wiki/HTML)/[JavaScript](https://en.wikipedia.org/wiki/JavaScript) for reports and dialogs, and C++/ATL for the backend COM library leveraged by those reports and dialogs.
* Created a COM library and declarative [XML](https://en.wikipedia.org/wiki/XML) format as an abstraction over [ActiveBar](https://web.archive.org/web/20000816133933/http://www.datadynamics.com/products/), a third-party toolbar library.

### 2000–2005

* Made continued contributions to LDLS, building an increasingly large codebase of C++ and COM.
* Wrote a Prayer List application for the [Palm PDA](https://en.wikipedia.org/wiki/Palm_(PDA)) (personal digital assistant) in C++.
* Wrote ClassesEtc, a JavaScript library to facilitate object-oriented code, and used it to improve the development of LDLS reports.
* Designed a [wiki](https://en.wikipedia.org/wiki/Wiki) syntax and wrote EdgeWiki, a personal project using [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language)) 2.0 and the [ASP.NET](https://en.wikipedia.org/wiki/ASP.NET) web framework. It was eventually adopted as the official Logos wiki.

### 2006–2010

* Helped persuade Logos to start yet another rewrite of Logos Bible Software, this time using C#/.NET and [WPF](https://en.wikipedia.org/wiki/Windows_Presentation_Foundation), the new user interface platform for Windows.
* Designed, architected, and implemented many C# and WPF components for what was released as [Logos 4](https://web.archive.org/web/20100131001144/http://www.logos.com/) in late 2009.
* Key early contributions to Logos 4 included a new rich text format, concepts and APIs for accessing data types and resources, a tiled user interface paradigm for the main application, and an ever-growing library of utility code.
* Wrote [NoteScraps](https://web.archive.org/web/20070202060532/http://notescraps.com/), a C#/WPF Windows application for taking notes.

### 2011

* Designed and implemented the Logos Sync Framework, a web service architecture for synchronizing data from desktop applications to the cloud, using C# on both the client and the server, storing client data in [SQLite](https://sqlite.org/) databases and server data in [SQL Server](https://www.microsoft.com/en-us/sql-server) databases, and communicating via [JSON](https://www.json.org/json-en.html) over [HTTP](https://en.wikipedia.org/wiki/HTTP).
* Helped integrate Sync into Logos Bible Software as well as [Proclaim](https://proclaim.logos.com/), our new church presentation software.

### 2012

* Co-wrote the Verse of the Day application for Windows Store using C# and the [Windows RT](https://en.wikipedia.org/wiki/Windows_RT) framework.
* Wrote the User Event Service to reduce the number of web service calls required to sync the Logos Bible Software app.

### 2013

* Designed and implemented the backend web service for Amber, the Logos digital asset manager.
* Wrote a prototype Logos book viewer for the web.

### 2014

* Designed and implemented the Verse of the Day API, allowing applications direct access to Verse of the Day media from Amber.
* Made ongoing contributions to Amber and Logos Bible Software.

### 2015

* Wrote [Faithlife.Parsing](https://github.com/Faithlife/Parsing), a C# library for parsing DSLs (domain-specific languages), and released it as open source.
* Created the Faithlife Service Framework, which used a [DSL](https://en.wikipedia.org/wiki/Domain-specific_language) to define [web APIs](https://en.wikipedia.org/wiki/Web_API) and generated C# code to help implement both clients and servers.
* Leveraged the Faithlife Service Framework to design and implement digital library web APIs for rich text, data types, and access to users' licensed books.

### 2016

* Renamed the Faithlife Service Framework to the [Facility API Framework](https://facilityapi.github.io/) and released it as open source.
* Added Facility code generators for JavaScript, [TypeScript](https://www.typescriptlang.org/), and [Markdown](https://en.wikipedia.org/wiki/Markdown). Also supported conversion to and from [Swagger](https://swagger.io/) aka [OpenAPI](https://www.openapis.org/).
* Wrote and used [XmlDocMarkdown](https://github.com/ejball/XmlDocMarkdown), an open source tool to generate Markdown documentation from C# XML comments.
* Continued contributions to digital library APIs and Logos Bible Software, including support for storing and leveraging data needed to preserve note highlights when Logos books are modified.

### 2017–2018

* Architected and implemented the backend for the next generation of the Notes feature of Logos Bible Software, storing data in SQLite on the client and in [MySQL](https://www.mysql.com/) on the server, supporting both synchronization and direct API access, all leveraging the Facility API Framework.
* Created a background service to migrate synchronized previous-generation notes, which continued to be created on old clients for many years.
* Continued contributions to digital library APIs, particularly for book access in the Logos Bible Software web app.

### 2019

* Wrote [Faithlife.Build](https://github.com/Faithlife/FaithlifeBuild), an open source C# build automation library akin to Cake but simpler, ultimately adopted by all new Logos projects.
* Wrote [Faithlife.Data](https://github.com/Faithlife/FaithlifeData), an open source library for querying ADO.NET-compatible databases with a better API than the leading library and support for the SQLite library used by Logos.
* Added [ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet) support to Facility.

### 2020

* Designed and implemented the client-side and server-side backend for the Factbook feature of Logos Bible Software.
* Wrote a web service to migrate Wordsearch user data to Logos.

### 2021

* Implemented many performance optimizations for Logos Bible Software.

### 2022

* Finalized the design and implementation of the new query syntax released with Logos 10.

### 2023

* Researched AI-enhanced search algorithms and providers, leveraging a [Blazor](https://learn.microsoft.com/en-us/aspnet/core/blazor/) prototype app for experimentation.
* Integrated [Azure AI Search](https://azure.microsoft.com/en-us/products/ai-services/ai-search) into the Logos book search API, released to customers on all platforms as Smart Search in early 2024.
* Leveraged generative API (the technology behind [ChatGPT](https://chatgpt.com/)) to summarize Smart Search results on demand.
* Enhanced Faithlife.Configuration, a library enabling single-file multi-environment configuration for ASP.NET Core.
* Ported multiple web APIs from .NET Framework to .NET Core.
* Assembled a year's worth of "coder tips" from software development books and websites, and wrote a script to post one per workday to a Logos Slack channel.

### 2024

* Designed and implemented AI API, an API for generative AI that provides unified access to AI models from multiple vendors, tracks AI costs, and caches AI output.
* Wrote a web app to facilitate AI prompt engineering using Blazor and leveraging modern HTML, CSS, and JavaScript.
* Implemented Help search using the same technology as Smart Search.
* Wrote the backend implementation for multiple sections of the new-and-improved Factbook feature.
* Integrated vector search into Smart Search in preparation for release in 2025.
* Designed and implemented an evaluation web app to fine-tune vector search algorithms by running queries, evaluating the results with AI, and calculating industry-standard statistics.

### 2025

* Finalized and deployed vector search support for Smart Search.
* Continued to maintain and improve the AI API and evaluation tooling.
* Created a chatbot API and prototype app with the ability to search and cite Logos books.
* Released [MuchAdo](https://muchado.net/), the successor to Faithlife.Data.
