# APIsec

###### APIsec - API Security Platform - https://apisec.ai

## APIsec - May 23rd, 2024

!!! danger "Security"

	- **Scanner Security**: Improved security in container image to resolve malware detected.
	
!!! success "Fixes"

 	- Many defects have been addressed with this release.

## APIsec - May 9th, 2024

!!! tip "Improvements"

	-  **hasAny or hasAll keywords**: The hasAny or hasAll keywords are supported in assertions across all categories.
 	-  **SwaggerHub Integration**: The SwaggerHub integration allows URL replacement for retrieving specifications.
	
!!! success "Fixes"

 	- The issue where allowed and disallowed tags were copied across all playbooks when using regex in assertions has been fixed.

## APIsec - April 4th, 2024

!!! tip "Improvements"

	-  **Security Categories**: The JWT Security Category has been implemented.
	
!!! success "Fixes"

 	- The identification of open CVEs in the APIsec Scanner, which represent potential security risks, has been addressed.
 	- Scans terminated as errored have been fixed.
  
!!! note "Note"

 	- A scanner refresh is required.
	
## APIsec - March 20th, 2024

!!! tip "Improvements"

	-  **New Feature: New Customer Onboarding Wizard**: Launched new beta feature to help customers with onboarding. This wizard is designed to empower customers to navigate their onboarding journey independently, ensuring a seamless experience with minimal manual intervention.
	-  **Security Categories**: Reflected GET Injection category updated based on latest security trends.
	-  **Integrations**: Enhancements to the MuleSoft integration updated to include a wider range of APIs in various environments regardless of naming convention.

!!! success "Fixes"

	- Many defects addressed with this release.

## APIsec - February 29th, 2024

!!! danger "Security"

	- **Scanner Security**: Improved security in APIsec Scanner to resolve open CVE's.

!!! tip "Improvements"

	-  **Security Center**: Updates to the Security Center to de-duplicate monthly data.
	-  **Enhancements to YAML Processing**: Enhancements to processor of complex YAML schemas and improve handling of edge cases.
	-  **Inference Engine**: Launched Inference Engine to automatically reduce false positives based on scan results and specification inconsistencies.

!!! success "Fixes"

	- Many defects addressed with this release.

## APIsec - January 31st, 2024

!!! tip "Improvements"

	-  **Monthly Report Updates**: Added the ability to select who should receive automated monthly reports from the APIsec platform.
	-  **Playbook Generation**: Enhancements to the automated playbook generation mechanism and synchronization.
	-  **ServiceNow Enhancements**: General improvements to the official ServiceNow integration.

!!! success "Fixes"

	- Many defects addressed with this release.

## APIsec - January 4th, 2024

!!! tip "Improvements"

	-  **Online Documentation Updates**: Online documentation has been updated for all APIsec integrations with simple to follow instructions.

!!! success "Fixes"

	- Many defects addressed with this release.


## APIsec - December 4th, 2023

!!! danger "Security"

	- Increased security of the platform by improving application control and enforcement features.

!!! tip "Improvements"

	-  **Skip Endpoints Enhancements**: Changed the Category ID to the Category names in the Skipped Endpoints list for better customer experience.

!!! success "Fixes"

  - Jira Integration issue resolved.
	- MuleSoft Integration issue resolved.
	- Many other defects addressed.

## APIsec - November 20th, 2023


!!! abstract "Improvements"

    - **Vulnerability Comments**: Enhanced the visibility of vulnerability comments.
    - **GitHub Integration**: Numerous enhancements related to GitHub integration including configuration updates, credentials, and playbook synchronization.
    - **Teams Feature Enhancements**: Enhancements to the previously released Teams feature based on customer feedback.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - October 5th, 2023


!!! abstract "Improvements"

    - **New Integration**: Introduction of the JumpCloud integration in this release. With this new feature, you can now seamlessly integrate your APIsec account with JumpCloud for enhanced user management and security.
    - **Vulnerability Navigation**: Added the filter by category option to the Vulnerabilities screen.
    - **New Teams Feature**: Administrators can create teams of users, optimizing access to specific objects according to Team based access controls.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - September 23rd, 2023


!!! abstract "Improvements"

    - **Security Categories**: Playbook autogeneration now supports custom parameters. Improvements to Rate Limit playbooks with POST operations. Excessive Data Exposure categories improved as well.
    - **List Sorting Improvements**: Sorting now available as an option throughout the User Interface.
    - **Security Center Updates**: Added new dashboard to report on a comprehensive List of Unscanned APIs.
    - **Aesthetic Improvements**: Buttons, fonts, tooltips, and text is now easier to read throughout the User Interface.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - September 1st, 2023


!!! abstract "Improvements"

    - **Updated Vulnerability Age Formula**: Enhanced the Vulnerability Age calculation in response to user feedback. Instead of displaying the number of days since a vulnerability was first discovered, it now calculates the age based on the time between the vulnerability's discovery and its subsequent fix.
    - **Scanner Listing Improvements**: enhanced the Scanner listing by adding Build Time information and Start Time.
    - **Enhanced Vulnerability Reports**: Several improvements with vulnerability reports to allow users to download additional details that were previously unavailable.
    - **New Scanner Option**: Added support for multi-cluster scanner setup as a new option.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - August 16th, 2023


!!! abstract "Improvements"

    - **Added OAuth2 Authentication Options**: Streamlined the OAuth2 wizard.
    - **Additional Integrations**: Added support for Microsoft Teams Notification.
    - **Security Center Updates**: Several improvements with Security Center dashboards.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - July 31st, 2023


!!! abstract "Improvements"

    - **Added Skip Endpoints**: Configuration of "skipping endpoints" is now possible as a global setting.
    - **Additional Integrations**: SwaggerHub API Gateway support, Azure Active Directory user and user roles auto-mapping.
    - **Security Center Updates**: Several improvements with Security Center dashboards.

!!! success "Fixes"

    - Many defects addressed with this release.

## APIsec - July 19th, 2023


!!! abstract "Improvements"

    - **Authentication Testing**: Basic authentication tests are now possible directly from the UI.
    - **Improved Messaging**: Many improvements and optimization with pop-up message dialog.
    - **Improved Security Categories**: Launched "Insecure Parameters" category.
    - **Improved Slack Integration**: Updated Slack notification alerts to include additional details.
    - **New Feature Spotlight: Security Center**: Security Center is now live. Please navigate to the "Security Center" tile and check it out.

!!! success "Fixes"

    - Many defects addressed with this release.


## APIsec - March 27th, 2023


!!! abstract "Improvements"

    - **New Org Creation**: With this release, every new tenant will be created with the crAPI project via Auto-pilot. crAPI is a vulnerable API project created by OWASP to educate Security Practitioners on API security risks and attack patterns. This ensures that all new users have access to a fully-onboarded API project so the outcome of the API onboarding process is more clear.![CrAPI](https://user-images.githubusercontent.com/105206963/228031392-4c8a1be5-3760-4bc7-a7f3-d3c90446eccc.png)


!!! success "Fixes"

    - Playbook name now has special characters restriction. Users are no longer allowed to use special characters such as %, $, #, *, etc. in the Playbook name field.
    - Fixed a UI issue which occurs when an API Specification does not have a fully qualified domain name.
    - Resolved an issue with updating project names and tags in the details tab of API Projects created without providing a spec file. Previously, users were unable to make changes to project names and tags. Now, users can update project names and tags as expected.![No API](https://user-images.githubusercontent.com/105206963/228031643-d1f1d788-c8e2-47fc-877b-4ae7ea5ed8bc.png)


## APIsec - March 15th, 2023


!!! abstract "Improvements"

    - We have release several Postman integration improvements:

		1. APIsec will now read any pre-request scripts in your postman collection for generating a token.  You will be able to access this script from the environments tab of the appropriate imported API. This script will not be run, but will be available if you want to copy it and manually execute the script to generate a token.![image](https://user-images.githubusercontent.com/105206963/225819307-4bc54fb9-f3b3-41e9-9bb2-e1717f8e0a3f.png)<br>To read more about pre-request script in Postman, please check out their [documentation](https://learning.postman.com/docs/writing-scripts/pre-request-scripts/).<br>

		2. APIsec supports displaying user defined headers in the postman. These will be shown in the playbooks under headers.![Headers](https://user-images.githubusercontent.com/105206963/225830185-756e75bb-00e2-4e90-a06f-d4cc02b69e8e.png)

		3. APIsec supports displaying original payload defined in the postman. Prior to this change, we would only show a sample payload.![headers1](https://user-images.githubusercontent.com/105206963/225830309-bd208da5-d9d0-4d3d-bbcb-fac84582fe78.png)

!!! success "Fixes"


    - Configurations-> Environments-> Variables Section:

		1. Issues deleting an existing variable issue have been fixed.
		2. Improved messaging when a new variable is added.![snackbar](https://user-images.githubusercontent.com/105206963/225223360-8b057a04-cecc-4542-9ee3-d00a0fdd1db6.png)

		3. **New variables(Bulk)** -  There was an error when added bulk variables in the help text. This has been corrected.

    - API Gateways - Messaging formatting improved during the API import.
    - Details page - API project name name length text wrap issue has been fixed.
    - Several empty profiles are added automatically upon project registration or cloning an environment, which results in "Master profile not available" error upon running a scan issue has been fixed.

    - **Project Tagging:**

		1. Error fixed when a project is registered through advanced section tag was not showing instead. Now it is showing.
		2. In API's table - If multiple tags were added it is getting overlapped with the source column instead. It is fixed now.![Multiple](https://user-images.githubusercontent.com/105206963/225223950-1bee68c2-d46a-4921-b8c2-127fbd77f5b8.png)

		3. Text wrap is added for tag name length.![text wrap](https://user-images.githubusercontent.com/105206963/225224002-1501bef7-eb6b-4611-ac05-8a4725d6053a.png)


!!! note "Note"

      - We have released a bug fix for the SSL Assertion category. To see the changes, please manually refresh local scanners.




## APIsec - March 6th,2023


!!! tip "Features"

      - **Spec Analysis**: We have introduced a new feature where we will analyze the specification.<br>At the moment it will look for the following:<br>
		- Incomplete items in the specification that are recommended to be there.
		- Items that are defined but lead to issues such as:
   			1. Basic auth
   			2. Parameters in methods that you should not use.
		![Spec Analysis](https://user-images.githubusercontent.com/105206963/223140935-0a4de044-7c0d-495b-b3b2-0149406e9169.png)
		More information can be found at our [documentation](https://docs.apisec.ai/SpecAnalysis/)


      - When creating a project and loading a new API, we will now automatically create 4 separate profiles. Each profile will refer to our security tiers. For more information on our security tiers, please go to this [link](https://docs.apisec.ai/SecurityCategories/) in documentation.![Tier](https://user-images.githubusercontent.com/105206963/223140880-ba9d8660-f942-4906-8d10-d3e3fe0d7a5a.png)



!!! abstract "Improvements"

        - Added the ability to see the SOURCE  of the API when viewing the API’s as a list.
      	<p>Options shown are:<br> File.<br> URL.<br> API_GATEWAY.</p>

  	![Source](https://user-images.githubusercontent.com/105206963/223141779-ca97b07f-35ef-4cf3-bd74-1ee87e7d7723.png)


!!! success "Fixes"

    - API Gateways - If the API that was registered via a gateway is no longer in the gateway, you would receive a message stating “Unable to generate playbooks”.  With this change, instead of getting an error message we will utilize the specification that is stored in APIsec.
    - Main page - APIs table - Navigation bar should get refreshed when we are logging in.
    - Project dashboard - vulnerabilities table  - Fixed an error where clicking the "Back" button on the Vulnerabilities details page would take you to the wrong page instead.
    - Configurations - Environments - Profiles - The training profiles will be hidden by default now. Users can see it by clicking on the "show training profiles" link.![Training Profiles](https://user-images.githubusercontent.com/105206963/223142268-7b37e95d-6736-4860-85b6-217a96dd6a3f.png)

    - Environments tab - When we cloned multiple environments and open a scan window it is throwing an error  issue has been fixed.
    - Endpoints section - Add endpoints - After adding endpoints scan is not getting triggered instead. Now scan is getting triggered.
    - Error fixed at profiles page while creating a profile, if scanner is not selected it was showing any random scanner on scan window instead. Now it is displaying the correct scanner.




## APIsec - February 24th, 2023


!!! abstract "Improvements"

    - Main page - The toggle now defaults to the “All API’s” instead of My API’s.![All Apis](https://user-images.githubusercontent.com/105206963/221225532-0b3b94d4-685e-4ac4-8f3b-75d6d5ff6bb1.png)
    - Configurations - variables tab - Delete option has been introduced in the variables table.![variables](https://user-images.githubusercontent.com/105206963/221227836-efb3c264-05b1-4808-b3e8-7700b32be1d3.png)
    - We now support variables in the base URL in Postman collections. During the import process, the variables will be resolved into the correct base URL.
    - If the OAS file contains multiple environments for an API, we will now automatically create all environments for a given API.


!!! success "Fixes"

    - Detailed scan report text alignment issue has been fixed.
    - Fixed an error where clicking the "Back" button on the Vulnerabilities page would take you to       the APIs page instead. Now it takes them to the Vulnerabilities section.
    - Project activities page - project name length text wrap  issue has been fixed.
    - Configurations - variables tab - Distorted UI issues have been fixed.
    - Unresolved Variables in the Base URLs issue have been fixed.


## APIsec - February 17th, 2023


!!! tip "Features"

      - Project Tagging -  This feature allows users to easily organize and categorize their projects for improved visibility and accessibility.![Screenshot 2023-02-17 153959](https://user-images.githubusercontent.com/105206963/219617975-bc97ca0f-2ee3-4a66-bccd-128df0b0438e.png)


!!! abstract "Improvements"

      - API Gateways - Improved with pagination and the ability to select all APIs in one go.

!!! note "Note"

      - Private Scanners will need to be refreshed.


## APIsec - February 10th, 2023


!!! abstract "Improvements"

    - Alert message for variables and bulk Auth are made window consistent.

!!! success "Fixes"

    - Search API field on the main dashboard is fixed.
    - Scan triggered via Jenkins failed to send a report issue is fixed.
    - Adding new endpoints & trigger a scan completes without any playbooks issue is Fixed.
    - On the vulnerabilities details page - the remediations field is fixed.
    - Playbook generation - single playbook issue is fixed.

## APIsec - February 2nd, 2023


!!! tip "Features"

      - AutoPilot : The Autopilot feature now has the ability to automatically trigger scans after playbook generation,With this feature, users can be confident that their playbooks will be scanned promptly and any necessary changes can be made promptly.


!!! abstract "Improvements"

      - Added active button to Issue Tracker for APIsec Issues.
      - Messaging improved for the playbooks page.

!!! note "Note"

      - Private Scanners will need to be refreshed.



## APIsec - January 27th, 2023


!!! tip "Features"

	- Variable page - Edit feature is added for ease of Variable customizations.

!!! success "Fixes"

	- RBAC inactive authentication issue is fixed.
	- When the payload is not modified, the error message issue is fixed.
	- API gateways - search field issue is fixed.
	- Comparison method violates its general contract issue - fixed.
	- Report coverage page showing empty with one endpoint issue is fixed.

## APIsec - January 13th, 2023


!!! abstract "Improvements"

    - On Summary page - Environments dropdown added.
    - Text enhancement and alignment in PenTest report.

!!! success "Fixes"

    - Summary report - download issues fixed.
    - Uploading CSV file in RBAC issue is fixed.
    - Search field on the categories tab is fixed.

## APIsec - January 6th, 2023


!!! tip "Features"

    - Notification is added for integration status.![notification](https://user-images.githubusercontent.com/105206963/210976328-ac80239e-f801-4cec-b571-d0e1e0bfa3af.png)

!!! success "Fixes"

    - Apigee SAML Authentication issue fixed.
    - Authentication Table issues fixed.

## APIsec - December 30th, 2022


!!! abstract "Improvements"


    - Search feature introduced at vulnerabilities list page.
    - OKTA settings can be accessible from the integrations Tab.
    - UX is improved across the RBAC category.

!!! success "Fixes"

    - Scan failing at endpoints is fixed.


## APIsec - December 22nd, 2022


!!! tip "Features"

	- Org level integrations introduced.![Screenshot 2022-12-22 223521](https://user-images.githubusercontent.com/105206963/209333874-05d4797f-be81-4fe2-9c11-c9b31c47a8fb.png)

!!! abstract "Improvements"

  - Overall performance improved.
	- Vaults section is moved to profile menu.![Untitledvault](https://user-images.githubusercontent.com/105206963/209281392-32c721fc-8e6e-4671-b5e5-4c2078c21c06.png)


!!! success "Fixes"

	- Categories page throws an error issue is fixed.
	- Postman host setting issue is fixed.
	- Exception when no auth items in postman collection issue is fixed.
	- Support of project creation for postman collection issues is fixed.
	- Bugs across the vaults section are fixed.

## APIsec - December 8th, 2022


!!! abstract "Improvements"


  - Performance improved at landing page.
	- Added help text for injection and stored injection category.
	- Messaging and hover text improved at various pages for null data.
	- Org name column added in "other private scanners" page.
	- All xlsx and Excel extensions are replaced with CSV extensions.
	- Confirmation dialogue box added after inactive project category.

!!! success "Fixes"

	- Search field at the security categories page is fixed.
	- Sorting at the vulnerabilities page is fixed.
	- Low severity added at various places


## APIsec - December 1st,2022


!!! tip "Features"

	- Download All API's feature added under vulnerabilities Action Section.
	- Added Last-Ping column to Scanners page.
	- Scanner page - Non Apisec Scanner tab Added and all Scanners views for Super Admin

!!! abstract "Improvements"

        - OAS Url added to EthicalCheck Executive summary Report.
	- Sort by category made case INSENSITIVE.
	- Download project Endpoints links moved to the top of the page instead of bottom.

!!! success "Fixes"

	- Manage ADOS dialog window fixed and Sorting Added.
	- Vulnerabilities-detail page redirecting to playbook and pagination issues fixed.
	- The Success rate issue on the scan details page is fixed.

??? note "Note"

	- Private Scanners will need to be refreshed.



## APIsec - November 16th, 2022

!!! danger "Security"

	- 2FA Implemented at Org Level.

!!! tip "Features"

	- CI/CD Integration - drone integration introduced.
	- Search Categories by tag and Name added.

!!! abstract "Improvements"

	- Improvements at Auth Test dialog Table, Help texts and Error messages.
	- Postman v10 support added for APIs in Postman-APIGateway.
	- 500 status added to all categories for FP/FN.
	- Flag added to org Vulnerability download endpoint.
	- Project list Tiles view - Base URL added.
	- Vulnerabilities section added on dashboard.
	- EthicalCheck email body and signature and text improved.
	- Maintenance window footer link added and updated.(https://docs.apisec.ai/maintenance-window/)
	- Project config - OWASP9 & OWASP10 added in compliance categories.
	- Auto Pilot - Improvements and Generate playbooks job implemented.
	- Sorting on Global Vulnerability table implemented.
	- Logs Added to wrike IT service.
	- All project vulnerabilities download is restricted to users(Role Basic).
	- Global dashboard vulnerabilities graphs displayed as scan graphs.

!!! success "Fixes"

	- Log4j Variable injection fixed.
	- Categories Display names fixed.
	- Free account - Unauthorized error is fixed.
	- 405 Errors due to empty variable replacements in url fixed.
	- Insecure cookies Category missing in scan window fixed.
	- Private Security Category Edit - User Authorization Fixed.
	- Pagination retaining issue fixed.
	- Notifications page toggle issue fixed.
	- No property found issue fixed.


## APIsec - October 27th, 2022

!!! danger "Security"

	- Injections in Scans - Fuzzing one property at a time.

!!! abstract "Improvements"

	- Ethical Check minor improvements.
	- Project list page - vulnerabilities view improved.
	- Integrations improved.
	- Environment edit page improved.
	- Messaging improved at the scanner page.

!!! success "Fixes"

	- Authentication Exploit (SQL) - Invalid assertion fixed.
	- Low severity on saving security category is fixed.
	- Delete/Archive issue fixed by disabling the button.
	- Minor fixes on the vulnerability page.
	- Project configuration - resync issue fixed.
	- Org vulnerabilities Download error is fixed.
	- Digest Auth issue fixed.


## APIsec - October 19th, 2022

!!! tip "Features"

	- Vulnerabilities view at Org level initiated.

!!! abstract "Improvements"

	- Messaging improved at various sections.
	- Ethical check Free &  Ethical check  Pro reports improved.
	- Add Endpoint minor improvements.
	- Added date comparison support in assertions.
	- Scans Schedule on weekly or monthly added.
	- Added documentations:
	   Getting OAS for an API from IBM DataPower,
	   JupiterOne IT integration,
	   Linear IT integration,
	   Wrike IT integration.

!!! success "Fixes"

	- Playbooks count on the scan history page is fixed.
	- Custom categories name updated.
	- Custom generator pages -  Assertion syntax OR fixed.


## APIsec - October 12th, 2022

!!! tip "Features"

	- Sftp - Storage Account.

!!! abstract "Improvements"

	- UI Flag Added to show endpoint was added manually.
	- Messaging improved at various sections.
	- PenTest and Ethical check reports improved.
	- Add Endpoint UI improvements.
	- Postman API Gateway - Fetch APIs/Collections based on workspace ID improved.
	- Cookies evaluation support added.

!!! success "Fixes"

	- Propagate Payload issue fixed.
	- obfuscating value from request headers in wirelogs fixed.
	- summary report - All vulnerable endpoints display & count in the table fixed.
	- Re-sync issue fixed.
	- Jupiter one IT fixed.
	- The TLS Headers/CORS category not visible in the scan window is fixed.
	- Save and reload spec issue fixed.
	- Propagate Assertions issue fixed.
	- Access control on "Org Activities" for User profile is fixed.

??? note "Note"

	- Private Scanners will need to be refreshed.


## APIsec - September 27th, 2022

!!! danger "Security"

	- TLS - Cryptographic protocol designed to provide communications security.

!!! tip "Features"

	- Download all projects Endpoints added.

!!! abstract "Improvements"

	- Reading Credentials from the postman collection improved.

!!! success "Fixes"

	- Project list - Persist last visited pagination fixed.
	- Developer Report - Vulnerabilities count in Active Vulnerabilities table fixed.
	- Propagate Assertions and Headers fixed.
	- ApiGateway - APIGEE projects register - fixed.
	- Minor UI fixes at footer and Scan summary.
	- CVSS Score below 3.9 marked as low severity - fixed.
	- Filter by task in profile activity is fixed.
	- Domain name at Auth and jupiter one issue tracker issues fixed.


## APIsec - September 20th, 2022

!!! danger "Security"

	- CORS category updated.

!!! tip "Features"

	- New API added to Re-Sync Project category with Org category.
	- Add Endpoint to API spec.
	- EthicalCheck Pro Launched.

!!! abstract "Improvements"

	- Messaging improved for propagations, snack bar and archive.
	- Invalid Base url warning improved.
	- Pentest and Developer minor improvements.
	- OKTA enabled org messaging improved.
	- CI/CD script improved.
	- Documentation updated for new playbook.

!!! success "Fixes"

	- Active and inactive bug for integrations fixed.
	- Creating a new profile bug fixed.
	- Postman API Gateway Fetch API/Collections bug fixed.
	- Search security categories issue fixed.
	- Minor Linear IT fixes.
	- PenTest and Developer minor fixes.
	- Global dashboard closed vulnerability count fixed.
	- New user unable to login with OKTA SSO issue fixed.
	- Vault page - rows are showing blank issues fixed.
	- Sync all issues fixed.


## APIsec - September 12th, 2022

!!! danger "Security"

	- PII Category added, it checks if Personal Identifiable Information is revealed through this API response

!!! tip "Features"

	- Linear Issue Tracker integrated.![LinearIT](https://user-images.githubusercontent.com/87167471/189995572-0346d487-458c-443b-8a34-ab939a125758.png)


!!! abstract "Improvements"

	- Messaging improved at Org member adding.
	- Messaging added on empty tables.
	- Search added for public categories saved as draft
	- Header Variable injection path processing
	- Improved logging
	- @plaintext added, PII Generator improved

!!! success "Fixes"

	- Fixed multi email issue.
	- Linear IT fixes


## APIsec - September 7th, 2022

!!! danger "Security"

	- CORS - False Negatives Added.

!!! tip "Features"

	- Add Endpoint to API spec via API.

!!! abstract "Improvements"

	- Messaging improved at Org member adding.
	- Validating Scanner status on playbook edit and scan trigger dialog window.
	- Homepage - Search field kept populated unless cleared.
	- API's are also being fetched in Postman API Gateway.
	- Security Categories info is linked from the reports section.
	- CI/CD & Github Actions Scripts updated.

!!! success "Fixes"

	- Search bar not working for saved draft categories is fixed.
	- User add - email validation is fixed.
	- CI/CD-Jenkins script fails for a Project name with empty space issue is fixed.
	- Search private security categories are fixed.
	- Email validations at signup and Org pages Added.
	- The User name accepting special characters is fixed.
	- Billing email field accepting invalid email id's is fixed.
	- Existing email restricted from creating an account.
	- Developer Reports - Wirelogs height issue fixed.
	- API Gateway - Register Dialog UI and duplicate name issue fixed.
	- Project configuration console error fixed.
	- New playbook - Playbook special character is fixed.
	- Pagination issues fixed.
	- Console error is fixed for CORS category.

??? note "Note"

	- cloud.fxlabs.io is redirected to cloud.apisec.ai
	- APIsec cloud is migrated to modern Kubernetes architecture.


## APIsec - August 29th,2022

!!! tip "Features"

	- "Wrike" issue tracker Integrated.![wrike](https://user-images.githubusercontent.com/87167426/188198360-e297f75f-cc9d-4764-881a-2dddbe3c00f2.png)


!!! abstract "Improvements"

	- Org Pages - Name and Email Validations have been improved.
	- Forthcoming Org Monthly Reports will be sent via SendGrid.
	- Improvements in form validation and environment base url validation at issue tracker pages and environment page.
	- Messaging improved for 400 status codes.

!!! success "Fixes"

	- Environment edit - console error is fixed.
	- API Gateway issues are fixed and credentials are being validated using the Test button.
	- Long variable value not able to be saved issue fixed.
	- Search field is kept populated unless it's cleared at the project Category section.
	- Environments Duplicate Authentication is fixed.


## APIsec - August 24th, 2022


!!! info "Academy"

	- APIsec Univeristy Launched.(https://university.apisec.ai/)

!!! danger "Security"

	- We have added new CORS Security Categories to find signs that your API server is extra vulnerable to Cross Site Scripting attacks. Improperly setup CORS policies will allow an attacker to redirect one of your users to your API with their credentials and impersonate them for further attacks. Here's a helpful link for more information on the security concerns of improperly configured CORS policy : https://portswigger.net/web-security/cors
	- Help text added to the Custom header category.![Help text](https://user-images.githubusercontent.com/87167426/186986277-a685b3e7-e950-4965-b74c-420c2381d168.png)

!!! tip "Features"

	- "JupiterOne" issue tracker Integrated.![jupyter 1](https://user-images.githubusercontent.com/87167426/186985659-65ef8f73-51f0-4487-ad47-a11a4d457729.png)

!!! abstract "Improvements"

	- Footer links updated.
	- Pentest Report improvements for Ethical Check.
	- Messaging at various sections has been improved.
	- APIsec Monthly Report Improved.
	- Added Postman set up documentation.

!!! success "Fixes"

	- Report Storage in clouds fixed.
	- API Gateways SpecAutoOnboarding fixed.
	- Pagination issue fixed in org list.
	- Issue Tracker links and url's fixes.
	- Error icon added in status section of playbooks page.
	- Login restricted to inactive tenants is fixed.
	- Playbook page toggle button fixed.
	- For private Security categories, search restricted to tenants is fixed.
	- Minor fixes at Project lists page.
	- Validating base url of environment on environment edit, project dashboard, playbook pages fixed.
	- API Gateways minor fixes.
	- Orgs API fixed.

??? note "Note"

	- Ethical check (free pentest) website also improved.(https://www.ethicalcheck.dev/)


## APIsec - July 25th, 2022

!!! danger "Security"

	- CICD-Powershell script and documentation updated.
	- Tenant Admins can now Create,Edit and Delete Security Categories within the same Tenant.

!!! abstract "Improvements"

	- Project registration on API Gateways page improved
	- Backend Sorting improved at various sections.
	- In the Developer Report Wirelogs Section made clickable from vulnerabilities table.
	- Password policy added for API calls for signup & reset.
	- Added categories as optional query param in runByProject API
	- Added error message for runByProject API
	- Messaging has been improved at various sections,

!!! success "Fixes"

	- Pentest, Developer and compliance reports fixes.
	- All projects toggle disabled for the project manager.
	- Playbooks page hidden columns fixed on tab resolutions.
	- Security researchers add in collaborators is fixed.
	- Github invalid url & sync all issue fixed
	- Responsive Fixes of Internal Project Dashboard
	- Add Collaborators to project fixes.
	- Postman Basepath Extraction fixed.
	- HMAC auth URL fixed
	- Jira issue tracker validation & duplicate issue logging fixed.
	- Scanner name edit Disabled.
	- API Gateway -- MuleSoft Business Group issue fixed.
	- Project Entitlements - fix
	- Dashboard page - Scan graph box alignment fix
	- Propagate Headers fixed.
	- private scanner page - copy to clipboard on new scanner and owner column is empty issues are fixed.
	- Project Owner - collaborator Fixed
	- Project dashboard page - dropdown button click issue fixed.
	- No runs found , 500 error msg fixed
	- On signup password hide was not working issue fixed.
	- Remediation sections and closed vulnerabilities Repeat issue in the Pentest and Developer report are fixed.
	- API Gateways Spec Auto On boarding issue fixed.


## APIsec - June 13th, 2022

!!! danger "Security"

	- Strong password policy implemented across the product.![Screenshot from 2022-06-15 00-21-34](https://user-images.githubusercontent.com/87167426/173896604-7d363e81-8334-4f5f-9948-4fcf882bc85f.png)
	- SendGrid integration: All the org monthly emails will trigger via SendGrid to the customers.

!!! tip "Features"

	- A new version of developer and compliance report launched.![Screenshot from 2022-06-15 00-27-28](https://user-images.githubusercontent.com/87167426/173896865-4b5c5eab-1052-48e9-a83e-0afa6298ba4e.png)
	- Skip ABAC: This option during project registration prevents identification of ABAC resources used for generating ABAC Playbooks.![Screenshot from 2022-06-15 00-30-01](https://user-images.githubusercontent.com/87167426/173896977-6050e971-1cdf-44f9-a4be-33942aba4292.png)

!!! abstract "Improvements"

	- Improved the Refresh button on the Playbooks tab (It refreshes the list of playbooks on the current page).
	- Revert the changes on the Authentication Exploit(SQL) category to generate playbooks for all endpoints.
	- Credentials field is set to optional in the advance project registration page. The user can enter and test the credentials from the 		           environments.
	- Project creation/deletion messaging improved in API gateway.
	- Improvements on the login page.
	- Help text improvements in various pages.
	- Search bars and dialog windows improved.
	- Backend sorting Improved for a few of the tables.
	- CICD-Jenkins job scripts improved.
	- Spec upload on project details page improved.
	- While uploading the project the text option was made read-only.

!!! success "Fixes"

	- All project data to excel-sheet download on the dashboard fixed.
	- Alignments fixed on the landing page.
	- Issue tracker validations and links fixed.
	- Injections data load fixed.
	- Category numbers in the summary report are accurate now.
	- Slack notification url fixed.
	- First scan shard error fixed for the fresh environments.
	- Variables page was listing duplicate download csv links, fixed now.
	- Text overlapping on the landing page is fixed.
	- Pie chart on project dashboard issue fixed.
	- Invalid scanner name in training profiles fixed.
	- The console error on the project details page is fixed.


## APIsec - May 10th, 2022

!!! danger "Security"

	- Authentication roles set to inactive are now restricted to scan the test results.

!!! tip "Features"

	- False positives in the unsecured category are now identified by Artificial Intelligence. AI can learn and analyse vast amounts of data in the blink of an eye.![unnamed](https://user-images.githubusercontent.com/87167426/167991704-5c3d8c72-3c64-49e5-85a0-b201a3c78a26.jpg)


!!! abstract "Improvements"

	- HMAC help text improved.
	- Issue trackers are now easy to access via the dropdown menu.
	- Messaging improves when data is empty on the dashboard, profiles and scanners table.
	- Sorting improved on the vulnerability details table.
	- Summary and detailed report info displayed via snackbar, messaging improved.
	- Playbook count reduced for authentication categories.
	- CI/CD helptext improvements.
	- Init and cleanup playbooks added to match playbooks count.
	- Improvements in the paginations.
	- Improvements in the performance.

!!! success "Fixes"

	- Overlapping of text in org list page and scan details page fixed.
	- Typos in playbook management, CI/CD and password reset page fixed.
	- Alignments for free users are fixed.
	- Search bar and empty table issue fixed on landing page.


## APIsec - April 19th, 2022

!!! danger "Security"

	- RBAC scan to use random UUIDs instead of variables for DELETE endpoints.
	- Supporting '*' wild card for partial header name search in RateLimit categories to check for any header starting with X-RateLimit.
	- APIsec is now supporting HMAC auth type.

!!! abstract "Improvements"

	- Improved save & sync functionality.![image (11)](https://user-images.githubusercontent.com/87167426/164306965-b30851fc-b361-4183-8387-d663f7435662.png)

	- CI/CD integration is now easy to access via the dropdown menu.![image (12)](https://user-images.githubusercontent.com/87167426/164307007-b1c6a5f4-3aaf-4879-bc94-b9a2d2d6c19f.png)

	- Scan dialog window improved for category selection.
	- Category names made user-friendly in the playbooks list page and open vulnerabilities on the dashboard page.
	- Project list view improvements on landing page.


## APIsec - April 11th, 2022

!!! danger "Security"

	- 301 Moved Permanently status code now marked as false positive.
	- Free users are now restricted to access summary reports.
	- API to get Vulnerabilities by Scan.

!!! tip "Features"

	- Tiles revamp on scan detail dashboard.![image (8)](https://user-images.githubusercontent.com/87167426/163156103-dd0bf59a-8e15-471e-929f-6f478ca56acd.png)

	- Review comments added in the vulnerability details page.![image (9)](https://user-images.githubusercontent.com/87167426/163156195-e70d2091-6f73-420a-96e1-d43e6725c604.png)

	- Projects on the dashboard can be switched to list view.![image (10)](https://user-images.githubusercontent.com/87167426/163156240-a1f59d01-6245-4318-a5a7-1246f9b2071e.png)

	- AWS Fargate Instructions added in release notes and scanner register page.![image (2)](https://user-images.githubusercontent.com/87167426/163153294-15b41efb-1a7c-48cd-af85-048986725c84.png)

!!! abstract "Improvements"

	- Invalid base url shows an alert and does not allow submitting the scan.
	- First and last navigation buttons added on the project list and scan details page.
	- Improvements in open vulnerabilities details table.
	- Inactive roles will be automatically removed from the RBAC map.
	- Register API gateway and cloud scanner tiles replaced with a button.
	- Unauthorized message on status code 403 for the USER role.
	- Help text improved in the vault for report storage.
	- Overall performance Improved.

!!! success "Fixes"

	- Report Storage, Notification and Git backup: the toggle button made active by default.
	- Replaced cancel button with Yes and No in the scan history page.
	- Tooltip updated on scan history and org list page.
	- Injection string org owner fix.
	- Pentest report TOC Missing 'UNmeasured' fixed.
	- Project register through advance section fix.
	- In the scan history page, profile activities and activities list page navigation fix.
	- Enabling space in edit project name from details page fix.
	- Clearing bulk add field on click of cancel button fix.
	- Summary report:  owasp coverage table values, severity column and vulnerabilities count issue fixed.
	- API register via file upload fix.
	- Beta tags removed from APIGateways and Ideabiz icon added.
	- Alignment fixes in the register scanner page.
	- Project activity page dialog fixes.
	- Environment auth delete and bulk add issue fixed.
	- Injection categories issues fixed.


## APIsec - March 22nd, 2022

??? note "Note"

	- This release has code changes in bot, please ensure to refresh the private scanners.

!!! danger "Security"

	- API Gateway - Region and session token added to AWS.
	- Authentication - Digest authentication type introduced.

!!! tip "Features"

	- Monthly Org Reports will be shared with Org owners on the first of every month. This report provides test executions of the past month.![monthly org](https://user-images.githubusercontent.com/87167426/160037891-ce89b0cb-c849-43a4-ad57-994d09c2a073.jpg)
	- Dashboard tiles revamp: It's all about new trends and making them simplify for our customers.![revamp](https://user-images.githubusercontent.com/87167426/160037982-141ccc07-2ef6-41a4-823e-23e4d738b57a.png)
	- Release Notes: Check out the new release notes integrated into GitHub with security updates.![release notes](https://user-images.githubusercontent.com/87167426/160038054-b4669c67-ceca-44cf-bbf9-9837ecec8800.jpg)

!!! success "Fixes"

	- Summary Report Page enhancements.
	- Session timeout message improvement.
	- Pentest Report Enhancements in intro and background.
	- Performance Improved throughout the product.
	- Save & Rewrite playbooks showing incorrect entity type in activities fix.
	- When a full RBAC map is generated, the header checkbox should also be checked for the roles.
	- Project activities entity type fix.
	- Add invalid scenario in ABAC fix.
	- Redirect from playbook to payload window in project activities fix.
	- Playbook edit window size fix.
	- Snackbar message improved in Scanner Deployment.
	- Playbook name in activity wirelog window fix.
	- Toggle button in playbooks page fix.
	- Project activities page sync event user missing issue fix.
	- Closing playbook window quickly after propagating button click.
	- Added special character restriction to API project name under project details page.
	- Request license url link in new project fixed.
	- Upgrade dialog fix, if the user type is basic.

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

	- Notification feature launched: Track all the required product information (e.g. project credentials not working etc).
	![notification](https://user-images.githubusercontent.com/87167471/158940604-51ea4f52-e057-4946-b262-4552dbecc064.png)

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
