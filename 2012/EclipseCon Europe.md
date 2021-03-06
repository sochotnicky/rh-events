# EclipseCon Europe
## Location: Ludwigsburg, Germany


## Tycho adoption: Lessons learned, tips and tricks from the 1st line of front
### Name: Krzysztof Daniel and Mickael Istria
### Time: October 24, 2012 10:30 - 11:30 CEST

Common Build Infrastracture (CBI) is an landscape-changing initiative to make builds easy for everyone. The technologies that are used in that build system are relatively young in the Eclipse environment, however, they'd been already adopted in a number of not-only-eclipse projects.

Eclipse Platform to Maven/Tycho conversion is the most difficult example of adoption, mostly due to the fact that its build system was created in ancient days of Eclipse creation, and it hardly can be mapped to current maven concepts.

In this talk, Mickael and Krzysztof will present their experiences that they had gathered while working on CBI and JBoss Tools (and a few others) build projects,
which include:

* the general concept of Tycho/Maven
* common signs that you'll have problems migrating to Tycho
* incompatibilities between Tycho and PDEBuild and how to deal with them
* common problems

For more information, including speaker bios, visit http://www.eclipsecon.org/europe2012/sessions/tycho-adoption-hints-based-examples-mylyn-and-platform-cbi


## OSGi and Cloud Computing
### Name: David Bosschaert
### Time: October 24, 2012 13:30 - 14:00 CEST

OSGi and Cloud Computing go very well together. Previously held OSGi Cloud Workshops have clearly shown that many people are using or planning to use OSGi in the Cloud. This session focuses on a demonstration of how OSGi can really help in a Cloud environment, taking advantage of OSGi's dynamism and services model.

The demo whill show how you can use OSGi to dynamically deploy an application in the cloud and use OSGi cloud discovery to hook the various entities together, each one potentially running in a different cloud node. The demo shows concepts such as dynamic provisioning, dynamic discovery, dynamic scaling and dynamic failover all from the OSGi programming model. I will also talk about cloud-related specification work relating to what is being demonstrated that is currently an active topic in the OSGi Enterprise Expert Group.

For more information, including speaker bio, visit http://www.eclipsecon.org/europe2012/sessions/osgi-and-cloud-computing


## A journey with Target Platforms
### Name: Mickael Istria
### Time: October 24, 2012 17:00 - 17:30 CEST

Target Platform are a powerful concept for Eclipse Plugin/RCP development. They are basically specification of how to resolve dependencies. But behind this very technical definition, target-platforms are a very elegant way to resolve some common use-cases at both dev-time and build-time. In this presentation, Mickael will highlight how you can profit from target-platforms by reminding concepts, typical use-cases and sharing some tips & tricks to stop fighting with dependency management, and turn it into your dedicated friend.

For more information, including speaker bio, visit http://www.eclipsecon.org/europe2012/sessions/journey-target-platforms


## Forging a Bond Between Eclipse and the Command-line
### Name: Koen Aers
### Time: October 25, 2012 11:30 - 12:00 CEST

It is common knowledge that some developers swear by using command-line tools to do their job. Typing quickly, the use of tabbed completion and running scripts are key ingredients to their productivity. Nevertheless a fancy IDE such as Eclipse also attracts many developers. These love to rely on key benefits such as incremental building, form based editing, outline views and navigating the workspace. Well, we have some excellent news for developers that want the best of both worlds.

JBoss Forge is a command-line driven open source tool that enables users to adopt an incremental approach to their daily Java development. It lets you take an existing Java project and safely add in new functionality. Whether you want to set up JSF, use persistence or create REST endpoints, it all becomes a real breeze. Forge was created with extensibility in mind and is completely technology agnostic.

The good news that was mentioned above is that a number of Eclipse plugins bring this power right to the heart of your favorite IDE. Just think about a command-line tool nicely integrated in an Eclipse view. Now imagine that the commmands issued at this command-line tool are immediately reflected with changes and useful feedback in your workbench... Doesn't that sound cool?

In this talk, Koen will show this powerful integration between IDE and command-line at work. He will highlight many of the benefits as well as some of the more advanced possibilities of this approach. Come to this talk if you want to know how to take advantage of all this power.

For more information, including speaker bio, visit http://www.eclipsecon.org/europe2012/sessions/forging-bond-between-eclipse-and-command-line


## Kick your Java EE development up a notch with m2e-wtp
### Name: Fred Bricon
### Time: October 25, 2012 11:30 - 12:00 CEST

The m2e-wtp project is a new project incubating at the Eclipse foundation. Built upon the popular m2eclipse-wtp plugin, it aims at providing a tight integration between the Eclipse’s Web Tools Platform and m2e, the Maven Integration plugin for Eclipse.

In this heavily demo-focused presentation, Fred will show you how you can bring powerful Maven capabilities to your legacy Eclipse Java EE applications, detailing 3 features m2e-wtp adds over your typical WTP installation:

* Convert your Eclipse projects to Maven : taking advantage of the new Eclipse to Maven Conversion API added in m2e 1.1, m2e-wtp translates your WTP project settings (Web, EJB, EAR ...) to their equivalent maven plugin configurations in a jiffy.
* web resource filtering : lets you dynamically change the content of your web resources (web pages, css files, deployment descriptors...) using placeholders much like a templating engine. This allows you, for instance, to enable or disable debug parameters in your web.xml depending on some specific Maven profiles.
* war overlays : ever needed to share the same web resources (images, css ...) across different web applications? The Maven war overlay mechanism allows you to define these common files in one location (be it a workspace project or a war archive) and let other web applications consume them without the need to duplicate them into their source control system

For more information, including speaker bio, visit http://www.eclipsecon.org/europe2012/sessions/kick-your-java-ee-development-notch-m2e-wtp
