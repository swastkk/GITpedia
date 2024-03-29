What is Version Control?
=======
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

----

Version control software is an essential part of the every-day of the modern software team's professional practices. Individual software developers who are accustomed to working with a capable version control system in their teams typically recognize the incredible value version control also gives them even on small solo projects. Once accustomed to the powerful benefits of version control systems, many developers wouldn't consider working without it even for non-software projects.

.. _version_control_software_tools:

Version Control Software Tools
---

GIT
^^^

  Git is one of the best version control tools that is available in the present market.

Features
--------

  :: 

     - Provides strong support for non-linear development.
     - Distributed repository model.
     - Compatible with existing systems and protocols like HTTP, FTP, ssh.
     - Capable of efficiently handling small to large sized projects.
     - Cryptographic authentication of history.
     - Pluggable merge strategies.
     - Toolkit-based design.
     - Periodic explicit object packing.
     - Garbage accumulates until collected.
  

Pros
----
  ::
    
    - Super-fast and efficient performance.
    - Cross-platform
    - Code changes can be very easily and clearly tracked.
    - Easily maintainable and robust.
    - Offers an amazing command line utility known as git bash.
    - Also offers GIT GUI where you can very quickly re-scan, state change, sign off, commit & push the code quickly with just a few clicks.

Cons
----
  ::

    - Complex and bigger history log become difficult to understand.
    - Does not support keyword expansion and timestamp preservation.

CVS
^^^

  It is yet another most popular revision control system. CVS has been the tool of choice for a long time.

Features
--------

  :: 

   - Client-server repository model.
   - Multiple developers might work on the same project parallelly.
   - CVS client will keep the working copy of the file up-to-date and requires manual intervention only when an edit conflict occurs
   - Keeps a historical snapshot of the project.
   - Anonymous read access.
   - ‘Update’ command to keep local copies up to date.
   - Can uphold different branches of a project.
   - Excludes symbolic links to avoid a security risk.
   - Uses delta compression technique for efficient storage. 
  
Pros
----
  ::
    
    - Excellent cross-platform support.
    - Robust and fully-featured command-line client permits powerful scripting
    - Helpful support from vast CVS community
    - allows good web browsing of the source code repository
    - It’s a very old, well known & understood tool.
    - Suits the collaborative nature of the open-source world splendidly.
    
Cons
----
  ::
   
  - No integrity checking for source code repository.
  - Does not support atomic check-outs and commits.
  - Poor support for distributed source control.
  - Does not support signed revisions and merge tracking.

GITLAB
^^^^^

GitLab is one of America's fastest-growing private software companies, posting huge gains in 2022. The company provides a central server that manages Git repositories and is used to simplify the administration tasks of many corporations worldwide. According to Wikipedia, GitLab has over 100,000 users and is used by large, well-known organizations such as IBM, Sony, Goldman Sachs, and NASA.

-----

Best for being used as end-to-end project life cycle with Git-based tools like version control, project management, CI/CD, etc.

Features
----
  ::

    - It supports Git workflows, CI/CD integration, project management.
    - It has over 30 million users & 100 thousand organizations.
    - Single application for the entire DevOps life cycle.

Pros
----
  ::

   - Uses standard Git underneath for version control.
   - Easy to use and learn.
   - Good support (depending on the pricing tiers).

Cons
----
  ::

    - High pricing tags make it less viable for larger teams and organizations.

Apache SubVersion
^^^^

Best for small to mid-sized teams who are looking for basic versioning features.

Features
----
  :: 

    - Open-source version control system.
    - Supports merge tracking and file locking.

Pros
----
  ::

    - Well documented and maintained.
    - Visual Highlighting helps with quick conflict resolution.

Cons
----
  :: 
    - Does not support basic features like Pull requests.
    - Can’t be used as a distributed system.


Mercurial
^^^^^


Best for teams of any size looking to get started with version control of their code.

Features
----
  ::
    - Web-based version control system.
    - Simple branching for hassle-free development.

Pros
----
  ::
    
  - Intuitive interface
  - Good IDE support
  - Easy to learn and use

Cons
----
  ::
    
   - The in-built merging tool can get complicated when there are a lot of merging conflicts.
   - Lack of pagination support for listing commit logs
