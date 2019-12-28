---
title: "Choosing an Editing Environment for SAP Translation"
date: 2019-09-02T22:58:49+02:00
draft: false
id: "blog"
description: "The sad truth is that most SAP translations are probably entered into Microsoft Excel spreadsheets, in a two column table with the texts exported from the SAP system on the left and the translations on the right."
---
<br>
*There are many aspects to SAP translation projects, such as scoping (finding the texts that need to be translated), translation automation, reusing existing texts, but at the end of the day, there are going to be texts from your Z programs, customizing tables, forms etc. that someone has to translate manually. This is a closer look at the most commonly used editors for entering the texts in the target language.*
### Good old Microsoft Excel
The sad truth is that most SAP translations are probably entered into Microsoft Excel spreadsheets, in a two column table with the texts exported from the SAP system on the left and the translations on the right. It’s easy to see why: spreadsheets are everywhere, and everybody knows how to use them, and many use them to do things they were never intended for. Translation is one of those things. 

![This is what translating in Microsoft Excel looks like.](/img/blog/Excel.jpg)
<center>*This is what translating in Microsoft Excel looks like, if you use the SAP Standard export functionality.*</center>

For translation of a few hundred lines, working in Excel can be a workable solution, but it does not scale well beyond that. Performance is an issue for  bigger spreadsheets, and so are the reserved characters like the equal sign that can cause trouble, but that’s not even the most important issue. Translators generally have two main concerns, they want to work efficiently by reusing translations they or other translators have entered before, and they want context for the texts they are asked to translate in order to make a knowledgable decision on what to enter when there is more than one possible translation. Microsoft Excel offers neither of these things, but most other solutions do.
### Professional TMS Solutions
If you are outsourcing your SAP translation and you are engaging the services of a translation agency, this is what most of them are working with. Solutions like SDL Studio or Memsource offer a great working environment for translators, and crucially, they all include a translation memory that all translations are stored in for later re-use. The best file format to export to when you plan to use these tools is the XML-based XLIFF format, which is supported by the SAP Standard and by all of our custom tools such as MDTM or CDTM. 

![The editing environment in Memsource.](/img/blog/Memsource.jpg)
<center>*The editing environment in Memsource, one of the biggest professional TMS solutions.*</center>

As for context,  depending on how you build the XLIFF, you can provide some metadata to your translators, such as the SAP module or text type that a text belongs to, but it’s not a lot of information. And don’t forget, if you use this solution internally instead of outsourcing, you will probably have to buy licenses for the third-party editing environment.
### Transaction SE63
Transaction SE63 gets a bad rap, mostly because if you ask your internal colleagues, the response probably won’t be very enthusiastic, and you will need to invest a lot of effort training internal translators. Its editor for short texts is simply not very user-friendly, and very complicated to use, albeit very powerful.
But consider this, with SE63 you already have a complete translation solution that SAP provides at no extra cost, which offers a built-in translation memory server and everything else you need to run highly complex SAP translation projects. It is lightning-fast, avoids any effort, performance or other technical issues resulting from exporting/importing files, and offers the most context information for translators that you are going to get from your SAP system.

![Transaction SE63's short text editor.](/img/blog/SE63.jpg)
<center>*Transaction SE63's short text editor may not look like much, but it's quite powerful.*</center>

All of that does not help you much if you are asking your internal colleagues to do the translation. But if you are considering to outsource and plan to work with translators that know their way around SE63, this is the option to choose if you need the best quality translations and a sustainable workflow that works not only for your current project, but also for updating and maintaining translation and continuously translating new texts from your custom developments.
### The Choice is Yours
While I have left out a few options for translating SAP texts, these are the most commonly used ones. There are also specialized editors available in the SAP system for texts that SAP does not consider to be user interface texts, such as F1 help texts or forms. So there are special cases that require their own editor, but for the bulk of the texts you are going to translate, you should be looking at the three options listed above.
Whichever one you select, your decision should be informed by project size, and by who will do the translating. If you are translating internally, SE63 is probably off the table. But if you are outsourcing and working with an experienced partner, it may be the best option. Just promise me one thing, try to avoid using Microsoft Excel for translating large-scale projects.


