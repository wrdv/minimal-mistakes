---
title: "Changelog"
permalink: /testme/release-notes/
excerpt: "Changelog of TestMe IntelliJ IDEA Plugin released versions"
modified: 2017-03-18T22:00:00+02:00
---
### TestMe Plugin Releases

| Version                                                                                                 | Notes |
| ------------------------------------------------------------------------------------------------------- | ----- |
|1.3.0 | {::nomarkdown}<ul> <li>On test class name collision - popup dialog for renaming generated class name</li> <li>Format generated test according to relevant <i>Code Style Settings</i></li> <li>Default TestMe shortcut key changed to <i>Alt+Shift+Q</i> due to collision with Scala plugin</li> <li>Test params generator: handle varargs types</li> <li>Groovy params generator: pass null for inaccessible type initialized by inline setters</li></ul>{:/nomarkdown}|
| <a href="https://plugins.jetbrains.com/plugin/download?updateId=33171" rel="nofollow">1.2.0</a> | {::nomarkdown}<ul><li>Support testing Groovy classes</li> <li>Identify cyclic object initialization, pass null instead.</li> <li>Improve performance when traversing nested objects.</li> <li>Test parameters initialization - pass null instead of initializing un-accessible types.</li> <li>Groovy test generation: ignore excessive property setters for inline initialization.</li> <li>Bugfix: in Groovy generated tests - wrap non String keys in maps.</li> <li>Parameter initialization: Ignore constructors accepting interfaces when default constructor exists.</li></ul>{:/nomarkdown}|
| <a href="https://plugins.jetbrains.com/plugin/download?pr=idea&updateId=32893" rel="nofollow">1.1.0</a> | Generate Groovy tests - new option in TestMe popup |
| <a href="https://plugins.jetbrains.com/plugin/download?pr=idea&updateId=32688" rel="nofollow">1.0.1</a> | Initialize objects in generic collections |
| <a href="https://plugins.jetbrains.com/plugin/download?pr=idea&updateId=32513" rel="nofollow">1.0.0</a> | {::nomarkdown}<ul><li>Generate Java Tests with JUnit 4 or 5 </li><li>Mock with Mockito</li></ul>{:/nomarkdown} |