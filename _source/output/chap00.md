---
layout: page
title: "Chapter 00"
---
<span id="title_page.xhtml"></span>

<div id="title_page.xhtml#cover-image">

[for Developers](SuiteCRM)(File:images/title_page.jpg)

</div>
<span id="verso_page.xhtml"></span>

## SuiteCRM for Developers ##

### Getting started with developing for SuiteCRM ###

 

#### Jim Mackin ####

 

This book is for sale at http://leanpub.com/suitecrmfordevelopers

This version was published on 2015-05-22

[logo](publisher's)(File:images/leanpub-logo.png)

*   *   *   *   *

This is a [Leanpub](http://leanpub.com) book. Leanpub empowers authors and publishers with the Lean Publishing process. [Lean Publishing](http://leanpub.com/manifesto) is the act of publishing an in-progress ebook using lightweight tools and many iterations to get reader feedback, pivot until you have the right book and build traction once you do.

*   *   *   *   *



<div>

© 2015 Jim Mackin

</div>
<span id="toc.xhtml"></span>

<div>

## Table of Contents ##

* [class="section-number">1. </span>Introduction](<span)(#chap00.xhtml#leanpub-auto-introduction)
** [is SuiteCRM](What)(#chap00.xhtml#leanpub-auto-what-is-suitecrm)
** [book](This)(#chap00.xhtml#leanpub-auto-this-book)
** [this book](Reading)(#chap00.xhtml#leanpub-auto-reading-this-book)
** [up SuiteCRM](Setting)(#chap00.xhtml#leanpub-auto-setting-up-suitecrm)
** [Tweaks](Initial)(#chap00.xhtml#leanpub-auto-initial-tweaks)
* [class="section-number">2. </span>SuiteCRM Directory Structure](<span)(#chap01.xhtml#leanpub-auto-suitecrm-directory-structure)
* [class="section-number">3. </span>Working with Beans](<span)(#chap02.xhtml#working-with-beans-chapter)
** [BeanFactory](#chap02.xhtml#leanpub-auto-beanfactory)
** [SugarBean](#chap02.xhtml#leanpub-auto-sugarbean)
** [for beans](Searching)(#chap02.xhtml#leanpub-auto-searching-for-beans)
** [fields](Accessing)(#chap02.xhtml#leanpub-auto-accessing-fields)
** [beans](Related)(#chap02.xhtml#leanpub-auto-related-beans)
* [class="section-number">4. </span>Vardefs](<span)(#chap03.xhtml#vardefs-chapter)
** [are Vardefs](What)(#chap03.xhtml#leanpub-auto-what-are-vardefs)
** [Vardefs](Defining)(#chap03.xhtml#leanpub-auto-defining-vardefs)
* [class="section-number">5. </span>Views](<span)(#chap04.xhtml#leanpub-auto-views)
** [Location](#chap04.xhtml#leanpub-auto-location)
** [Customising](#chap04.xhtml#leanpub-auto-customising)
* [class="section-number">6. </span>Metadata](<span)(#chap05.xhtml#metadata-chapter)
** [Intro](#chap05.xhtml#leanpub-auto-intro)
** [Location](#chap05.xhtml#leanpub-auto-location-1)
** [Customising](#chap05.xhtml#leanpub-auto-customising-1)
** [metadata](Different)(#chap05.xhtml#leanpub-auto-different-metadata)
* [class="section-number">7. </span>Controllers](<span)(#chap06.xhtml#leanpub-auto-controllers)
** [controllers](Customising)(#chap06.xhtml#leanpub-auto-customising-controllers)
* [class="section-number">8. </span>Entry Points](<span)(#chap07.xhtml#entry-point-chapter)
** [an entry point](Creating)(#chap07.xhtml#leanpub-auto-creating-an-entry-point)
* [class="section-number">9. </span>Language Strings](<span)(#chap08.xhtml#language-chapter)
** [Strings](Module)(#chap08.xhtml#leanpub-auto-module-strings)
** [Strings](Application)(#chap08.xhtml#leanpub-auto-application-strings)
** [List Strings](Application)(#chap08.xhtml#leanpub-auto-application-list-strings)
** [and when to customise](Why)(#chap08.xhtml#leanpub-auto-why-and-when-to-customise)
** [Usage](#chap08.xhtml#leanpub-auto-usage)
* [class="section-number">10. </span>Config](<span)(#chap09.xhtml#config-chapter)
** [config files](The)(#chap09.xhtml#leanpub-auto-the-config-files)
** [config options](Using)(#chap09.xhtml#leanpub-auto-using-config-options)
* [class="section-number">11. </span>Logging](<span)(#chap10.xhtml#logging-chapter)
** [messages](Logging)(#chap10.xhtml#leanpub-auto-logging-messages)
** [output](Logging)(#chap10.xhtml#leanpub-auto-logging-output)
** [levels](Log)(#chap10.xhtml#leanpub-auto-log-levels)
* [class="section-number">12. </span>Logic Hooks](<span)(#chap11.xhtml#logic-hooks-chapter)
** [Intro](#chap11.xhtml#leanpub-auto-intro-1)
** [Types](#chap11.xhtml#leanpub-auto-types)
** [Hooks](Application)(#chap11.xhtml#leanpub-auto-application-hooks)
** [Hooks](User)(#chap11.xhtml#leanpub-auto-user-hooks)
** [Hooks](Module)(#chap11.xhtml#leanpub-auto-module-hooks)
** [Queue Hooks](Job)(#chap11.xhtml#leanpub-auto-job-queue-hooks)
** [Implementing](#chap11.xhtml#leanpub-auto-implementing)
** [Tips](#chap11.xhtml#leanpub-auto-tips)
* [class="section-number">13. </span>Scheduled Tasks](<span)(#chap12.xhtml#scheduled-tasks-chapter)
** [Intro](#chap12.xhtml#leanpub-auto-intro-2)
** [Scheduler](#chap12.xhtml#leanpub-auto-scheduler)
** [Queue](Job)(#chap12.xhtml#leanpub-auto-job-queue)
** [Debugging](#chap12.xhtml#leanpub-auto-debugging)
* [class="section-number">14. </span>Extension Framework](<span)(#chap13.xhtml#extensions-chapter)
** [Introduction](#chap13.xhtml#leanpub-auto-introduction-1)
** [Extensions](Standard)(#chap13.xhtml#leanpub-auto-standard-extensions)
** [Extensions](Custom)(#chap13.xhtml#leanpub-auto-custom-extensions)
* [class="section-number">15. </span>Module Installer](<span)(#chap14.xhtml#module-installer-chapter)
** [manifest.php](#chap14.xhtml#leanpub-auto-manifestphp)
** [Types](#chap14.xhtml#leanpub-auto-types-1)
* [class="section-number">16. </span>API](<span)(#chap15.xhtml#leanpub-auto-api)
** [the API](Using)(#chap15.xhtml#leanpub-auto-using-the-api)
** [custom API methods](Adding)(#chap15.xhtml#leanpub-auto-adding-custom-api-methods)
* [class="section-number">17. </span>Best Practices](<span)(#chap16.xhtml#leanpub-auto-best-practices)
** [instances](Development)(#chap16.xhtml#leanpub-auto-development-instances)
** [control](Version)(#chap16.xhtml#leanpub-auto-version-control)
** [Backup](#chap16.xhtml#leanpub-auto-backup)
** [upgrade safe](Be)(#chap16.xhtml#leanpub-auto-be-upgrade-safe)
** [appropriate log levels](Use)(#chap16.xhtml#leanpub-auto-use-appropriate-log-levels)
** [running logic hooks](Long)(#chap16.xhtml#leanpub-auto-long-running-logic-hooks)
** [SQL](Minimise)(#chap16.xhtml#leanpub-auto-minimise-sql)
** [Use](SQL)(#chap16.xhtml#leanpub-auto-sql-use)
** [check](Entry)(#chap16.xhtml#leanpub-auto-entry-check)
** [after post](Redirect)(#chap16.xhtml#leanpub-auto-redirect-after-post)
* [class="section-number">18. </span>Performance Tweaks](<span)(#chap17.xhtml#leanpub-auto-performance-tweaks)
** [Server](#chap17.xhtml#leanpub-auto-server)
** [Indexes](#chap17.xhtml#leanpub-auto-indexes)
** [Changes](Config)(#chap17.xhtml#leanpub-auto-config-changes)
* [class="section-number">19. </span>Further Resources](<span)(#chap18.xhtml#leanpub-auto-further-resources)
** [Website](SuiteCRM)(#chap18.xhtml#leanpub-auto-suitecrm-website)
** [SuiteCRM Resources](External)(#chap18.xhtml#leanpub-auto-external-suitecrm-resources)
** [Resources](SugarCRM)(#chap18.xhtml#leanpub-auto-sugarcrm-resources)
** [Links](Technical)(#chap18.xhtml#leanpub-auto-technical-links)
** [Links](Other)(#chap18.xhtml#leanpub-auto-other-links)
* [class="section-number">20. </span>Appendix A - Code Examples](<span)(#chap19.xhtml#appendix-a)
** [Metadata](#chap19.xhtml#leanpub-auto-metadata)
** [Installer](Module)(#chap19.xhtml#leanpub-auto-module-installer)
* [class="section-number">21. </span>Appendix B - API Methods](<span)(#chap20.xhtml#appendix-b)
** [Methods](#chap20.xhtml#leanpub-auto-methods-1)


</div>
