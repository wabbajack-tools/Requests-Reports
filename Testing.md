# **Featured Review System Design Doc:**

*Design document for forming a new system for "Featured" status. It being written here* **DOES NOT** *mean it is guaranteed to be in the newly designed system*. This document is being filled out to create a framework to see if it is agreeable and hypothetically solves the issues prevalent in the current system. Also there isn't autocorrect so...apologies if there's typos, it's a lot of info to pull together.

This system seeks to address some of the issues that have been pointed out by users, modlist authors and moderators about our current feature review system and it's issues. Please see below for the outline on those problems identified, and solutions. The current working solutions can be seen under Featured criteria, Featured Framework Overview and Review Reporting. 

## Sections:
- Problems
- Solutions
- Featured Critera
- Featured Framework Overview 
- Review Reporting


# **Problems:**

### **Modlist author/user side:**

Issues will be addressed with solutions below. If you have any further concerns please highlight them to @JTK on discord in one message which we can further discuss.

1) Reviews take too long. - *May improve. Subject to future review. *
2) Reviews don't account for new modlists/modlist authors with 0 contact well enough.suggestion: *git message to authors with a merged pull request with the full documentation on how to go forward on featured stuff. This should be doable through github actions. Trigger for this aka first repo addition, etc needs clarification*
3) Lack of reviewing featured status for existing lists. - *Framework outline. Detail and definitions needed.* https://discord.com/channels/605449136870916175/623261438022254612/1161023280178806805
4) Lack of transparency (hence people thinking 1000 downloads etc). *See Framework Overview*
5) The above not making it a reliable quality metric. -*May improve. Subject to future review. *
6) ~~The user view that "Lack of updates = buggy/incomplete"~~ - *Unsolvable*
7) Not enough feedback as to *why* list doesn't become featured. - *See Framework Overview*
   

### **Moderator/Reviewer side:**

1) Monitoring all of these is incredibly time consuming. - *May improve. Subject to future review.*
2) Limited information to determine patching quality without installing, where quantity makes it very difficult to do old style xEdit testing/game testing. - *Framework Overview + Testing framework. Is it enough?. " *
3) Nobody wants to do it due to the quantity of work and people working on their own stuff.  - *Possible expansion to those reviewing, "trusted" sources for each game?*
4) Maintaining quality standards that allow us to reject bad stuff and not become Collections with worse branding. - *Clarified standards but not sure how far this changes things*


### **Solutions suggested:**

1) Featured Communication (form TBD)(1 or combination) - Forms, Modmail, Github Repo 
2) Exact criteria definitions for approval
3) Some form of testing - *Identified brigading issues with most solutions.* 
4) A rating system. - *Identified issues*
5) Ensure Wiki and server are fully updated with *whatever* system ends up being.
6) Ensure all documentation covers Featured/Show All Lists, rather than "Official" nomenclature. 


### **Not a Solution:**

1) Old style testing


### **Provisionally Accepted Solutions:**

1) Ensure Wiki and server are fully updated with *whatever* system ends up being.
2) Ensure all documentation covers Featured/Show All Lists, rather than "Official" nomenclature.
3) Exact criteria definitions for approval - Definitions TBA


# Featured Criteria: Exact definitions TBD

#### Featured Criteria will be broken into clearly defined criteria that are assessable and transparent for prospective modlist authors, or anyone who is curious. 

- Support activity and quality, 
- Documentation quality
- Modlist patching, 
- Prevalence of unresolved conflicts
- Crashes and bugs.
- Modlist must have sufficient proof of the above, newly released lists with no downloads will not be considered immidiately. Popularity and longevity are **only** considered for evidence to prove the above.

#### Additionally to help improve the speed at which featured reviews take place, we will require the following to be submitted when an author seeks to make their list "featured":

- Definition and Description of list for /FAL
- Load order library for any list made for a game it is compatable with

# Featured Framework Overview
#### Github Issues based system. Whereby each Featured Critiera are reviewed, with information able to be submitted for each point. Labels and checkboxes used to denote progreess. Much more transparent system. 

Much better to showcase a alpha mockup of it rather than an unclear explaination of functionality, please see: https://github.com/EzioTheDeadPoet/demo_rep/

Featured Requests, Issues with modlists and license issues are all reported as "Issues" on the new repo that will be made. You can see a couple of examples in the issues tab, feel free to create an issue to see how it works on the side of someone submitting request/issue.


# Review Reporting

Design framework for featured reviews and "re-reviews". Look at the framework, not the specific definitions of each thing, will be defined more later on, this is just an example to suggest a methodolgy to better classify issues that would prevent "featured" status.

Error reporting form for error submission used for "New Featured applicants" and the rare cases of lists that may require a "Re-Review"

- User submits error, bug, issue, lack of support, general problem they have. This *requires* evidence. Some kind of user friendly solution for the form is 100% needed. 

- Error report gets looked at and categorised: Put into e.g. Tier 1-3 or rejected based on info provided.

Modlist author gets a prompt of some kind to respond (Possible bot automation for prompt?) Mod author response considered into rejections/tiering. Possible to put error into "Waiting fix", where it will progress to defined T-error until <determined time> has passed. If fixed, removed. If not, error applied against retest criteria. 

- T1 - Gamebreaking Major Bug, major support issue, repeatable consistent CTDs 

- T2 - Medium tier errors that need defining in some way

- T3 - Minor issues e.g. clipping, one blackface conflict. Little things that are annoying but not gamebreaking for users. 

Retest is triggered on the basis # of errors:
Hypothetical Example: T1 = 10 x T2, T2 = 10 x T3.
3 T1 errors required for retest.


#### Numbers and examples in tiers are *purely hypothetical to illiustrate what the system could look like*. They will be defined **exactly** later.




- 
