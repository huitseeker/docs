Changelog
=========

2.1 (master) - codename Helium 
------------------------------

2.1.0-rc01 (unreleased)
.......................


M2 (released: 2012-07-31)
.........................

* `Implicit hyperlinking`__ - `#1001002`_, `#1000209`
* `Infer Type of Structured Selection`__ - `#3214`_
* Missing Scala library in run classpath - `#1000786`_, `#1000919`_, `#1001022`_
* Provide reusable sdt.core.tests bundle - `#1001080`_
* Problem deleting files on Windows - `#1000909`_, `#1000923`_
* Removed code generation groups from editor's context menu - `#1000972`_
* Correctly expose Scala @throw annotation to Java - `#1000707`_, `#1000800`_, `#1001005`_
* Support nested projects (Maven style) - `#1000881`_, `#1000734`_, `#1000621`_
* Fixed crash in tooltip launch button - `#1000951`_
* Made ``Run As Scala Application`` more robust - `#1000911`_, `#1001096`_
* Use the configured JDK when instantiating the presentation compiler. - `#1000820`_
* Warn the user if JDT Weaving is disabled - `#1001104`_
* Fixed NullPointerException occurring when using the ``New Application`` wizard - `#1000797`_, `#1001115`_
* Fixed Assertion exception: ``Marker property value too long`` - `#1001107`_
* Several improvements for ``Organize Imports`` refactoring - `#1000846`_, `#1000857`_, `#1001004`_, `#1001008`_, `#1001085`_, `#1001122`_, `#1001124`_, `#1001126`_, `#1001127`_, `#1001155`_, `#1001160`_, `#1001028`_, `#1001073`_
* Several improvements for ``Rename`` refactoring - `#1000884`_, `#1000959`_, `#1001031`_, `#1001049`_, `#1001081`_, `#1001117`_, `#1001118`_, `#1001148`_, `#1001150`_, `#1001177`_, `#1000981`_, `#1001059`_
* Several improvements in ``Move`` refactoring - `#1001079`_, `#1001123`_, `#1001147`_, `#1000980`_
* Assignment operators and extract local refactoring don't mix wel - `#1001110`_
* Fixed ``ConcurrentModificationException`` when starting Eclipse - `#1000941`_
* Added ``scala-actors`` jar in Scala 2.10 library and made the class path container resilient to non-found items (``scala-dbc`` is gone in 2.10) - `#1000979`_
* Updated syntax coloring for Scala 2.10, i.e., macro keyword and string interpolation literals - `#1001012`_
* Fixed *mark occurrences* highlights type aliases in Scala 2.10 - `#1001069`_
* Extract Method messes up anonymous class definition - `#1001111`_
* Redirection of stdout and std err to the log file should be optional - `#1001133`_
* Initial support for Find References - `#1001146`_, `#1001167`_, `#1000063`_, `#1000067`_, `#1001084`_, `#1001135`_
* Added support for parameter names in method completion - `#1000534`_
* Semantic highlighting should have its own background job - `#1001016`_, `#1000943`_
* `Create Source generation actions`__ - `#1001018`_
* Add an option to stop building dependent projects when there are compilation errors - `#1000893`_
* Quickfix to expand case-class bindings in pattern-matching - `#1000982`_
* Add IIndexedValue support to split large arrays in Variables view - `#1001009`_
* Editor improvements: surround selection with ``{ (or (,",[)`` - `#1001010`_, `#1001034`_
* sbt builder is too restrictive when looking for the scala library jar - `#1000729`_, `#1001027`_, `#1000987`_
* Improve Scala Debugger to no more rely of an launched JDT debug session - `#1001130`_
* Could not find or load main class ``scala.tools.nsc.MainInterpreter`` - `#1001157`_
* Enable using the Scala debugger for applications with 'Equinox weaving' - `#1001158`_
* Add import not working correctly in Scala 2.10 - `#1001161`_
* Abstract val/var not shown in the outline - `#1001173`_
* Missing implementation of abstract val/var not reported in Java class - `#1001174`_
* Exception when deleting a Scala project - `#1001058`_
* Java debug broken when Scala debug enabled - `#1000995`_
* False error markers set in editor window - `#1000976`_

__ http://scala-ide.org/docs/helium/features/implicit-hyperlinking/index.html
.. _#1001002: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001002
.. _#1000209: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000209
__ http://scala-ide.org/docs/helium/features/show-type.html
.. _#3214: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/3214
.. _#1000972: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000972
.. _#1000800: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000800
.. _#1000881: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000881
.. _#1000707: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000707
.. _#1000734: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000734
.. _#1000786: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000786
.. _#1000621: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000621
.. _#1000951: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000951
.. _#1000909: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000909
.. _#1000911: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000911
.. _#1001096: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001096
.. _#1000919: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000919
.. _#1000923: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000923
.. _#1000820: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000820
.. _#1001005: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001005
.. _#1001022: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001022
.. _#1001080: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001080
.. _#1001104: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001104
.. _#1001108: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001108
.. _#1000797: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000797
.. _#1001115: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001115
.. _#1001107: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001107
.. _#1000846: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000846
.. _#1000857: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000857
.. _#1001004: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001004
.. _#1001008: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001008
.. _#1001085: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001085
.. _#1001122: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001122
.. _#1001124: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001124
.. _#1001126: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001126
.. _#1001127: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001127
.. _#1001155: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001155
.. _#1001160: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001160
.. _#1001028: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001028
.. _#1001073: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001073
.. _#1000884: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000884
.. _#1000959: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000959
.. _#1001031: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001031
.. _#1001049: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001049
.. _#1001081: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001081
.. _#1001117: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001117
.. _#1001118: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001118
.. _#1001148: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001148
.. _#1001150: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001150
.. _#1001177: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001177
.. _#1000981: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000981
.. _#1001059: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001059
.. _#1001079: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001079
.. _#1001123: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001123
.. _#1001147: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001147
.. _#1000980: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000980
.. _#1001110: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001110
.. _#1000941: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000941
.. _#1000979: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000979
.. _#1001012: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001012
.. _#1001069: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001069
.. _#1001111: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001111
.. _#1001133: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001133
.. _#1001146: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001146
.. _#1001167: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001167
.. _#1000063: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000063
.. _#1000067: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000067
.. _#1001084: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001084
.. _#1001135: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001135
.. _#1000534: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000534
.. _#1001016: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001016
.. _#1000943: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000943
__ http://scala-ide.org/docs/helium/features/source-generators/index.html
.. _#1001018: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001018
.. _#1000893: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000893
.. _#1000982: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000982
.. _#1001009: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001009
.. _#1001010: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001010
.. _#1001034: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001034
.. _#1000729: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000729
.. _#1001027: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001027
.. _#1000987: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000987
.. _#1001130: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001130
.. _#1001157: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001157
.. _#1001158: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001158
.. _#1001161: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001161
.. _#1001173: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001173
.. _#1001174: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001174
.. _#1001058: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1001058
.. _#1000995: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000995
.. _#1000976: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000976


M1 (released: 2012-04-13)
.........................

* Bundled with Scala 2.9.2.
* Linked refactoring actions to quickfix proposals. `pr-86`_
* Fixed incomplete package problem with auto-import on code completion. `#1000855`_
* Fixed 'invalid thread access' when creating first Java file. `#1000738`_
* Improve reference of selected elements. `pr-76`_
* Semantic highlighting support. `#1000591`_
* Fixed open declaration from context menu. `#1000920`_
* Improved closing braces management. `#1000926`_
* In development Scala Debugger. `#1000864`_
* Removed some duplicated errors. `#1000735`_
* Propagate fine-grained build information to downstream projects. `#1000894`_
* Added memory leaks test.
* Fixed problem linked to using compiler plugins, in particular the continuation plugin. `#1000901`_, `#1000908`_, `#1000917`_
* Rewriting of the REPL integration. `#1000883`_
* Move Class, Trait and Object refactoring. `#1000422`_, `#1000839`_, `#1000842`_
* Improved logging infrastructure. `#1000880`_
* Extracted external libraries from source code.
* Improved 'package.scala' support. `#1000859`_
* Implicit highlighting support. `#1000628`_
* Eclipse 3.7 Indigo support. `#1000852`_
* Fixed occasional problem with auto-import on code completion. `#1000854`_
* Improved UI for Scala completion (context information and caret position).

.. _#1000422: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000422
.. _#1000591: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000591
.. _#1000628: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000628
.. _#1000735: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000735
.. _#1000839: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000839
.. _#1000842: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000842
.. _#1000852: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000852
.. _#1000855: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000855
.. _#1000859: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000859
.. _#1000864: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000864
.. _#1000880: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000880
.. _#1000883: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000883
.. _pr-76: https://github.com/scala-ide/scala-ide/pull/76
.. _pr-86: https://github.com/scala-ide/scala-ide/pull/86

2.0.2 (release/scala-ide-2.0.x)
-------------------------------

2.0.2-final (released: 2012-07-12)
..................................

* (no changes between RC3 and the final release)


2.0.2-rc03 (released: 2012-07-04)
.................................

* Fixed NullPointerException occurring when using the ``New Application`` wizard - `#1000797`_, `#1001115`_
* Fixed Assertion exception: ``Marker property value too long`` - `#1001107`_

2.0.2-rc02 (released: 2012-06-28)
.................................

* Fixed issue with ``Run As Scala Application`` - `#1001096`_
* Warn the user if JDT Weaving is disabled - `#1001104`_

2.0.2-rc01 (released: 2012-06-22)
.................................

* Missing Scala library in run classpath - `#1000786`_, `#1000919`_, `#1001022`_
* Provide reusable sdt.core.tests bundle - `#1001080`_
* Problem deleting files on Windows - `#1000909`_, `#1000923`_
* Removed code generation groups from editor's context menu - `#1000972`_
* Correctly expose Scala @throw annotation to Java - `#1000707`_, `#1000800`_, `#1001005`_
* Support nested projects (Maven style) - `#1000881`_, `#1000734`_, `#1000621`_
* Fixed crash in tooltip launch button - `#1000951`_
* Made ``Run As Scala Application`` more robust - `#1000911`_
* Use the configured JDK when instantiating the presentation compiler. - `#1000820`_


2.0.1 (release/scala-ide-2.0.x)
-------------------------------

2.0.1-final (released: 2012-04-30)
..................................

* Bundled with Scala 2.9.2.

2.0.1-rc03 (released: 2012-04-05)
.................................

* Bundled with Scala 2.9.2 RC3.

2.0.1-rc02 (released: 2012-03-27)
.................................

* Bundled with Scala 2.9.2 RC2.

2.0.1-rc01 (released: 2012-03-22)
.................................

* Fixed 'invalid thread access' when creating first Java file. `#1000738`_
* Fixed open declaration from context menu. `#1000920`_
* Improved closing braces management. `#1000926`_
* Propagate fine-grained build information to downstream projects `#1000894`_
* Fixed occasional problem with auto-import on code completion. `#1000854`_
* Fixed problem linked to using compiler plugins, in particular the continuation plugin. `#1000901`_, `#1000908`_, `#1000917`_
* Bundled with Scala 2.9.2 RC1.

.. _#1000738: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000738
.. _#1000854: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000854
.. _#1000894: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000894
.. _#1000901: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000901
.. _#1000908: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000908
.. _#1000917: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000917
.. _#1000920: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000920
.. _#1000926: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000926

2.0.0 (release/scala-ide-2.0.0)
-------------------------------

2.0.0-final (released: 2011-12-21)
..................................

* Scala IDE plugin now signed (no more warning dialog displayed when installing the Scala IDE). `#1000719`_

.. _#1000719: http://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000719

2.0.0-rc04 (released: 2011-12-13)
....................................

* Scala IDE now again compatible with Groovy IDE. `#1000798`_

.. _#1000798: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000798 

2.0.0-rc03 (released: 2011-12-09)
....................................

* compatible with Spring IDE. `#1000780`_
* Incremental compilation of Java files that depend on Scala files is now correctly handled. `#1000607`_
* Corrected completion suggestions for overloaded methods. `#1000654`_
* Make Scala Interpreter view more visible. `#1000791`_
* Corrected unnecessary warning generated at start-up (*Couldn't find a match for 2.9.2.r26031-b20111119033233 in . Using default.*). `#1000793`_

.. _#1000607: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000607
.. _#1000654: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000654
.. _#1000780: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000780
.. _#1000791: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000791
.. _#1000793: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000793

2.0.0-rc02 (released: 2011-11-24)
....................................

* Better error reporting. `#1000757`_
* Fixed crash in the Eclipse Outline. `#1000748`_
* *protected* Scala entities are now exposed to Java code as *public* (this matches Scala compiler behavior). `#1000751`_
* Scan project's dependencies only for Scala projects. `#1000643`_
* Better error handling for missing class files in dependent projects.

.. _#1000643: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000643
.. _#1000748: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000748
.. _#1000751: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000751
.. _#1000757: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000757

2.0.0-rc01 (released: 2011-11-09)
....................................

* Updated the Classpath Validator to play nice with Maven project. `#1000631`_, `#1000728`_
* TODO comments are now displayed in Eclipse Task section. `#1000634`_
* Fixed an important source of instability affecting Windows Eclipse users (causing the following exception to be reported: *java.lang.IllegalArgumentException: Path for project must have only one segment.*). `#1000715`_, `#1000660`_
* Improved the Run Selection Interpreter (a project picker is now displayed when no project is selected). `#1000480`_
* The JDK selected in the project's classpath is now honored. `#1000406`_
* Resource files are copied to the output directory. `#1000636`_
* Braces and parenthesis are now (correctly) automatically matched in the editor. `#1000688`_
* Better support for dependent projects in the presentation compiler, leading to less spurious errors. `#1000699`_, `#1000645`_
* Completion support for inherited trait members in Java sources. `#1000412`_

.. _#1000406: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000406
.. _#1000412: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000412
.. _#1000480: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000480
.. _#1000634: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000634
.. _#1000631: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000631
.. _#1000636: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000636
.. _#1000645: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000645
.. _#1000660: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000660
.. _#1000688: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000688
.. _#1000699: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000699
.. _#1000715: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000715
.. _#1000728: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000728

2.0.0-beta12 (released: 2011-10-31)
......................................

* Hyperlinking on definitions between dependent projects works correctly.
* For mixed Scala/Java project, allow to change sources' compilation order (i.e., first Java and then Scala, or the other way around).
* Improved interoperability of mixed Scala/Java. `#1000652`_, `#1000670`_, `#1000678`_
* Fixed a deadlock when the presentation compiler was awaken during builds.
* Presentation compiler is notified of changes in dependent projects (no spurious errors after rebuild).
* Fixed issue in the presentation compiler that caused implicit conversions not to be applied. `#1000647`_
* Added classpath validator. An error is reported if the Scala library is missing or the version is wrong. `#1000631`_
* Improved refactoring (better support for organize/add imports). [by Mirko Stocker]
* Wizard for creating Scala Application uses now trait _App_ instead of the deprecated _Application_ trait. [by Matt Russel]

.. _#1000631: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000631
.. _#1000647: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000647
.. _#1000652: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000652
.. _#1000670: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000670
.. _#1000678: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000678

2.0.0-beta11 (released: 2011-10-03)
......................................

* Added completion proposals for any type from the classpath in the Scala editor, with automatic imports.
* Several fixes to improve interoperability of mixed Scala/Java project. `#1000594`_, `#1000568`_, `#1000524`_, `#1000586`_
* Fixes in the SBT builder regarding passing compiler options, continuations support and classpath resolution. `#1000605`_, `#1000617`_
* SBT builder is the default builder.
* Fixed Toggle Comment and Indentation for multi line string. `#1000618`_
* Fixed problem when trying to put line breakpoint in object private method. `#3271`_

.. _#3271: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/3271
.. _#1000524: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000524
.. _#1000568: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000568
.. _#1000586: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000586
.. _#1000594: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000594
.. _#1000605: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000605
.. _#1000617: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000617
.. _#1000618: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000618

2.0.0-beta10 (released: 2011-09-13)
......................................

* new SBT-based builder with inter-project dependencies. The default builder remains 'refined', but you can enable the SBT builder in Eclipse -> Preferences -> Scala  -> Compiler -> Build manager.
* better integration of mixed Scala/Java project (no more spurious errors when Java classes call Scala classes that contain annotations).
* new field in Compiler preferences for additional command line parameters, cleanup of compiler options.
* new "Show Inferred Semicolons" feature: :ref:`typingviewing_show-inferred-semicolons`.
* syntax colouring for new REPL view.
* stop inappropriate Java save actions firing on Scala source. `#1534`_
* corrected cursor's positioning after asking completion.
* better navigation and occurrences highlighting when clicking on ``import`` clauses.
* Error Log is not in the default Scala perspective anymore.
* fixed Toggle Comment action which was incorrectly commenting an additional line. `#1000462`_

.. _#1534: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1534 
.. _#1000462: https://scala-ide-portfolio.assembla.com/spaces/scala-ide/tickets/1000462

2.0.0-beta09 (released: 2011-07-21)
......................................

* better breakpoint support (fixes errors when setting breakpoints in traits coming from external libraries).
* better completions (works in many more situations, such as partially typed method names).
* better diagnostics ('no completions at all syndrome') and re-setting the Java completions flag.
* better integration with Eclipse. When clicking a Scala classfile on a stack trace report, the Scala file editor will be correctly opened and functionalities such as navigation and setting breakpoint just work.
* moved Scala completions to its own category (instead of Java Proposals). This eliminates a source of incompatibilities with the Mylyn plugin. Now you can enable/disable Scala completions from Preferences, Java/Editor/ContentAssist/Advanced Scala Completions and Scala Completions (Java sources).
* added package object wizard.

2.0.0-beta08 (released: 2011-07-12)
......................................

* fixed large memory leak in mark occurrences.
* new Run Selection REPL: edit window for commands (with history). Try it by pressing Ctrl-Shift-X inside a Scala editor to run the selected expression (or the current line). :ref:`Read more <scalainterpreter_scala-interpreter>`.
* JUnit runner finds tests in Scala files reliably (even when files are not open).
* Fixed errors shown in Java sources coming from the Scala compiler.
* Fixed crash in Java completion for Scala classes in the default (empty) package.

2.0.0-beta6 
...............

* Improved stability (correct use of 'ask' calls)
* Removed dummy features used for upgrading from the old 2.7 IDE.
* Better description of the JDT weaving feature when installing it.
* Downgraded the JDT weaving plugin to the latest released version. We were using the development repository, and that caused conflicts on installation, when the user had AspectJ (or was using STS) installed -- requiring the user to unselect the JDT weaving plugin from our update site. Now the versions are the same, and no conflict is reported.
* Organize Imports improvements: various configuration options and support for adding missing imports.
* Eclipse 3.7.0 (Indigo) compatibility
* New REPL view: Launch by selecting text and pressing Ctrl+Shift+X (Cmd+Shift+X on the Mac). 
    * A different key combination can be set by going to General -> Keys, and redefining the key binding for "Send Selection to REPL." 
    * The interpreter can be stopped and restarted, with optional replay. 
    * NOTE: the colon commands (e.g. ":implicits") that work in the terminal REPL do not yet work in this REPL view, but this will be fixed for the next beta.

2.0.0-beta2
..............

* Fixes various crashes in the structure builder, leading to un-editable files in Eclipse.
* Correctly saves preferences for the diagnostics window.
* Correctly show bean getters/setters in mixed Java/Scala projects.
* Performance improvements in structured selection.
* New formatter preference window, with preview.
* Format selection only.
* Better memory usage when closing projects.
* Allow compiler plugins in the presentation compiler.
* other bug fixes.

The full list of fixed tickets: `2.0-beta2 fixed tickets`__

__ https://scala-ide-portfolio.assembla.com/spaces/ae55a-oWSr36hpeJe5avMc/tickets/report/u33405

1.x (backport releases)
-------------------------

1.0.0.20110226-M01
.....................

* fix    : reduce freeze in editor on typing
* add    : display of implicits (result of GSoC 2010)
* add    : several tuning preferences to tune editor/plugin behavior and diseable some features
* add    : support for Eclipse Galileo (3.5) and Helios (3.6)
* add    : support of scala-2.8.1
* add    : some templates (eg : specs)
* update : Formatting Scalariform has gone from 0.0.4 to 0.0.9
* update : better Mark Occurrences
* update : better Quick Fix Imports
* update : better Structured Selections
* update : better code completion (don't forgot to enable Java Completion)
* update : better hyperlink code navigation
* delete : support of scala-2.8.0

1.0.0.20100804
..................

* Refactoring Support
* Formatting
* Mark Occurrences
* Structured Selections
* XML Syntax Highlighting
* Code Templates
* Quick Fix Imports
* new build system based on tycho, to ease contribution

see `news`__

__ http://www.scala-ide.org/2010/08/not-a-release-but-new-and-noteworthy-even-so/)
