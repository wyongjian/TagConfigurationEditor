#Tag Configuration Editor(TCE)
================
### The Tag Configuration Editor (TCE) is an application development utility used to create and edit tag configuration files for use in a machine control application. It is distributed as an executable application and can be accessed from the LabVIEW tools menu. The tag configuration files created by the TCE describe the list of tags used in a HMI and controller of the machine control reference architecture and are used to initialize a number of other components in the application.
 The Tag Configuration Editor was creating using the CEF
================
####*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
================

###Overview:
The Tag Configuration Editor is used during the development phase of a machine control application to create the HMI and controller configuration files that are used during the run-time initialization of several application components. When targeting an HMI, the user may create and edit tags for the Current Value Table (CVT) and the CVT Client Communication (CCC) interface. When targeting a controller, the user may create and edit tags for the CVT and the cRIO I/O Engine (CIE).
 
ore information in [Tag Configuration Editor(TCE)](http://www.ni.com/example/30331/en/)
More information in [Configuration Editor Framework (CEF)](http://www.ni.com/example/51881/en/)


 
###Contribution Workflow:
*For a more complete workflow, view [this set-up guide](https://decibel.ni.com/content/docs/DOC-37416) and [this workflow guide](https://decibel.ni.com/content/docs/DOC-37417).*

1. Fork this repository into your account.
2. Create a branch for your change.
3. Make changes, periodically pulling and merging any updates from the central repository.
4. Push your changes up to your branch in your copy of the repository.
5. Send a pull request to the owner of this primary repository. Follow the contribution guidelines.
 
###Contribution Guidelines:
- Limit the scope of your change as much as possible. Smaller changes are easier to process. Any major changes should be discussed beforehand with the managers of the repository to ensure that it fits within the goals and vision of the project.
- Explain the reason for your change with as much detail as possible. If it is a bugfix, link it to an issue in the issues tracker. If it is an enhancement, consider making an issue in the issue tracker to discuss the enhancement before making it. This ensures that the enhancement will provide value to other users.
- Run through the style guidelines and any available VI analyzer tests to ensure compliance with the general style of the project. Don't go crazy trying to make the code perfect. Do make sure there are no glaring issues.
- Before committing a change, be sure to rebase or merge your code off of the most up-to-date source in the master. This reduces the risk of merge conflicts and makes it that much easier to merge your pull request and that much more likely that the change will be accepted.
- Ensure that all builds are successful with your change in place, after rebasing.
- Ensure that all tests pass with your change in place, after rebasing.
