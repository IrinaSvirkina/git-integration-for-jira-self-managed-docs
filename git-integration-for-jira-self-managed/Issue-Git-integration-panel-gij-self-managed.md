---

title: Issue Git integration panel - Features
description:
taxonomy:
    category: git-integration-for-jira-data-center

---

<div class="bbb-callout bbb--note">
    <div class="irow">
    <div class="ilogobox">
        <span class="logoimg"></span>
    </div>
    <div class="imsgbox">
        <b>Note</b><br>
        By default, <a href='https://marketplace.atlassian.com/4984'>Git Integration for Jira</a> has the Git integration panel enabled. (<a href='#how-can-a-jira-administrator-enable-or-disable-the-issue-git-integration-development-panel'>How to disable?</a>)
    </div>
    </div>
</div>

<div class="bbb-callout bbb--alert">
    <div class="irow">
    <div class="ilogobox">
        <span class="logoimg"></span>
    </div>
    <div class="imsgbox">
        The <b>View developer tools</b> <i>permission</i> is required to view the Issue Git integration panel. Jira users must also have the <b>Browse Project</b> <i>permissions</i> to a project associated with a repository to view.
    </div>
    </div>
</div>
<br>

## Overview

The Issue Git integration panel displays:

*   **Git Commits:** number of commits and link to [Git Commits Issue Tab](/git-integration-for-jira-data-center/git-commits-tab-gij-self-managed/), link to [Git Roll Up Issue Tab](/git-integration-for-jira-data-center/git-roll-up-tab-docs-gij-self-managed/).

*   **Branches:** Create branch function, list of branches associated to Jira issue (Jira issue key must be in branch title)

*   **Pull/Merge Requests:** Create pull/merge request function, list of pull/merge requests associated to Jira issue (Jira issue key must be in PR/MR title), status of pull/merge request

*   **Tags:** git tags associated to Jira issue (via associated commit). Tags are sometimes referred to as Releases in some products.


![](https://bigbrassband.atlassian.net/wiki/download/attachments/1932329305/gitserver-git-integration-panel-view.png?version=1&modificationDate=1642594991246&cacheVersion=1&api=v2)

## How can a Jira administrator enable or disable the Issue Git integration development panel?

1.  Install the [Git Integration for Jira](https://marketplace.atlassian.com/4984) app.

2.  Navigate to the [**General settings**](/git-integration-for-jira-self-managed/general-settings-docs-gij-self-managed) page of the application.

3.  Enable or disable the setting: `Show Git integration panel on issue pages`.

4.  Click **Update** button.


![](https://bigbrassband.atlassian.net/wiki/download/attachments/1932329305/gitserver-gencfg-dev-panel-sel.png?version=1&modificationDate=1642598628491&cacheVersion=1&api=v2)

**Contact us**
If you still have a question - reach out to our [Support Desk](https://bigbrassband.atlassian.net/servicedesk/customer/portals) or email us at [support@bigbrassband.com](mailto:support@bigbrassband.com)

