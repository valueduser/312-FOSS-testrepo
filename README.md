## Week 2 Assignment: FOSS Survey Results ##

### Project 1: EverPad https://github.com/nvbn/everpad ###
<p> As a Linux user, I am forced to use the web app version of Evernote to take and review class notes, recipes, and articles of interest. While the Evernote rarely discusses developing or future projects, it appears that there are no current plans for a native Linux client. While the Windows version can be run in Wine, there exists a few projects to bring an Evernote client to Linux including one called Everpad. EverPad leverages Evernote's API to allow for the creation, modification and syncing of notes between a Linux machine and the user's Evernote account in the cloud on the official Evernote servers. </p>

<p>Reviewing the commits from both the lead developer, nvbn, and the Everpad community, it appears that the number and frequency of commits has dwindled since their peak in May of 2013.  That said, the developer appears interested in accepting pull requests for bug fixes as recently as June 7th. </p>

<p>As it is a very small project at the moment, EverPad lacks a developer mailing list but does have a small wiki on installing and developing for the project. This wiki includes basic information on the use of the API, installation of the project as well as it's dependencies, and debugging best practices. </p>

<p>The code appears to be written predominantly in Python with clear organization and structure as well as a small test suite. The code follows best practices to ensure good readability but has comparatively few comments within the code making it somewhat difficult but not impossible to follow. The absence of comments provide an opportunity to contribute. Issue tracking is handled via GitHub's built-in bug tracker and has helpful comments from both developers and users discussing errors and bugs.</p>

<p>EverPad is used by a subset of both Evernote and Linux users. Ubuntu, one of the most widely used Linux distros recently released a Long Term Stable version, 14.04, and users of many applications, EverPad included, have been submitting bug-fix requests as a result. 14.04's LTS status means it will have a large install base and will be supported for many years. This means it is critical to the survival of the project that as many bugs with 14.04 are squashed. There are several competing Evernote clients for Linux but none dominate the field as of yet. These facts provide opportunities for contributions and collaboration. Another area where a bug fix could take place would be where EverPad breaks list and sublist markup on note creation. </p>

<p>In summary, EverPad would benefit from bug fixes to ensure its installation base as well as code commenting to encourage additional developer support. As the number of commits have declined in the past months, it is critical developer interest returns for the survival of the project.  </p>

### Project 2: Transdroid https://github.com/erickok/transdroid ###
<p>	Transdroid is a remote torrent client manager for Android. It doesn't store torrents or downloaded files on the phone but can manage the torrent activity for a remote computer or seedbox by means of a friendly GUI. Transdroid has existed since 2009 and has a fairly large user base (Google estimates it is on the order of 10,000 – 50,000) with many users uncounted as only a lite version of the app is available on the Google Play store. Transdroid's code base is also relatively light weight making it an ideal candidate for open source contributions in Java. </p>

<p>The lead developer, erickok, actively encourages contributors to contact him by email or social media to get more information about the contribution process and best practices and licenses the code GPL v3.  The readme of the project contains a brief explanation of the code's structure and a reminder to respect coding standards to aid in merging. The code itself is well commented and organized in a way that improves the reader's understanding of the code. The developer has also listed a number of the libraries used in the project on the main page for easy reference. </p>

<p>Transdroid makes use of the GitHub issue tracker for assigning and evaluating bugs and has a dedicated website for update news,  release notes, and full version apks of the project. The issue tracker has further evidence of a large install base and bugs with the lead developer commenting and answering several of the issues and feature requests. The number of bugs seems proportionate to the size of the code base and the number of reported users of the software. </p>

<p>Transdroid has numerous opportunities to contribute including bug fixes, feature enhancements, and other added functionality. The project is in active development and could benefit from improvements to the developer readme as well as extending features such as torrent search on the full version. One potential bug fix would be to handle issue #68 where items in the GUI remain selected even after refresh events. Another example would be to add support for KitKat's new API for opening files as seen in issue #97. </p>

### Project 3: GIMP (GNU Image Manipulation Program) https://github.com/GNOME/gimp ###
	
<p>	GIMP is a GNU licensed photo editor and drawing tool and acts as one of the flagships of FOSS projects and as an open source alternative to Adobe Photoshop. The GIMP project is used by millions of users around the world and has been one of the most visible free software projects for nearly 18 years. With over 700,000 lines of code as of June  2014, and several new features in development, GIMP has ample opportunities for open source contribution. </p>
<p>With almost 60 active contributors, I wasn't able to assess all of GIMP's code base. That said, what was reviewed was both consistently and appropriately documented. The code reviewed was in C and readable with good use of coding best practices. In terms of developer support, GIMP was head and shoulders above the other reviewed applications, with an IRC channel, mailing list, dedicated developer wiki, an RSS feed of active bugs, BugZilla issue tracking system, a list of general ways developers can contribute to the project, a dedicated developer web-page with instructions on getting started and easily available contact information for involved senior developers. </p>
<p>GIMP has several areas that could use contributor attention. The largest of these areas is bug-squashing. With as many users as GIMP has, bugs are constantly being uncovered with varying levels of bug reproducing documentation with currently 777 total bugs of various levels of urgency.  In addition to that, the GIMP project suggest new contributors debug existing features, clean up or expand documentation, write tutorials, program new features, and localization tasks. One item that stands out is that the devs invite contributors to participate in the UI brainstorm – a task usually relegated to the full-time developer team or left over from the original design group. Finally, there exists a “How to create and submit a patch” - a helpful addition of information regarding best practices of finalizing contributions. </p>
<p>A notable bug found in the BugZilla system for GIMP that would be a candidate for contribution is bug #731390 – an issue related to the XCF file type having a maximum file size of 4Gb.  Unfortunately, the portable version of GIMP doesn't warn or throw an error when this happens.</p>
