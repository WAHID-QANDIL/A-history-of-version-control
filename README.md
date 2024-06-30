# A-history-of-version-control
A history of version control

As you know by now, version control is a system that records changes to a file or set of files over time so that you can access specific versions later. In software development, Version Control Systems (VCS) allows developers to manage changes to their code and track who made each change. But how did this software come about?

Version Control has a long history going back to the 1980s. In fact, version control systems were created before the Internet!

One of the first significant Version Control Systems was the Concurrent Versions System (CVS). It was first developed in 1986 by *Walter F. Tichy at Purdue University and released publicly in 1990*.

CVS stores information about every file in a folder structure, including the name of the file, its location in the folder structure, who last modified it, and when it was last modified. The CVS also stores information about folders, including their names and who created them.

It was popular for many years; however, it has some significant flaws in its design. CVS does not include integrity checks which means your data can become corrupted. When you update or submit changes to the system, if an error occurs, the system accepts the partial or corrupted files. Additionally, the system was designed mainly for text files, not binary files such as images or videos.

The main successor to CVS was Subversion (SVN).

CollabNet developed Subversion in 2000 and solved many of the issues present in CVS. To ensure data integrity, it included integrity checks in its design. It also supported the versioning of binary files better than CVS. Thanks to these improvements, SVN became popular in the open-source community with free hosting being offered for open-source projects by Google and SourceForge.

However, Subversion used a centralized VCS model. This means that all operations have to be done using a centralized server. If the server were down or slow, this would impede development.

In 2005, two new projects were started to develop distributed version control systems; Mercurial and Git. Both projects were created in response to an event involving the Linux kernel development.

Previously, the Linux kernel was using a proprietary VCS known as *BitKeeper*. BitKeeper was one of the first distributed version control systems initially released in 2000. BitKeeper had originally provided a free license to Linus Torvalds to support Linux’s development. However, in 2005, the *license was revoked*. This controversy led to the creation of the Mercurial and Git projects.

Mercurial was developed by *Olivia Mackall*. It is developed as a high-performance distributed VCS. Many platforms offering Subversion hosting began to offer Mercurial hosting too. It became popular as Subversion users found it easy to transition to a Mercurial repository, thanks to the hosting providers and its small learning curve.

Git was developed by *Linus Torvalds* to host the Linux kernel’s source code. Like Mercurial, it is a distributed VCS. Its first public release came in 2007.

Git became popular in the open-source community due to its distributed VCS design and Github offering free Git hosting for open-source projects. Git has since become the selected version control system for many open-source and proprietary software projects.
##https://en.wikipedia.org/wiki/List_of_version-control_software
