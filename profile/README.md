# University of Pennsylvania GitHub Campus Program
GitHub Campus Program makes GitHub Enterprise features available to the Penn Community.

## University of Pennsylvania GitHub Organization
You must have a GitHub account before you can become a member of the University of Pennsylvania (upenn) organization on GitHub. You can use an existing account or create a new GitHub account here:

* [Join GitHub](https://github.com/)

You can use any available name for your GitHub account. If your PennKey username (PennName) is unavailable, consider using yourpennname-upenn (i.e. bfrankln-upenn). Since GitHub account names are not unique to the **upenn** organization, do not assume that a GitHub account belongs to a Penn affiliate because it is the same as someone’s PennName.

All members of the **upenn** GitHub organization are required to have two-factor authentication enabled on their GitHub accounts. If you have not done so already, see these instructions (be sure to save your recovery codes when prompted):

* [Configuring two-factor authentication](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)

After logging into your GitHub account (with two-factor authentication enabled), visit this URL to authenticate with your PennKey and automatically become a member of the upenn GitHub organization:

* [https://github.com/orgs/upenn/sso/sign_up](https://github.com/orgs/upenn/sso/sign_up)

Note that you can associate your Penn WebLogin SSO identity with any of your GitHub accounts, but only one can be associated at a time. You will also be required to enable [Two-factor authentication](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/accessing-github-using-two-factor-authentication) on your GitHub account, if you haven't done so already.

**WARNING:** GitHub is not suitable for storing sensitive information, including:

* Data subject to FERPA rules
* HIPAA protected information
* Unencrypted secrets such as passwords or private keys

## Why use Penn’s Github Campus Program?

Benefits:

* Protected by Penn WebLogin SSO
* [GitHub Teams](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-organizations-and-teams/about-teams) for cascading access permissions
* Standardized infrastructure available to University
* Security features enforced across all repositories in the enterprise
* [Security Vulnerability Alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies) for vulnerable repos
* Enterprise support for [GitHub Classroom](https://docs.github.com/en/free-pro-team@latest/education/manage-coursework-with-github-classroom/basics-of-setting-up-github-classroom) and integration with Canvas
* External collaboration with nonmembers is supported
* Continued access to code repostories is resilient to developer turnover
* GitHub Copilot coding assistant with multiple models (with Penn billing code; $19 / user / month)

Considerations:

* Not appropriate for storing sensitive data (see above)
* [File Size Limits](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github#file-size-limits)
* [Repository Size Limits](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github#repository-size-limits)
* [Migrating existing repositories into GitHub](https://docs.github.com/en/migrations)

## GitHub Copilot

GitHub Copilot is available for $19 per user per month [at the Business level](https://github.com/features/copilot/plans). At the business level, users are each given **300 premium request credits** per month [to use for queries](https://docs.github.com/en/copilot/managing-copilot/monitoring-usage-and-entitlements/about-premium-requests); using the default model, currently GPT 4.1, is free.

As of this writing, the GitHub Campus Management Team has set up Copilot as follows:

* **Data is excluded from training by default.**
* Models available: Claude Sonnet 3.7, Google Gemini 2.0, and OpenAI o3
* Organizations choose whether to enable EDITOR PREVIEW FEATURES.
* User feedback collection is disabled across the Enterprise.
* Mobile and Copilot Extensions are disabled across the Enterprise, to ensure data remains excluded from any training by default.
* Copilot is enabled on GitHub.com, for features such as automated Copilot for Pull Requests, Copilot Chat in GitHub.com, and knowledge base search.
* Copilot is enabled on both the CLI and IDE.
* Copilot can search the web for additional context.
* Copilot Metrics API access is enabled for administrators at the organization and enterprise level.
