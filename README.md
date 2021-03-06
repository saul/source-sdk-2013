Saul's Community-driven Source SDK 2013 Repository
==================================================

Introduction
------------
This repository, as well as [others listed on the Valve Developer Wiki](https://developer.valvesoftware.com/wiki/Source_SDK_2013_community_repos), contains fixes and features that have yet to be, or were refused, merging into [Valve's official repository](https://github.com/ValveSoftware/source-sdk-2013).

Pull requests or code change suggestions on the official repository may be refused for a number of reasons. [Joe Ludwig](https://github.com/JoeLudwig) (one of the maintainers of Valve's repo) has stated in numerous issues:

> The [ValveSoftware/source-sdk-2013](https://github.com/ValveSoftware/source-sdk-2013) repository is a view of the state of the Orange Box source code on Valve's internal servers. For changes that don't have to do with the deployment of the SDK itself, we suggest that you propose this pull request to one of the community-maintained repositories _[such as this one]_

In this repository, I shall personally merge pull requests which fix bugs or add worthwhile features (i.e., do not bloat).

New features/bug fixes
----------------------
In reverse chronological order:

 *  2013/08/05, __Bug fix__: [Custom URL handlers for the vgui::HTML panel now pass the URL and protocol](https://github.com/saul/source-sdk-2013/issues/3)

    Awaiting Valve response on pull request. Added in commit [c6ad567](https://github.com/saul/source-sdk-2013/commit/c6ad5673281f1aacb3152c60cc61b8589733227d)

 *  2013/08/05, __Bug fix__: [VBSP now checks all search path for FGD files when using func_instance](https://github.com/saul/source-sdk-2013/issues/3)

    Awaiting Valve response on pull request. Added in commit [c6ad567](https://github.com/saul/source-sdk-2013/commit/c6ad5673281f1aacb3152c60cc61b8589733227d)

 *  2013/08/05, __New feature__: [Added auto-complete to "give" ConCommand](https://github.com/ValveSoftware/source-sdk-2013/pull/64)
   
    Valve rejected pull request. Added in commit [19da23d](https://github.com/saul/source-sdk-2013/commit/19da23d)
    
    
 *  2013/08/05, __New feature__: [Print chat messages to console in color](https://github.com/ValveSoftware/source-sdk-2013/pull/63)
   
    Valve rejected pull request. Added in commit [45b370b](https://github.com/saul/source-sdk-2013/commit/45b370b)
