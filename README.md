# **Introduction**

You are here to contribute with the `Verified Token Framework (VTF)` protocol? That's great. We really need people like you. Feel welcome and read the following sections in order to know how to submit contributions, ask questions and how to work on something.

To be accepted as a `VTF` contributor you must also be a BTA member. You can join the BTA at https://www.blockchaintokenassociation.org/membership/.

We are all working together to create common standards to help the future of the token ecosystem. By following the guidelines, you show respect to everyone developing and maintaining this open source project. In return, maintainers make their best to assessing submissions, addressing issues and finalising pull requests in a timely manner.

Please make sure you are welcoming and friendly in all of our spaces.

<!--[ADD GUIDE TABLE OF CONTENTS]-->


### Contributions we are looking for

There are many ways to contribute to the `VTF` protocol. Here are some of them:

*   Writing bake-off code
*   Providing test cases
*   Writing tutorials for code submission
*   Improving documentation (such as the Nomenclature)
*   Submitting bug reports
*   Submitting pull requests
*   Submitting feature requests

We make sure contributions are reviewed in a timely manner and code changes are incorporated into the protocol through a merge process.


### Getting in touch

Email: contact@verifiedtokenframework.com
<!--[ADD MAIL LIST AND OTHER CHANNELS]-->


# **Ground Rules**

<!--[ADD CODE OF CONDUCT - IF AVAILABLE]-->


*   Ensure cross-platform compatibility for every code submission (e.g. bake-off, test cases, feature requests). Windows, Mac, Linux.
*   If applicable, ensure cross-blockchain compatibility for code submission. E.g. Ethereum, EOS, NEM etc.
*   Pull requests have passing criteria before deployment to protocol. Make sure PRs meet requirements <!--[example: https://gist.github.com/audreyr/4feef90445b9680475f2 ]-->
*   Code bugs are demonstrable problems in the repository code. Before submitting new issues, use the [`issue search`] to check if the bug is already fixed. If not, provide as much detail as possible along with test cases.
*   Before submitting new feature requests, make sure you idea fits within the scope and aims of an existing code base. Provide as much detail and context as possible on new features.
*   Keep feature version as small and clear as possible. <!--[Standard to add?]-->

# **Your First Code Contribution**


Unsure where to begin contributing to Verified Token Framework? Start by looking at [beginner] and [help-needed] issues in the [`issue tracker`](https://github.com/BlockchainTokenAssociation/Contribution/issues)

**Beginner issues** - these are issues that should allow you to contribute to the repo with a smooth start. These should only require a few lines of code, followed by a couple of test cases.

**Help-needed issues** - these issues give exposure to more complex parts of the protocol than [beginner] issues. They have a bigger scope and should be followed by detailed description.

<!--[ADD PROCESS OR TAG RELATED COMMENT - IF APPLICABLE]-->

First time contributor to open source projects? Check out how to submit your first pull request on this free series http://makeapullrequest.com/. Feel free to ask for help from maintainers [link to ask for help].

<!--[ADD MAINTAINERS PAGE - [Example](https://github.com/chef/chef/blob/master/MAINTAINERS.md)]-->

<!--[ADD INSTALLATION GUIDELINES - IF APPLICABLE]-->


# **Getting started**

Pull Requests are the way changes are made to the code, documentation and dependencies contained in the `VTF` repository. Make sure you have [git] installed locally.


### **Setting up a branch**

**Step 1: Fork and create a branch** [link](https://help.github.com/articles/fork-a-repo/)

If you identified a bug you can fix or want to make improvements, then fork `VTF` repository and create a branch with a descriptive name.

Fork the project on GitHub and clone your fork locally.

As a best practice to keep your development environment as organized as possible, create local branches to work within. These should also be created directly off of the master branch.


### **Making code changes**

**Step 2: Commit changes to your fork**

After doing the changes to your branch, commit changes to your forked code.

Keep your changes as logically grouped as possible within individual commits. There is no limit to the number of commits any single Pull Request may have, and many contributors find it easier to review changes that are split across multiple commits.

<!--[Any code style guide??]-->

<!--[Any documentation style guide?]-->

<!--[Any licensing signature required? ]-->

**Step 3: Add commit message**

A good commit message should describe what changed and why. 

If you are new to contributing to `VTF`, please try to do your best at conforming to these guidelines, but do not worry if you get something wrong. One of the existing contributors will help get things situated and the contributor landing the Pull Request will ensure that everything follows the project guidelines.

**Step 4: Rebase**

As a best practice, once you have committed your changes, it is a good idea to use [git rebase] to synchronize your work with the main repository.

**Step 5: Test**

All bug fixes and features should always come with tests. A guide <!--[ADD GUIDE FOR WRITING TESTS]--> has been provided to make the process easier.

**Step 6: Push**

Once you are sure your commits are ready to go, with passing tests, begin the process of opening a Pull Request by pushing your working branch to your fork on GitHub.

**Step 7: Open pull request**

From within GitHub, open a new Pull Request [[link](https://help.github.com/articles/creating-a-pull-request)]. You will be presented with a template that should be filled out:

<!--[ADD TEMPLATE FOR PR SUBMISSION - IF APPLICABLE]-->

Once opened, pull requests are reviewed by maintainers within 21 days.


### **Reviewing pull requests**

**Step 8: Merging a Pull Request (maintainers only)**

It's the work of the maintainer(s) to assess pull requests and merge them into the master. To be approved, pull requests need to be reviewed and pass tests run by a `VTF` maintainer. After review, if no objections are raised by maintainers or other contributors, the pull request is merged.

A PR can only be merged into master by a maintainer if:

*   It is passing required test cases.
*   It has been approved by at least two maintainers.
*   It has no requested changes.
*   It is up to date with current master. Make sure it is synced

Any maintainer is allowed to merge a PR if all of these conditions are met.

**Note on minor fixes**

Small contributions, such as fixing spelling errors, can be submitted through a "light" pull request and review process. It only requires one maintainer for acceptance and merge.

As a rule of thumb, changes are minor fixes if they do not introduce any new functionality or wider impact to the protocol. Some common minor fix examples include the following:


*   Spelling / grammar fixes.
*   Correcting typos like the transposition of letters in a variable name.
*   Cleaning up comments in the code.
*   Changes to white space or formatting.

<!--[ADD ITEMS TO MINOR FIX LIST - IF APPLICABLE]-->

<!--### Release cycles-->

<!--*   Bake-offs - quarterly-->

# **How to report a bug**


### **Security bug**


You must never report security related issues, vulnerabilities or bugs including sensitive information to the [`issue tracker`], or elsewhere in public. Instead, sensitive bugs must be sent by email to contact@verifiedtokenframework.com.


### **Other bugs**

Found a non-security related bug? Here are some notes on how to report the bug so we can fix it as fast as possible:

*   Ensure the bug was not already reported in the [`issue tracker`].
*   If you're unable to find any open issue addressing the problem, open a new one [link].
*   Explain, as detailed as possible, how to reproduce the issue.
*   Include what you expected to happen, as well as what actually happened.
*   Include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.
*   If possible, use the relevant [bug report templates] to create the issue.
*   Include all this information in a new issue on our `issue tracker`

<!--[ADD BUG REPORT TEMPLATE - IF APPLICABLE - [example](https://github.com/atom/atom/blob/master/ISSUE_TEMPLATE.md)]-->


# **How to suggest a feature**

Feature requests are welcome. Take a moment to assess if your idea fits with the scope and aims of the `VTF` protocol. If you see fit, make a case to convince contributors of the merits of this feature. Please provide as much detail and context as possible.

Below is a process to suggest new features:

1.  Check if your feature suggestion has already been raised under the [issues tracker].
1.  If no feature has been raised, open a new issue on our [issues tracker] on GitHub.
1.  Provide a clear description of the feature you would like to see, why you need it, and how it should work.
1.  Discuss with other contributors your features to gather feedback.
1.  After discussing the feature you may choose to attempt a [Pull Request]. If you're at all able, start writing some code and test cases. This will likely speed up the process.

<!--[Alternative, having a Request for Comment process for features - [example](https://github.com/emberjs/rfcs#ember-rfcs)]-->

Be mindful that some features can be "substantial". These will likely require a bit of design process and gathering feedback from other contributors.


# **Code review process**

The maintainer(s) team looks at Pull Requests on a regular basis in a monthly triage meeting.

After review and triage, if required, requests for further clarification are posted on the repository. After a request has been provided by maintainers, contributors are expected to come back within two weeks.

<!--[ADD TRIAGE PROCESS AND POLICY - [example](https://docs.readthedocs.io/en/latest/contribute.html#contributing-to-development)]-->

<!--[ADD PR CLEAN UP PROCESS - IF APPLICABLE]-->


# **Community**

You can also chat with other contributors and maintainers on [slack channel]. For security-related conversations contact contact@verifiedtokenframework.com. We welcome you and invite you to participate.

<!--[ADD LEVELS OF COMMUNITY CHANNELS - Troubleshooting, dev…- IF APPLICABLE]-->

