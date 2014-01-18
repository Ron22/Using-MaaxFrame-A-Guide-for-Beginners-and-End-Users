# Setup MaaxFrame

This section tells you how to take the next steps by outlining the key areas to begin setting up MaaxFrame, including:

* Company profile
* User access and permissions
* Customization
* Adding users
* Importing data

---

## Set Up Your Company Profile

The company profile information determines basic settings related to time zones, language, and how the fiscal year is defined. You can leave the default settings as is; however, it’s important to know where to find and change this information.

* Company profile – These settings use your local time for setting the time zone, default language, and the default currency.
* Fiscal years – The fiscal year definitions are used in reporting, opportunities, and forecasting. The default fiscal year setting is a 12-month calendar year, with the first day of the fiscal year starting on any first day of the month. However, you can choose custom fiscal year periods.

![](img/company.PNG)

---


## Establish User Access and Permissions

There are some key components that determine users’ access to data as well as what they can do with the data they have access to.

### Data Access

When setting up MaaxFrame for the first time, you need to make some decisions about who will have access to what data. In MaaxFrame, there are four ways to control data access:
  
* ***Organization-wide defaults*** – Configure the baseline access users will have to your data.
* ***Role hierarchy*** – Determine the level of visibility users have to data.
* ***Sharing rules*** – Extend access to data if you’ve restricted access through your organization-wide defaults.
* ***Manual sharing*** – Provide the flexibility to allow record owners to manually give access to other users.

#### Organization-Wide Defaults

These settings, which determine the default level of data access for different types of information, are referred to as “organization wide defaults.” These include:

* ***Private*** – Users can access (view and edit) their information and that of those below them in the role hierarchy.
* ***Public Read Only*** – Users can view all data, but can edit only their information as well as that of those below them in the role hierarchy
* ***Public Read Write*** – Users can view and edit all data

For smaller organizations, we recommend granting at least Public Read Only access to create a collaborative working environment.

Examples:

* To allow all users to see everyone’s accounts, but not everyone’s opportunities, set access for account records to Public Read Only and for opportunity records to Private.
* To allow the operations team to calculate commissions, they need to see opportunities. However, you don’t want them to edit the opportunities. To allow read-only access, set opportunity records to Public Read Only.
* To set up organization-wide-defaults, please refer to our techincal guide.

For an overview of user access and permissions, view our Techincal Guide : Setup.

#### Role Hierarchy

The role hierarchy looks similar to an organization chart, but it has a different purpose. Because the role hierarchy is based on who needs to work with what data to do his or her job, role hierarchies usually have fewer layers and the people at the top are not necessarily those at the top of the org chart.

![](img/access.PNG)

The person in the top role (i.e Admin) has full access (view ,edit and delete ) to his or her data as well as the data of anyone lower in the hierarchy. Two common ways to set up role hierarchy are by region or by product.

There are three basic steps to setting up a successful role hierarchy:

1. Define the basic roles, such as sales representative, director of sales, and CEO. It’s not necessary to create individual roles for each title; the idea is to simply define a hierarchy that gives users in higher-level roles access to the information entered by users in the lower-level roles.
2. Build the role hierarchy based on how information should roll up for reporting and on who should see what data.
3. Assign individual users to the roles.

### Sharing Rules

Sharing rules let you make automated exceptions to your organization-wide defaults for particular sets of users, so you can give them access to records they don’t own or can’t normally see. Sharing rules, like role hierarchies, are only used to give additional users access to records—they cannot be stricter than your organization-wide default settings.

![](img/sharing_rules.PNG)

### Manual Sharing

Sometimes it’s impossible to define a consistent group of users who need access to a particular set of records. In those situations, record owners can use manual sharing to give read and edit permissions to users who would not normally have access to the record. Although manual sharing isn’t automated like sharing rules, it gives record owners the flexibility to share particular records with users that need to see them.

#### Permissions

Profiles control what users have permission to do with the data they have access to, and how they view the information.Please refer to our technical guide.

#### Understand Profiles

A profile is a collection of settings and permissions that defines how users with particular profile access records, how they see their data, and what they can do within the application. For MaaxFrame Premium Editions, you can use the standard MaaxFrame profiles but you can’t create custom profiles. Even so, it’s important to understand profiles and how they work together with the organization-wide defaults and the role hierarchy. The most important profiles include:

* System Administrator – Can configure and customize the application
* Standard User – Can run reports and create and edit records


When you add users as you prepare to go live, you will assign one of these profiles to each user.

---

## Customization

When you sign on with MaaxFrame, it’s ready to use as is. But you can also easily modify MaaxFrame so that it’s an even better fit for your business and your users. In fact, the more you customize the application to fit your specific users, the more comfortable they’re likely to be—and customization can do great things to boost your adoption rates.


In this section, you’ll learn about customization and get links to step-by-step procedures for making MaaxFrame your own.

* Customization tips & tricks
* What can you customize
* Whether to use the lead functionality
* Capturing leads from your website

### Use Customization Tips & Tricks

Customizing MaaxFrame is so easy that there’s a tendency to create lots of fields that end up not being used. For that reason, it’s important to take a step back before you dive in.

Here are the top five things to think about before starting to customize:

* ***Think before you build*** – Start with the end in mind by identifying your end goal. Think about what information you want to pull out of the system, and then make sure you have the fields to match. At the end of the day, MaaxFrame is only as good as what’s in your reports.

* ***Ask for input*** – Talk to your users to find out what’s critical for them to know. Then capture that information to run your business.

* ***Seed and grow*** – Start with the basic fields you need and then identify new fields that could make your business run even better. This approach ensures you don’t turn off your users.

* ***Run reports*** – Run reports about one month after you go live to find out which fields are not being used. Use the opportunity to survey users about what could be improved.

* ***Make changes on the fly*** – In response to feedback, make changes immediately to gain instant credibility. Make sure you communicate any changes, because users don’t like it when anything that affects their work happens “magically.”

### Know What Can You Customize

You can customize many different MaaxFrame components; however, most customers customize three things:

* Fields
* Page layouts
* Reports

#### Customize Fields

Because fields hold the data you want to capture and report on, it’s important to make sure you have fields for important data elements and that those fields have names that make sense to your users. Here are common approaches to customizing fields:

![](img/field.PNG)

* Modify the standard MaaxFrame fields – MaaxFrame provides commonly used fields for standard records such as accounts, contacts, opportunities, and leads.
  * For example, the Lead object has a standard field called “Lead Status,” which has existing values of “Attempted to Contact,” “Cold,” “Hot,” "Pre-Qualified," "Warm," and few more. You can easily add a new value called “Dukewarm.”
* Create fields from scratch – If a standard MaaxFrame field that you need doesn’t already exist, you can easily create a custom field. For example, you can add a new picklist to capture “Lead Type” and track the main competitor in the sales cycle.
* Do both! Combine standard fields and custom fields to create the best experience for your users.

#### Customize Page Layouts

Page layouts define how fields—standard and custom—look to your users and which fields are required; that is, they can’t be saved unless the user enters a value. You’ll want to customize your layouts so that they’re attractive and easy to use. It may be tempting to create many required fields to force users to enter data; however, keep in mind that user satisfaction tends to suffer when there are too many required fields.

![](img/layout.PNG)

Here’s what you can do to customize page layouts:

* Remove unnecessary fields
* Change field locations
* Create new sections
* Determine if filling in a field is required before saving

#### Customize Reports

* Being able to easily generate reports containing the information that’s most important to you is one of the great things about MaaxFrame. With a large number of standard reports available out of the box, you can be reporting in no time.

* In the planning process, you determined what information you would need to pull from MaaxFrame based on your current business needs. Then you customized the application based on those needs.

* After you add the custom fields to MaaxFrame, it’s time to re-evaluate if you have all the information you need to pull the proper reports.

![](img/reports.PNG)

Now you’re ready to start creating your reports. Here’s what you can do with reports:

* Customize the standard reports to better fit your business needs.
* Create custom reports from scratch and determine which fields they contain, how they’re laid out, sorting options, date ranges, and charting options.
* Leverage pre-built dashboards that contain all the underlying reports tied to the dashboard.

### To Lead or Not to Lead?

An important step in setting up MaaxFrame is to decide whether or not to use lead functionality. Leads are a critical part of the sales cycle of most businesses, and MaaxFrame includes a lot of very useful lead functionality, such as analyzing how leads convert or finding your best channels. Some companies decide not to use lead functionality because it requires an additional step to turn a prospect into an opportunity. What's right for you depends on your business processes.

![](img/leads.PNG)

#### Take Advantage of Lead Functionality

Leads are unique among MaaxFrame records because they come with special functionality, including:

* ***Lead Conversion*** – A benefit of using leads in MaaxFrame is that it creates a separate area in which you can keep information in any kind of format to track anyone who ever expressed interest. This approach keeps a clean distinction between leads and contacts, so you don't have to worry about “dirty” data or duplicates. If you don't use leads, you can't run an analysis of how leads convert or the best channels for creating leads.
* ***Reports*** – Available reports show conversion rates, the time required to convert a lead, and lead channels that are the best performers when it comes to bringing in deals.
* ***Web-to-Lead*** – Getting leads from multiple channels is critical to any business. By using the Web-to-Lead functionality, you can easily create forms that capture leads from your website.

To learn more about leads, take a look at our tip sheet within the Help & Training portal refer to our techical guide.

### Capture Leads from Your Website

If you have decided to use leads, it makes sense to also evaluate the Web-to-Lead functionality. You probably have a website that lets prospects contact you te your product or service.

![](img/lead_website.PNG)

To make the most of your website:

* Customize MaaxFrame to use Web-to-Lead functionality to capture leads when prospects fill in a form.
* Bring that information right into MaaxFrame.

Setting up this functionality is as simple as deciding which fields to include on the Web-to-Lead form, creating a URL as a landing page (such as a “thank you” page), and clicking a button to generate the HTML code. Your webmaster will jump for joy when you deliver HTML code that's ready to deploy immediately.

## Add Users

When MaaxFrame is set up the way you want it, you're ready to add users.

Adding users is a fairly easy task. Earlier we covered profiles and setting up your organization's role hierarchy. When you add users, you associate actual users with those profiles within your role hierarchy, so users can log in and access the data that's appropriate for them.

![](img/add_users.PNG)

Adding users serves three important purposes:

* Once you add users, you can import data and automatically associate that data with the correct users.
* By associating roles and profiles with all users, you can determine how they see data, what they can do in the application, and how their data rolls up.
* When you add a user, MaaxFrame uses that user's record to generate an invitation to log into the application.

> Tip: If you want to notify users to reset password, be sure to “Reset New password” button when you go through the process of adding users. And then You can edit the user records and generate usernames and passwords whenever you're ready for users to actually log in.

## Import Data

The final task before you're ready to go live is to import your data into MaaxFrame. To help you, MaaxFrame has wizards to walk you through the process and provide some tips along the way. When the import is complete, you're can start to train your users and announce that MaaxFrame is ready for business.

> Note: This import step is probably the most complex task in any other platforms bur not in MaaxFrame , it's ease to use.

Most companies already have account and contact information stored somewhere—usually in Act!, Goldmine, or Microsoft Outlook, as well as in spreadsheets, on sticky notes, or in the heads of their sales reps. Getting that information out of Outlook and off the sticky notes and into your organization's knowledge base is one of the most important steps in the implementation process.

![](img/import.PNG)

Although you could collect all these resources and enter them one by one, it's obviously not efficient to enter hundreds or even thousands of records by hand. MaaxFrame provides a step-by-step data import wizard that walks you through the process of importing leads, accounts, and contacts.
 
### Prepare to Import Your Data

Best practices for importing your data include having a well thought-out plan, properly preparing the data, and doing a test run.
Planning your data import includes the following steps:

* Identifying your data sources data sources: Is your data in spreadsheets?
* Listing fields in your current data records.
* Mapping your current fields to the MaaxFrame fields.

### Prepare Your Data

We suggest you “scrub” your data before importing it into MaaxFrame because starting with clean data really pays off. Remember: “Garbage in, garbage out.”

Here are some tips for preparing your data:

* The MaaxFrame import wizard was designed to work with Microsoft Excel. If necessary, export your data from any other data sources to Excel first.
* Now is a good time to standardize naming and clean up your data. For example, set standards for company names (such as International Business Machines instead of IBM) or the way countries are listed (USA instead of United States).
* Take time to weed out “dirty” data and de-duplicate people who may be in the system multiple times.
* Review your Excel file to see if you missed any critical data elements for which you haven't yet created custom fields. For example, if your sales reps are tracking the number of employees at each account, you'll need a field to store that information in MaaxFrame.
* Map your data columns to the  MaaxFrame field names. For example, the Company field in Microsoft typically maps to the Account field in MaaxFrame. Consider renaming the column headers in your Excel file so they match the field names in MaaxFrame exactly. This step will simplify the mapping step in the wizard.
* Wherever possible, assign the correct owners to records. If you don't have all the records assigned, the default owner is the administrator who performs the import.
* Now start importing your data.

![](img/import1.PNG)

Test the import: Test a small sample—approximately 5 to 10 records—before going ahead with the full import. When you analyze the results of your test, try this approach:

* Build a custom report or custom view that lets you see at a glance whether the data is laid out correctly.
* Open a record and compare it against the import file. Confirm that the record's fields show what you want them to show.
* Validate the test results with selected stakeholders or power users.
* Make changes to the import file or make changes to MaaxFrame based on the test results. For example, data could import incorrectly because it was mapped to the wrong field.
* Delete the test records and test again after making your changes. Repeat this process until you're sure the data was imported accurately and that it is displayed correctly in the reports and views your users will see.

### Import Your Final Data

Once your test results meet your expectations, you're ready to import your file or files. Here are a few suggestions for importing data:
* Consider importing data during non-working hours – If the system is live for some groups before others, this approach helps avoid confusion.
* Give yourself some cushion for error – Don't try to import your data the day before sales training, for example.
* Validate your data – Run key reports and display important screens to make sure all the data was imported into the fields where it belongs and in the format you want.