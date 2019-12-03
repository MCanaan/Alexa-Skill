# Alexa-Skill
We imported the Jar Libraries and they are added to Referenced Libraries but i can't see them here.

We added the Dependencies to the pom.xml but we still get the Following Errors.


[INFO] Building AlexaSkill 1.0

[INFO] --------------------------------[ war ]---------------------------------

[WARNING] The POM for clojure-complete:clojure-complete:jar:0.2.3 is missing, no dependency information available

[WARNING] The POM for yandex-translate:yandex-translate:jar:0.1.0 is missing, no dependency information available

[INFO] ------------------------------------------------------------------------

[INFO] BUILD FAILURE

[INFO] ------------------------------------------------------------------------

[INFO] Total time:  0.370 s

[INFO] Finished at: 2019-12-04T00:32:03+01:00

[INFO] ------------------------------------------------------------------------

[ERROR] Failed to execute goal on project de.unidue.ltl.ourAlexaExample: Could not resolve dependencies for project de.unidue.ltl:de.unidue.ltl.ourAlexaExample:war:1.0: The following artifacts could not be resolved: clojure-complete:clojure-complete:jar:0.2.3, yandex-translate:yandex-translate:jar:0.1.0: Failure to find clojure-complete:clojure-complete:jar:0.2.3 in https://repo.maven.apache.org/maven2 was cached in the local repository, resolution will not be reattempted until the update interval of central has elapsed or updates are forced -> [Help 1]

[ERROR] 
