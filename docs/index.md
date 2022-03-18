

# APIsec

###### APIsec - API Security Platform - https://apisec.ai
###### EthicalCheck<sup>TM</sup> - Free & Instant API Penetration Test Tool - [Try Now](https://www.apisec.ai/free-api-pen-test)



## APIsec - Feb 23rd, 2022

!!! danger "Security"

	- Playbook sync issue with inactive user fixed.


!!! tip "Features"

	- Auto-Onboarding feature launched: The APIsec automatic onboarding was designed to detect weekly specs to onboard their projects. This initial version now supports detection of the open api specs to register in multiple projects in the same account through API gateways.![AutoOnboarding](https://user-images.githubusercontent.com/87167426/158768718-232fe3f3-e5b6-434d-bce7-2fd6aed641cb.png)
	- Help text of Jira issue tracker introduced.![JiraelpText](https://user-images.githubusercontent.com/87167471/158938463-f48ece03-907c-4ea6-ac94-68159621d3eb.png)

	- Faster Playbook Generation - 15% performance improvement 
	- Propagate headers in activity list format are in badge style now. 

!!! success "Fixes"

	- Playbook sync issue with inactive user fixed.
	- Propagate assertion message fixed.
	- Duplicate project name issue fixed.
	- Default profile selection improved on issuetracker and CI/CD pages.
	- Vulnerability excel download issue fixed.
	- Display message if notification list is empty.
	- Message added for password protected url on project registration page.
	- Token field set to blank for auth type certificate on environment settings.
	- Password field made optional for certificate type auth in environment page.
	- Jquery dependency removed from CI/CD copy to clipboard.
	- Scan detail page cancel window showing duplicate buttons fixed.
	- Horizontal scroll removed from vulnerability actions dropdown.
	- License numbers issue fixed.

## APIsec - Feb 7th, 2022
!!! tip "Features"

	- Apigee SPEC type feature launched: Apigee Edge supports OpenAPI Specification 3.0, though a subset of features are not yet supported.![Spec type](https://user-images.githubusercontent.com/87167471/158939153-73d816b3-e4ea-4e40-ab9e-27ca9a001fbb.png)

	- Pentest report re-launched (1.3 version): A new version of pentest report launched, which gives altogether a new UX look and feel which will be easy to read.![pentest](https://user-images.githubusercontent.com/87167471/158940142-7d546950-972c-482d-8443-7f5a48a93612.png)

	- APIsec converter will now register the password protected spec urls.![Password PROETEX](https://user-images.githubusercontent.com/87167471/158940232-1b554809-8d67-4435-afb5-5899551cef90.png)

	e.g. https://<Username>:<Password>@<URL>

!!! success "Fixes"

	- Scan details page refresh button improved
	- Available license validation improved on UI
	- Notification icon hidden for non-admin users

## APIsec - Jan 20th, 2022
!!! danger "Security"

	- Basic test auth issue fixed.
	- CVSS score null issue and test creds validation issue fixed.
	- Sensitive data exposure L2 variable injection fix


!!! tip "Features"

	- Log4j category introduced: The Log4j vulnerability allows malicious attackers to execute code remotely on any targeted computer. ![log4j](https://user-images.githubusercontent.com/87167471/158940325-39b84534-396e-4dc0-811d-1c44e8b4814e.png)

	- Skip Filing Vulnerability feature launched: This feature will allow you to skip the vulnerabilities for selected categories.![SkipFilingVuln](https://user-images.githubusercontent.com/87167471/158940390-b43c6df0-8626-4d33-b1ac-c66edc9fc4f9.png)

	- Filter added for managed playbooks: This will allow users to filter the playbooks by bot or user. ![PBfilter](https://user-images.githubusercontent.com/87167471/158940455-1a539b28-19c0-49fb-b4b3-f9f4623d6b84.png)


!!! success "Fixes"

	- Page break 404 error on payloads tab fixed.
	- Page break 404 error on invite guest user fixed.
	- Test and save all auth bugs fixed.
	- Delete env button hidden for master environment, this is an improvement.
	- Default values (status and active) removed for the new auth before saving.
	- The High severity color changed to orange.
	- Snack bar messages remodified for bulk auth and test all auth.

## APIsec - Jan 12th, 2022

!!! danger "Security"
	- Jira bug logging issue fixed.
	- Reset password issue fix.
	- Injection strings in post playbooks are fixed.
	- Invalid Auth SQL Injection fix.
 	- Injections are fixed for Windows, Linux and XSS.


!!! tip "Features"

	- Notification feature launched: Track all the required product information (e.g. project credentials not working etc).![notification](https://user-images.githubusercontent.com/87167471/158940604-51ea4f52-e057-4946-b262-4552dbecc064.png)

	- Forgot password feature enhanced.

!!! success "Fixes"

	- Autocomplete off for environment auth fields.
	- Issuetracker issue fix, the creds disappear when a new environment is selected.
	- Jira bug logging issue fixed.
	- Reset password issue fix.
	- Injection strings in post playbooks are fixed.
	- File upload on project edit for api gateway fix.
	- Status improvements in the environment page.
	- Pagination issue fixed in header page.
	- Invalid Auth SQL Injection fix.
	- Injections are fixed for Windows, Linux and XSS.
	- Reports: Email Subject Update

## APIsec - Dec 15th, 2021
!!! tip "Features"

	- Support for SAML Authentication in Apigee API gateway integration.
	- Error playbook count added to org dashboard.
	- @EmptyValue added

!!! success "Fixes"

	- Error playbooks percentage upto 2 decimal values
	- Jira IssueTracker null Issue ID in logs/wirelogs fix
	- Request License contact url updated on project register page
	- Label added to apigee gateway authentication on APIgateway page
	- Add/Edit Vault page shimmer effect added
	- Handling ComposedModel recursive infinite loop
	- Rename Fxlabs to APIsec in injections
	- Updated Env page link in Actions
	- Notification list UI change
	- Alerts not displaying properly fixed
	- Delete confirmation msg corrected on vul details page
	- Dashboard page perf issue fix
	- Run details table pagination fix
	- Snackbar msg corrected on vul detail page
	- Snackbar msg typos fix
	- Perf Metrics: Config Details module
	- Skip Path check in Injection categories
	- Dashboard Performance Improvement: count tests/Runs query updated
	- Dashboard page perf improvements  added pagination and total endpoints count fix
	- Project list page tiles alignment for non admin users
	- New/Edit Account pages- radio buttons added
	- API Gateway name was not set while fetching specs. and error response was not returned fix
	- Replaced Coverage with Playbooks Count

## APIsec - Nov 30th, 2021

!!! danger "Security"

	- RBAC map error fix.


!!! tip "Features"

	- Payloads tab enhancement : Search by endpoint filter added on Default, injection and stored injection tab.
	- Propagate payload : Propagating payload within the playbook will make changes in injection and stored injection categories and playbooks of respective categories will be regenerated automatically.
	- Org-dashboard enhancement: Open vulnerabilities bar graph now showing monthly data.

!!! success "Fixes"

	- Corrected Log statement.
	- Renamed org-name FXLabs to APIsec.
	- Upgrade to standard tier link corrected.
	- Payload search exception fix.
	- 404 page not found  improvements.
	- CICD-Jenkins  documentation  and email value updated.
	- Password reset error message updated.
	- SQL Injection playbooks delete fix.
	- ABAC3 inactive scenarios issue fix.
	- Payloads filter issue fixed.
	- Payloads pagination issue fixed.
	- Project list page search option invisible issue fixed.
	- Alignment on myprofile page fix.
	- ABAC resource proper shimmer effect added.
	- Composed Model handling in Spec parsing.
	- Org Dashboard Month-Year Graph fix.
	- Propagate payload message improved.
	- Perf Metrics: Config Categories Module.
	- Scan history New/Closed/Total Vulnerabilities count issue fix.
	- Added Non working playbooks count to Project.
	- Error playbook percentage added on dashboard.

## APIsec - Nov 16th, 2021

!!! danger "Security"

	- Disabled new user feature for okta enabled org.
	- Disabled the password reset for OKTA from the org-user page.
	- Disabled the password reset for OKTA.
	- Deactivating the playbook functionality is deleting the playbook fix.
	- Password reset fix


!!! tip "Features"

	- CI/CD Jenkins :Added support for Email report after scan completion.
	- Added custom angular modal window on Alerts.

!!! success "Fixes"

	- Details tab dialog window fix.
	- Do not allow PWD authentication for OKTA enabled org users fix.
	- After propagating headers, the activities log is displaying incorrect info fix.
	- Project registration issue fix.
	- ABAC 3 resource refresh fix.
	- Bulk add Authentications input area is not displaying fix.
	- Playbooks are not generating fix.
	- Error in Propagate Severity in new SQL categories fix.
	- Page not found error on scan history page fix.
	- Page not found error on profile create page fix.
	- Page not found error on scan history analytics page fixed.
	- Inactive Playbooks count - fix
	- Build failed fix
	- Dialog windows typos fixed
	- Missing module imported
	- Updated the error message.
	- Snackbar msg improvement
	- Search field is hidden on the payloads tab.
	- Project dashboard page - don't show search field until page loads
	- Added null checks.
	- Raw file token ,file remain changes 
	- Cronjob weekly once for new project
	- Vulnerabilities details no longer accessible fix
	- Updated readme 

## APIsec - Nov 8th, 2021

!!! danger "security"

	- Stored SQL injection type fix.
	- SQL Injection category fix.


!!! tip "Features"

	- AI module integration : Implemented APIsec AI bot , It Intelligently detects severity and sorts type of vulnerability accordingly.
	- IdeaBiz API Gateway integration: A next generation integration platform as a service for cloud native engineering.
	- Pagination added in the payloads tab.


!!! success "Fixes"

	- Loader added on signup page.
	- Updated the title for RBAC vulnerabilities.
	- Changed reportFileType to optional.
	- Wirelogs and remediation columns removed from download all projects vulnerabilities report.
	- Activity API - EventStatus is null -->fix.
	- The snack bar message is displaying the category name as undefined fix.
	- Retaining scanner name on cloning a profile fix.
	- Severity propagation snackbar msg fix.
	- Missing tag fixed.
	- Typos fix.
	- After propagating assertion & severity, we need to manually refresh  fix.
	- Flag comparison corrected scan details page.
	- Playbook author fix for logging & monitoring cate.
	- XSS is shown as an assertion for propagate severity.
	- Assertion window is showing a blank fix.
	- Custom Playbook case-sensitive names persist--> fix.
	- Footer alignment issue fixed across the product.
	- Tooltip corrected.
	- Payloads pagination fix.
	- After propagating assertion & severity, we need to manually refresh the playbooks fix.
	- Performance: Orgs-Users Module.
	- Removed redundant object reference.
	- ABAC3 Resource lock.
	- Field added to run-detail page calls.
	- SQL Injection Categories - Remove DB selection.
	- Added logs in Cert Auth.
	- Playbook generates payload optimization.
	- Extracted Utility method.
	- Handling * in spec.
	- Handling * in path for playbook.
	- Removed * from path.
	- Corrected alignment.
	- CVSS score -- Fix.

## APIsec - Oct 26th, 2021

!!! danger "Security"

	- Page size decreased to 10 on the project dashboard.


!!! tip "Features"

	- Dialog enhancements: Browser dialog confirmation changed to custom angular material dialog.
	- Propagate headers feature launched in the playbooks action items. Users should be able to propagate headers across the all the playbooks for the specific endpoint.

!!! success "Fixes"

	- Search security model accuracy fix.
	- Serif converter updated in Github actions.
	- Master env data on the dashboard remains after non-master env deleted fix.
	- Shimmer effect added on default payloads page.
	- Project search feature on project list page fix.
	- Showing profile of selected env on issue tracker and ci/cd page fix.
	- Stored Injection component separated from default payloads.
	- Scan timeout increases from 2hrs to 3hrs.
	- Reports: Text export fix and export functionality for multiple formats.

## APIsec - Oct 20th, 2021
!!! tip "Features"

	- Okta Integration launched: Okta is one trusted platform to secure every identity, from customers to your workforce with Single Sign-On and more.
	- New SQL & Stored SQL categories launched.
	- Project search functionality added on the landing page.
	
!!! success "Fixes"

	- Search activities by users are fixed.
	- Playbook's deactivation issue fixed.
	- In project activities, search by entity and tag fixed.
	- Wirelogs added in get all vulnerabilities API.
	- Error popup on project deletion fixed.
	- Custom stored injection category payload fixed.
	- EST time and bounty value fields added to the security category page.
	- Remediation section removed from vulnerability details page.
	- Scanner name fix for new profile creation.
	- APIGateways fix - unable to register the endpoints and playbooks.
	- Reports design refactor to support multiple file types.

## APIsec - Oct 13th, 2021

!!! danger "Security"

	- Invalid AuthSQL: get injection strings from security marketplace.
	- Mark as unsecured error fix.
	- Issue tracker pagination improvements.


!!! tip "Features"

	- WSO2 feature launched in API Gateway module - A next generation integration platform as a service for cloud native engineering.
	- Vulnerability details page - vulnerability description and suggested fix time enhanced.
	- Playbook generation flow design refactor using RabbitMQ - This change made the playbooks to generate faster than before, 30% performance improvement.
	- GitHub Actions feature introduced: Automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.
	- Scan details action menu now gives a new look and easy access.
	- Scanner and date tile rearranged, moved it to the top.
	- Expand collapse feature added in swagger editor page.

!!! success "Fixes"

	- Propagate severity and assertion issue fixed.
	- False positives column removed from vulnerability table.
	- Issue tracker message improvements.
	- ABAC 2 & 3 resources fixed.
	- Non-Master environment losing its value, fixed across the product.
	- Scanner improvements.
	- Gitbackup console error fix.
	- Next-prev improvements in log details under activities page.
	- Jira formatting fix.
	- Category list and tiles view fixed.
	- Vulnerability list based on profile fix.
	- Time Out for scan shown on project recommendation with badge warning
	- Summary email reports buttons disable while scanning.
	- GitHub actions improvements.
	- Retaining closed/open vulnerability status from vulnerability details page.
	- Environment authentication hyphen fix.
	- Gitback is set active by default.
	- Compliance categories resources missing fixed.
	- Inconsistent numbers in closed vulnerabilities fixed.
	- Sort improvements on org users list.
	- Next previous button improvements.
	- Tabs routing to its default pages fixed.
	- Added logs in activities to show specs parse error.
	- RBAC multi new line fix.
	- Payloads search improvements.
	- Converter URLs moved to system settings.
	- Edit action removed from activity log.
	- Console error fix for system settings.
	- Trends page performance improvements.
	- Trends page download excel improvements.
	- Improvements in test all authentication environment pages.
	- Injections string fix for Linux, Windows and XSS.
	- Snack bar message corrected.
	- Owner name disappearing in vault fixed.
	- Search improvement in security list.
	- Added optional parameter tag in Scan API via script.
	- Added project based search in activities.
	- Post execution delay added in the playbooks.
	- Duplicate report names fix.
	- Postman and RAML moved to new IP fix.
	- Comments and reasons for closed vulnerabilities improvements.
	- Headers authentication type certificate fix.
	- Timeout flag added on scan timeout dashboard.
	- Sorting improvements for vulnerability table.
	- Redirection issue fix after reset password.
	- Anonymous authentication in init call fixed.
	- Removed authentication section from environment edit page.
	- Sub tab rearrangements under reports tab.
	- Table alignments in summary report.
	- Security category fix on click events.
	- Jira sync all issues fixed.
	- Not a vulnerability not reflecting in global dashboard fix.
	- Coverage page project name blinking issue fixed
	- Authentication delete issue fixed.
	- OAS editor endpoints validations.
	- Sync all API issues fixed.
	- Severity in reports fixed.
	- Typos fixed in project dashboard.
	- Profile edit bug fixed.
	- Init header injection fixed.
	- Cancel button added on profile edit and profile new


## APIsec - Sep 7th, 2021

!!! danger "Security"

	- Auth type certificate save action fix.


!!! tip "Features"

	- New feature "Download all project vulnerabilities" will now capture all open/closed vulnerabilities of the specific tenant.
	- On click expand/collapse functionality introduced in the playbook editor.
	- Summary report in the reports tab, Initial version released (V1).
	- Adding a new environment will now create all the default authentications automatically.
	- View XML response as pretty print.
	- Versions upgraded for postgres, node js, intellij plugins
	- Register the API project without supplying the API, create your custom spec in OAS editor. API Documentation URL
	- Delete/Cancel button added to bulk authentication.

!!! success "Fixes"

	- Scanner name changed from region to scanner name.
	- The new environment stays on the same page instead of redirecting to master.
	- Improvement fixes in RBAC and env auth test.
	- Scan details page alignments fix.
	- Bulk/Close archive vulnerabilities will now be redirected to the home page (fix).
	- Check status model window fix.
	- Custom category injection fix.
	- Trim project name in global dashboard.
	- Active by default fix in security categories.
	- Red cross mark removed from RBAC map.
	- Validate authentication issue fix.
	- Set random regions for master profiles.
	- Enhancements and fixes in Environments and Auths.
	- Test all auth will pop up only invalid auths.
	- Sync logs fixed in project activities.
	- View OAS file in editor - enhancements.
	- Project activity sortings fixed.
	- XSS playbooks generate fixes.
	- Propagate assertions bug fix.
	- Null fuzz category name fixed.
	- Anonymous auth init fix.
	- Env name disappearing while deleting fixed.

## APIsec - Aug 23rd, 2021

!!! danger "Security"

	- Edit/Delete auth fix.
	- Oracle stored sql injections fix.

!!! tip "Features"
	
	- Consolidated action items in environment page.
	- Categories in scan model window will show the auth status if invalid.
	- Select environment options
	- GitHub actions launched in CI/CD integrations.
	- Severity can be changed for single playbook or category, propagate severity feature launched in playbook action items.
	- Scanner names enhanced for more readability.
	Scanners name
	OAS V1 editor launched in endpoints page.

!!! success "Fixes"

	- Add bulk auth enhancements.
	- Sorting improvements in auth table.
	- Request and Response logs added for XML support.
	- False positive tile color changed to green in scan run details page.
	- Status column removed from global dashboard.

## APIsec - Aug 16th, 2021

!!! danger "Security"
	 - Private injection category fix.
	 - Env Auths fixes.


!!! tip "Features"

	- APIs (Public, Mobile, IoT, Web) now changed to Secured APIs SecureAPIs
	- Renamed API operation to API composition in reports page.
	- Action items enhanced in env page, consolidated menu for Add, Edit, Delete Env & Auth.
	- Colors and icons changed for a few tiles on the dashboard.
	- Renamed categories to Security Categories on dashboard.
	- Vulnerability severity graph position changed on dashboard.
	- Project Name and Since column added to vulnerability excel download.
	- Last scan badge removed and text muted in the project tiles. Last Scan
	- Severity high & score color is now set to orange for ABAC categories in the vulnerabilities dashboard.

!!! success "Fixes"

	- Cosmetic column name changes in global scanner table.
	- Uppercase applied for AWS in the scanners page.
	- Columns rearranged in the project dashboard vuln table.
	- Bundle collection for API Gateways & Activities module.
	- Snack bar messages fixed in issue trackers.
	- Environments are editable now, edit option in the action menu.
	- Ace color editor changed to single color in vulnerabilities details wirelog.
	- Sorting added on env auth table.
	

## APIsec - Aug 9th, 2021
!!! tip "Features"
	
	- XML Support: APIsec now supports the XML version which validates and registers the project
	- Vulnerability Report Download Enhancement: Vulns can be downloaded associated with the filters (Category & Severity).
	- User Variable: User variable is now set to case sensitive

!!! success "Fixes"

	- Configuration tabs: Breadcrumb position sticky to make it visible while scrolling down.
	- Category name alignment in scan history table.
	- Footer alignments fix.
	- Typos fixed.
	- Performance enhancements: Modules shipment for scanner, Vault, Security Model, Signin/Signup.
	- Playbook window resized for bigger screen.
	- RBAC map search placeholders fix.
	- Sorting columns in download as excel.
	- APIGateway: Multiple project registration fix.
	- Clone playbook from vulnerabilities and scan history fix.
	- UAT login issue fix.

## APIsec - Aug 2nd, 2021
!!! tip "Features"

	- Propagate Assertions: Changing assertions in a Playbook auto triggers the suggestion to apply the changes across the entire category playbooks. 
	- Vulnerability Report Download: Added six new columns like (Method, Playbook Name, Bug Bounty savings, CVSS, OWASP Rank, Since, etc.)
	- Environment: Defaulted to a detailed view. Instantly see all the credentials in an environment
	- Test Credentials: Instantly check your Jira and GitHub accounts are working.
	- RBAC: Separate columns to view method and endpoint (break out in RBAC map) and sorting applied.
	- Scan history reports: Enhanced both summary and detail report to the new version.
	- Project Dashboard: Project name trimmed and tooltip applied for a big text.
	- Wirelogs: Color coding disabled to avoid confusion with red/green texts

!!! success "Fixes"

	- GitBack sync: Individual and custom playbooks deletion fix.
	- Close vulnerability count fix on dashboard.
	- Dashboard tabs & Pagination: Extra spaces removed.
	- Assertions are fixed in AUTH categories, it has its own assertions now.
	- Free licenses removed from the product.

## APIsec - July 19th, 2021

!!! danger "Security"

	- Vault account fix.


!!! tip "Features"
	
	- New style for project tabs: Project tabs moved to breadcrumb position. White background added & table size aligned.
	- Dashboard enhancement: Dashboard changed to the project name with bold view.
	- Org list: Created by column added into the org table and email notification.

!!! success "Fixes"

	- Column alignments in ABAC categories.
	- Clear the fields on change of account type - vault.
	- User variable copy to clipboard fix.
	- ABAC3 payload fix.
	- Org tag update fix.
	- Duplicate org name fix.
	- Dismiss snackbar when error popups.
	- Sorting fixed in the global scanner.
	- CLI link updated.
	- Pagination fix from the project list, landing to the home page.
	- Console error fix for scanner check connection.
	- Extra spaces removed from collaborators page.
	- Enterprise license removed from details page.

## APIsec - July 5th, 2021
!!! tip "Features"

	- Propagate assertions: A new feature is added into playbooks actions which instantly propagates the assertion throughout the category.
	- Issue tracker enhancements: Enhancements applied for the Jira and Github.
	- Report storage: The default storage feature allows to save all the generated reports.
	- Test Credentials: Test credentials feature introduced for issue trackers.
	- Non-OAS Spec: Introduced a page to view the original file loaded as OAS.

!!! success "Fixes"

	- Show less added in the advance section of project registration.
	- Github data sync issue fixed.
	- Profile menu width increased.
	- Free licenses removed from org.
	- Typos fixed.

## APIsec - June 21st, 2021

!!! danger "Security"

	- Manage skip paths fix in Unsecured and AUTH categories.


!!! tip "Features"

	-	Categories pie chart: Categories pie chart made clickable, which takes you to the vuln management.
	-	Spinner introduced on the playbooks tile: Playbooks creation will now show the spinner (in progress) on the tile until it completes.
	-	Trigger scan: Trigger scan will now redirect to the scan history page.
	-	Payloads: Payloads tabs enhanced for easy access.
	-	Snack bar: Playbook creation will now show the status on the snack bar.

!!! success "Fixes"

	-	Multiple headers are now supported for Auth.
	-	New playbooks and activities page direction fixed.
	-	Global dashboard sorting fix.
	-	URL names changed to sync the page names across the product.
	-	Side menu added in env, variables, and profile pages.
	-	Copy-paste removed from confirm password field.
	-	Page size minimize in web browser fixed.
	-	Removed save & close action from playbooks.
	-	Private scanner rows made clickable in the security marketplace.
	-	Shimmer validation issue fixed under the details tab.
	-	Date and owner name fix on project tile.
	-	RBAC map open from dashboard fix.

## APIsec - June 15th, 2021

!!! danger "Security"
	- Injection fix in AuthNoSql category.
	- Added content for a basic role in all the pages.
!!! tip "Features"

	- Activate/deactivate playbook: New action item introduced.
	- Browser enhancements: Now APIsec product is supporting the MS edge and apple safari browsers.
	- License enhancements: License numbers enhanced for both free and paid.
	- Angular version upgrade: Upgraded to version 12.

!!! success "Fixes"

	- VC-Git consumer count increase to 10.
	- Added basic role in the org user pages.
	- Azure key encryption in the backend.
	- URL page name changes.
	- Duplicate header content fix in the details tab.

## APIsec - June 7th, 2021

!!! danger "Security"

	- XSS Injection query param fix: Injection to be injected in query param strings.


!!! tip "Features"

	- Password validation: Confirm password field and strong password validation introduced on the free signup page.
	- Configuration tab enhancements: Variables and profiles tabs moved under environments.
	- Org enhancements: Added filter for org tags and removed legal name column.
	- Org notification: Custom email group field added for new org creation.
	- Beta tags: Beta tags removed from security marketplace and muted in issue trackers, ci/cd integrations, and categories.
	- Bot: Large response truncated to 1 MB with notification text in wire logs.

!!! success "Fixes"

	- Duplicate outbound email footer fixed.
	- Alignment fixes in the free signup page.
	- Callout removed in payload and categories.
	- Orgs with billing fxlabs.io are deactivated.

## APIsec - June 1st, 2021

!!! danger "Security"

	- RBAC map fix: fixed form-data type.
	- Access key expiration added for the playbook generation failure fix.


!!! tip "Features"

	- Free account introduced: The free user will be able to signup and run the security testing, but restricted to access the Integrations and - Reports tab.
	- Dashboard enhancements: Renamed settings tab to configurations and sub-tab details to the API project.
	- Org enhancements: Added few org tags like PARTNER, CHURN, OPPORTUNITY.
	- Org table enhancements: Columns renamed and, used license numbers added.
	- Email notification: Trigger notifications to super admins for new tenant creation.
	- Beta tags: Beta tags removed from API gateways and reports. 

!!! success "Fixes"

	-	Report fixes.
	-	Advance project section error fixed.
	-	Request Headers: Processing request headers in the body
	-	Jira: Wire logs are now showing in Jira.
	-	Null value injection: Inject null when value not found to avoid resource not entitled error.
	-	Propagate assertions from playbooks to categories.

## APIsec - May 24th, 2021

!!! danger "Security"

	- Url validations applied in environment pages.


!!! tip "Features"

	- Integrations tab: Introduced the new Integrations tab to accommodate Report storage, Issue tracker, Notifications, Git Backup, CI/CD in one place.
	- Pentest & Developer Report: Graph modified for better vision and few other enhancements.
	- Org page: Org tag added to identify customer or prospect.
	- Huge Payloads Blocker: Blocker introduced for huge payloads or files.

!!! success "Fixes"

	- Jira issue tracker fixes.
	- Jira issue tracker severity mapped to the APIsec severity.
	- Redirect access page to login page.
	- Modified FX to APIsec in the system settings page.
	- Text help improvements in Integration inner tabs.

## APIsec - May 3rd, 2021
	
!!! danger "Security"

	- Injections removed from date types from all the injection categories.


!!! tip "Features"

	- GCP storage integration: Connect your GCP storage account and receive API Penetration Testing reports automatically monthly.
	- Certificate Auth: New feature certificate added to authentication type in the environments.
	- Error playbooks: New feature error playbooks introduced on dashboard and playbooks page.
	- Curl command support: Curl commands can be verified through test authentication in environments.
	- Monthly job schedules: Triggers developer & compliance report every month.
	- Manage skip paths: Manage coverage is now manage skip paths in unsecured and auth categories.
	- Jira issue tracker: Default issue type set to Bug and applied validations for the mandatory input fields.
	- Action tile: In the vulnerability details page, the action tile is sticky now.
	- Developer report: Category name added to the endpoints of the table content.
	- Login page: Privacy policy page link added to the MSA.
	- Remove user: Added remove user functionality for the guest users. Can be removed only by Admins.
	- Category list view: "Last Modified By" column added to the table.

!!! success "Fixes"

	- Validations included for add authentication forms.
	- Font-size adjustments in Gateways, Vault, Dashboard, Security Marketplace, Register API.
	- Endpoint sorting fixes on vulnerability table on dashboard.
	- Select All fix for the scan dialog window.
	- Inconsistent count of overlapping roles in RBAC map fix.
	- Close compliance categories fix.
	- Removed skipped vulnerability count from close vulnerabilities tile on the dashboard.
	- Removed get query param playbooks from Stored NoSQL category.
	- Payloads injections fix.
	- Cosmetic fixes in the reports.
	- Project health status fixes for invalid and not reachable values.
	- Removed the last page from all the reports.
	- Set SC 500 as false positive in all the categories.
	- Set SC 400 as false negative in all the categories.
	- Active flag added to the header customization category.
	- Page navigation fix in developers report.
	- Heading added in the variable bulk page.
	- Invalid endpoints fix in postman collection converter.

## APIsec - April 19th, 2021
!!! tip "Features"

	- Compliance Report: Compliance report launched.
	- Vulnerability details (Excel download): Wirelogs and Remediation columns added to the sheet.


!!! success "Fixes"

	- Space adjustments in tabs (scanner page).
	- Left & right padding added globally.
	- Show tutorial steps removed.
	- Header text updated to call out standard.
	- ABAC severity fix.
	- Categories in the scan window improved, OWASP ranks sorting applied.
	- Save icons removed from the graphs.
	- Changed FX to APIsec in the vuln issue tracker details.
	- Filter applied to remediations in the reports.
	- Project registration tile fix.
	- Console error fixes.
	- Aligned logo, page items and activity tile.
	- Forgot password made to lower case.
	- Renamed the custom tab to default in payloads.
	- Changed FX to APIsec in UI pages.
	- Additional text removed from all the create buttons.
	- Shimmer effect fix.
	- Environment test authentication token issue fixed.
	- Postman collection (API Gateway) fixed.


## APIsec - April 5th, 2021

!!! danger "Security"

	- Query parameter fix for stored injections

!!! tip "Features"

	- Security improvements: Java-runtime upgrade from version 8 to version 13 across all APIsec micro services for improved security and performance
 	- Filter projects: Admins can now see only their registered and managed projects by default. Admins can also see all other projects using the toggle control "My projects/All" on the main page.
	- API Security Developer Reports: launched (Beta).
	- AWS S3 Integration: Connect your AWS S3 storage account and receive API Penetration Testing reports automatically monthly.
	- Azure Storage Integration: Connect your Azure storage account and receive API Penetration Testing reports automatically monthly.


!!! success "Fixes"

	- MuleSoft RAML fix
	- Moved "Bulk Add" authentications link next to "Add Authentication" on environment page.
	- Renamed "FX Issue Tracker" to "APIsec Issue Tracker"
	- Removed options "Delete" and "Bulk Close/Archive" from Closed vulnerabilities action items
	- Kubernetes deployed scanner status is now showing Running in the Scan window
	- Skip path check-in - Injection categories
	- Query and body parameter fix
	- Kubernetes scripts corrections
	- Error playbook column added to the reporting table
	- Handling escape characters text added in the playbook documentation
	- Activities tile aligned on the dashboard
	- Search vulnerability by endpoint enhanced added.
	- The EULA page agreement button is always visible.

## APIsec - April 13th, 2021

!!! danger "Security"

	- Scan not found error fixed.
	- Severity changes fix in the ABAC category.
	- Org edit error fix.


!!! tip "Features"

	- Playbook Management: Playbook management name changed to (Bulk Create/Delete Playbooks).
	- Vulnerability: details page structure changed from tabs to scrollable.
	- Variable codes: added to the variables under the variable tab.
	- Release Notes: The release notes link added to the footer.
	- Forgot password: Forgot password functionality added to the login page.

!!! success "Fixes"

	- Header text added to the setting tabs.
	- Filter applied for developers report omitting remediation's for non-critical categories.
	- RBAC map view from the vulnerabilities detail page.
	- Default scanner selection through advance section fixed.
	- Stopped status on dashboard fix after canceling the scan.
	- "My projects/All projects" selection is sticky.
	- Update/Delete validation added to Azure & AWS storages.
	- Tag added to SLA category in the scan window.
	- Different screen size fix.
	- Activities tile aligned on the dashboard.

## APIsec - Jan 2018 - April 2021

!!! example ""

	+ Archived Releases
