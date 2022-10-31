# FluentCRM-DateTrigger

FluentCRM as a WordPress CRM lacks a date trigger for automation. This function determines if today is a date that should trigger an automation in FluentCRM and then adds a Tag or List to the contact. This can then be used to start an automation in FluentCRM. The function hooks into the WP-cron because it is not time critical. For the time being it should run during night or a time when only few users are active on the site to avoid any performance issues. This planned to improve in a future version. It is meant to run via Advanced Scripts/Scripts Organizer/Code Snippet or functions.php. It is not a plugin.

*This is BETA.*

Although, FluentCRM now has a birthday function. It works for just that, birthdays. With this solution you can also apply the functionality to other datefields.

## Install

Add the code to your functions.php or Scripts Manager

For convenience you can simply import the json file from this package into Advanced Scripts. 

## Setup

Change the following details according to your set up:
  - $listIds -> Set the IDs of the lists that are subject for setting the trigger tags
  - $tagIds -> Set the ID (only one!) that is used for the automation to kick off

Create an automation in FluentCRM that looks for contacts added to the tag above.

## Finetuning

You can now set the number of days before or after the birthday to kick in the tag/list.

## Buy me a coffee

If you like this solution and want to thank me, you can buy me a coffee at ko-fi.com/andredaus
I appreciate your support!
