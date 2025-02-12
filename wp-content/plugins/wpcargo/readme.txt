﻿=== WPCargo Track & Trace===

Contributors: WPTaskforce
Donate link: https://wpcargo.com/
Tags: transportation management, status tracking, shipment tracking, order tracking, delivery tracking, tracking system, package tracking, courier tracking, order management, order status, order shortcode, order management system, order tracking system, status tracking system, status tracking software, delivery tracking system
Tested up to: 5.8.1
Requires PHP: 7.0
Stable tag: 6.x.x
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

WPCargo is a track &amp; trace system for courier, courier script, parcel, shipment and transportation management system, ideal solution for freight forwarder, customs broker, balikbayan forwarder, importer, exporter, supplier, shipper, overseas agent, transporter, &amp; warehouse operator.​​ WPCargo helps manage operations, customers, drivers, quotation, form, branch, and employees.

== Description ==

[Main Site](https://www.wpcargo.com/) | [Documentation](https://www.wpcargo.com/knowledgebase/) | [Showcase](https://www.wpcargo.com/features/) | [Premium Addons](https://www.wpcargo.com/purchase) | [Demo](https://www.wpcargo.com/demo-login/)

WPCargo is a WordPress plug-in designed to provide ideal technology solution for your freight forwarding, transportation & logistics operations. Whether you are an exporter, freight forwarder, importer, supplier, customs broker, overseas agent, or warehouse operator, WPCargo helps you increase the visibility, efficiency, and quality services of your cargo and shipment business.

WPCargo helps manage operations, customers, drivers, quotation, form, branch, and employees. The latest version is flexible that can be used and utilised as transport management, project management or other status tracking management system.

= Core Plugin Features =

* Shipment Track Form
* Manage Shipment 
* Shipment Settings
* Search & Sorting of Shipment List
* Email Notification - Client & Admin
* Auto Generate Tracking Number 
* Client Account - shortcode for user created shipment 
* Multilingual Support
* Support Barcode
* Shipment History - track location , date and status of the cargo
* Print Label
* Generate Report
* Multiple Packages

= Premium Features =

* [Fully customizable form fields](https://www.wpcargo.com/product/wpcargo-custom-field-add-ons/)
* [Add Signature in custom field manager](https://www.wpcargo.com/product/wpcargo-signature-add-ons/)
* [SMS Notification](https://www.wpcargo.com/product/wpcargo-sms-add-ons/)
* [Allow user to manage thier shipment](https://www.wpcargo.com/product/wpcargo-client-accounts-add-ons/) - Merge in free version
* [User Front-end Manager](https://www.wpcargo.com/product/wpcargo-frontend-manager/)
* [CSV Import/Export](https://www.wpcargo.com/product/wpcargo-importexport-add-ons/)
* [Online Booking](https://www.wpcargo.com/product/wpcargo-pick-management-add-ons/)
* [Address Book](https://www.wpcargo.com/product/wpcargo-address-book-add-ons/)
* [Proof of Delivery - allow driver or delivery to sign by reciever  and add images as a proof that the cargo has been delivered](https://www.wpcargo.com/product/wpcargo-proof-delivery/)
* Vehicle Manager can assign the delivery to your driver or vehicle - Merge in Proof of Delivery
* [Detrack.com Integration](https://www.wpcargo.com/product/wpcargo-detrack-integration-add-ons/)
* [Branch Manager](https://www.wpcargo.com/product/wpcargo-branch-manager-add-ons/)
* [Shipment Container](https://www.wpcargo.com/product/wpcargo-shipment-container-add-ons/)
* [Multi Receiver](https://www.wpcargo.com/product/wpcargo-multi-receivier-add-ons/)
* [Request Quotes with  Woocommerce integration](https://www.wpcargo.com/product/wpcargo-parcel-quotation-add-ons/)
* [Woocommerce Order Tracking Integration](https://www.wpcargo.com/product/wpcargo-woocommerce-order-integration/)
* Delivery Calculator - Customization
* Collection Point - Customization
* Ability to track shipment from other company (Fedex , USPS) - Discontinue 
* [Shipment Consolidation](https://www.wpcargo.com/demo-login/)
* [Shipping Rates with Woocommerce integration](https://www.wpcargo.com/product/wpcargo-shipping-rate/)
* [POS](https://www.wpcargo.com/product/wpcargo-woocommerce-pos-add-on/)
* [Barcode Reader Status Update](https://www.wpcargo.com/product/wpcargo-receiver-add-ons/)
* [Service API](https://www.wpcargo.com/product/wpcargo-api-addon/)

= Demos =

[View Our Demos](https://www.wpcargo.com/demo-login/)

[View More features](https://www.wpcargo.com/features/)

Contact Skype: arni.cinco

== Installation ==

1. Upload `WPCargo.zip` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently asked questions ==

- How can I add the Pages for Track Form and Track Result?

First thing to do is to create a pages and setup the Track Form and Track Result under the WPCargo Settings->Page Settings

- How can I add options on each fields?

In WPCargo Settings Page add the option that you needed on each fields.(New line on each option)

Example on Add Shipment Status section:

On-Hold,Pending,Delivered

- How to add an Agent?

Add a new user and change the role into "Agent".

- What is the shortcode to use?

Single Page with results:[wpcargo_trackform]

2 Page with results:

[wpcargo_trackform id=page id of results]

[wpcargo_trackresults]

[wpcargo_account] or [wpc-ca-account]

== Screenshots ==

1. All Shipments

2. Track Shipment

3. Shipment Results

== Changelog ==

= 6.8.8 =
- Added filter hook "wpcargo_calculate_weight" to have an option in European decimal compatibility.

= 6.8.7 =

- Fixed European decimal separator.
- Fixed undefined variable of $wpcargo_shipments_update.
- Fixed mobile responsive of package table in wp-admin form.
- Enable google map autocomplete in Parcel Quotation and Shipping Rate forms.

= 6.8.6 =

- Fixed package error undefined function wpcpq_dimension_unit()

= 6.8.5 =

- Fixed package calculation error
- Add new action and filters hooks for the parcel calculation for weights and volumes
- Add volume metric calculation for the FREE version
- Fixed shipment history arranegments and add the shipment history to the last sections
- Fixed errors on the country list options
- Add visual map for the defualt geolocation on shipment history map settings
- Fixed email settings placholder value closing tags error and set defualt value
- Update language translations files

= 6.8.4 =

- Fixed Shipment and Package table mobile responsive in track result template.
- Fixed shipment form fields overlapping
- Add new filter hook "wpcargo_history_order" to customize shipment history order
- Fixed email notification settings for the body and footer form fields value.

= 6.8.3 =

- Add filter for admin and frontend template customization.
- Add filter "wpcargo_client_mail_notification_message" and "wpcargo_admin_mail_notification_message" for email notification message.
- Add hook "wpcargo_after_client_mail_notification" and "wpcargo_after_admin_mail_notification" after email notification.
- Add total volume and weight package information in invoice print template.

= 6.8.2 =

- Fixed email notification template in mobile display.
- Add new filter hooks "wpcargo_shortcode_meta_value" for the shortcode custom meta value.
- Fixed package calculation decimal point with auto detect number of decimal place to display.

= 6.8.1 =

- Fixed package and shipment history data deleted after submission when array value has quote characters.
- Fixed track result no display for labels.
- Fixed "All in One SEO" plugin compatibility, NO result display when track form is submitted.

= 6.7.9 =

- Added new filter hook wpcargo_client_email_attachments to add attachment to the email notification.
- Added new settings for the Restrict Duplicate Shipment Number.
- Fixed email notification NOT sending error on the wp-admin bulk update.
- Fixed Frontend Manager Add on dashboard report compatibility error on single and bulk update shipment in wp-admin page.
- Fixed SMS add on compatibility on bulk updates notification.
- Fixed email notification when shipment assigned shipper is NOT registered.
- Update plugin language translation files


= 6.7.8 =

- Added filter hook for assign shipment email body content.

= 6.7.7 =

- Fixed email shortcode meta "{wpcreg_client_email}" for Registered Client Email mapping error, data not matched.
- Fixed action hook parameter missing on "wpcargo_after_package_row"

= 6.7.6 =

- Fixed email shortcode meta "{wpcreg_client_email}" for Registered Client Email.

= 6.7.5 =

- Update plugin language translation files.
- Introduce new filter "wpcargo_barcode_type" to alter barcode type
- Introduce new filter "wpcargo_barcode_size" to alter barcode size
- Add new default email shortcode meta "{wpcreg_client_email}" for Registered Client Email.

= 6.7.4 =

- Added filter hook for email notification recipients.

= 6.7.3 =

- Added filter hook in exporting shipments meta_query.
- Enabled to override export form template.

= 6.7.2 =

- Fixed - Shipment History Map marker order sequence.
- Enhancement - Allow to focus map view to the last address.
- Enhancement - Add new Map Icon for the last address.

= 6.7.1 =

- Added setting for barcode size and hook.

= 6.7.0 =

- Fixed Google Map history order.

= 6.6.9 =

- Additional hooks for shipments' table actions.

= 6.6.8 =

- Remove Print Waybill text when generating AWB pdf.

= 6.6.7 =

- Notify register client when status is update.

- Additional hooks for custom scripts on Google map and Google autocomplete.

= 6.6.6 =

- Fixed field labels with apostrophes.

= 6.6.5 =

- Fixed jQuery .live function script error

= 6.6.4 =

- Update track result template and add Print Invoice functionality

- Fixed some static text that are not translatable.

= 6.6.3 =

- Update time format to H:i a.

- Update for the shortcode to be called twice in a single page.

- Added translation: Dutch.

= 6.6.2 =

- Update function of multiple package when dimension is disabled.

= 6.6.1 =

- Fixed error on exporting reports.

- Added translation: Chinese(Simplified, China), Hebrew, Macedonian.

= 6.6.0 =

- Fixed Print Invoice template on mobile device.

- Fixed RTL display.

- Fixed Print Invoice packages template on mobile device.

- Display packages data only when enable in invoice template.

= 6.5.9 =

- Fixed error function get_fields_data() undefined in print invoice.

= 6.5.8 =

- Fixed error undefined is_plugin_active function when Frontend Manager add on is deactivated.

= 6.5.7 =

- Add new settings for the print font family and size.

- Update the print invoice template.

- Fixed shipment history error during add new shipment.

- Fixed error in shipment history display when data is not an array.

- Fixed setting metakey error when the array key not exist.

- Fixed shipment view templates pop up for wpcargo shortcode theme compatibility.

- Fixed dimension error for the volume weight calculation.

- Add new settings for the Dimension Divisor for both centimeter and inch metric unit.

= 6.5.6 =

- Update the print invoice template to be able to make it customizable through theme.

- Fixed track result header template display layout.

= 6.5.5 =

- Fixed export shipment error functiona undefined.

- Fixed export data display for Arabic, Cyrillic and Chinese characters.

- Fixed export shipment data label mapping error.

- Change the Print label text into waybill.

- Allow the print waybill template to be customize in themes/theme-name/wpcargo/ directory name under waybill.tpl.php file

= 6.5.4 =

- Fixed settings Display Shipment History in Invoice not working.

= 6.5.3 =

- Fixed error Google Map Marker upload logo not working.

- Fixed error {location} not working in email notification not working.

- Fixed memory size exhausted.

- Add filter for the shipment prefix and suffix.

- Fixed local time issue.

= 6.5.2 =

- Fixed error of [wpcargo_account] shortcode

= 6.5.1 =

- Fixed error of responsive table in history section of track results

= 6.5.0 =

- Updated function used to override frontend templates for child theme

= 6.4.10 =

- Fixed shipment history error undefined index

- Remove user meta for the wpcargo user information (Depreciated) 

= 6.4.9 =

- Fixed error on local time

- Fixed error of undefined index in shipment results template

= 6.4.8 =

- Fixed translations of the following languages: Arabic, Italian, French(France), French(Canada), Spanish, Russian, Romanian

= 6.4.7 =

- Fixed shipment status settings not showing when custom field add on installed and activated

- Add Registered Shipper filter for reports

= 6.4.6 =

- Fixed error google autocomplete when no API is found

- Fixed the assign employee meta key based on the frontent end manager meta key for the assign employee

- Add auto search for the report page

= 6.4.5 =

- Fixed date data undefined to other language

- Fixed Color Picker script error on add new page

- Update email footer devider to be removable through hook

= 6.4.4 =

- Fixed error of Russian translation of WPCargo menu on wp-admin

- Add Italian language translation

= 6.4.3 =

- Add class attribute in the shipment history table row and data

- Add class attribute in the packages table row and data

= 6.4.2 =

- Fixed error on removing shipment history.

- Updated wpcargo_field_generator function to include checkbox and radio button type with array as option

- Fixed invoice layout

= 6.4.1 =

- Updated array format of getting meta data for reports fields.

= 6.4.0 =

- Fixed error on reports features when WPCargo Custom Field Add-ons is activated

- Fixed error on search form and results when WPCargo Custom Field Add-ons is activated

= 6.3.9 =

- Additional hook to add setting option for disabling emails when branch manager and pod is installed

- Updated wpcargo_field_generator to identify required fields

- Add translation for Russian language

- Fix translation of French(France) language

= 6.3.8 =

- Add translation for French(France) language

= 6.3.7 =

- Fix error in reports form.

- Add translation for Arabic and Spanish(Spain) language

= 6.3.6 =

- Fixed error of saving status when status field is empty.

= 6.3.5 =

- Adjust width of dimensions in package table

- Fixed error on after package data shows even multiple package is disabled

- Update description for package table to textarea

- Use wpcargo fullname function on assigning users dropdown

- Fixed layout of track result page

- Add setting to enable/disable sending of emails to assigned users

- Removed print track result on frontend until layout will be fixed

- Fixed login form layout

- Deprecate [wpc-ca-account] and [wpcargo_trackresults] shortcodes

- Changed Add Shipment Country to Add Shipment Location in General Settings

= 6.3.4 =

- Additional hook to disable sending of email to assigned employee, agent and client.

= 6.3.3 =

- Additional field for map setting to set specific country for auto complete results.

= 6.3.2 =

- Additional map setting to set default location.

= 6.3.1 =

- Fixed error on assign user to shipment email notification.

- Fixed track result nonce error with woocommerce installed.

- Fixed track result show parameter not working.

= 6.3.0 =

- Fix error of map not showing on results.

= 6.2.9 =

- Fix error of saving an empty status.

= 6.2.8 =

- Fixed Admin packages table repeater functionality not working error.

= 6.2.7 =

- Return missing print label Account's Copy

= 6.2.6 =

- Added functionality that enables user to customize print label on wp-admin through child theme

= 6.2.5 =

- Fix issue of status not saving

= 6.2.4 =

- Added email notification when assigning shipments to employee, agent and client

= 6.2.3 =

- Fixed change common class with prefix wpcargo conflict

= 6.2.2 =

- Fixed error on email notification

= 6.2.1 =

- Updated history fields to be dynamic on quick edit shipment

- Fixed width of fields on package table

- Fixed issue on map API

- Fixed issue on saving status

- Fixed issue on auto populate of time and date in history fields ( Admin Page )

= 6.2.0 =

- Additional filter for modifying history fields

- Removed package details on print label

- Changes on the function to display map

- Removed function wpcargo_shipment_history_map_callback and replace it on wpcargo_gmap_library function

- Added Datetime Picker library to be used on all plugins

- Removed timepicker library

= 6.1.8 =

- Fix Package details missing on track form

- Remove demo section on settings

= 6.1.7 =

- Fixed print label and invoice errors with custom sections

- Fixed packages field display error

- Fixed packages volume calculation errors

= 6.1.6 =

- Remove Client Account Settings

- Remove dropdown fields for Registered Shipper and Registered Receiver

- Fix error of bulk edit of shipments

- Removed required attribute from client and employee dropdown in wp-admin

= 6.1.5 =

- Removed required attribute from client and employee dropdown in wp-admin

= 6.1.4.1 =

- Fixed error of non-existing callback

= 6.1.4 =

- Fixed shipment metabox errors

- Fixed error for non-numeric value encountered

- Disabled wp-admin top bar for client login

- Restrict Client access to wp-admin

- Added employee role as default when plugin is activated

= 6.1.3 =

- Fixed wordpress plugin version compatibility

= 6.1.2 =

- Restrict access of Client user on wp-admin

- Additional Assign Shipment to metabox for respective designations

- Added user role Employee

- Added default page Account for Client

- Updated user capabilities of Agent

- Fix bugs on repeater field for packages

= 6.1.1 =

- Fixed the shipment bulk update.

= 6.1.0 =

- Fixed SMS hook error.

- Update the shipment multiple package templates and add volumetric and actual weight calcualtion.

- Add some hooks and filters for easy customization.

- Changed "Invoice" print button label into "Print".

- Add defualt settings value during plugin activation.

= 6.0.9 =

- Update track result template and add new section for the shipment status.

- Update shipment details section into 3 column layout

- Update track result font family into google font "Roboto"

= 6.0.8 =

- Add new settings for the TAX in percentage.

- Checked plugin error for wordpress version 5.2.

= 6.0.7 =

- Add new parameter on the "wpcargo_trackform" shortcode "show", this parameter will allow user to either to display the track form after form submission or not. This paramter will accept 1 or 0, the default value is 1.

- Fixed the pagination styles

- Add Hook "wpcargo_before_shipment_details" for the track result template.

- Fixed the "wpcargo_get_postmeta" function for the URL form field display format.

- Add filter "wpcargo_track_result_shipment_number" for customizing track result shipment number label.

- Add filter "wpcargo_print_invoice_label" for customizing track result print invoice button label.

= 6.0.6 =

- Add new settings for the Shipment Map for "Map Type" and "Zoom Level"

= 6.0.5 =

- Fixed shipment history map display in print invoice page.

- Fixed date format display based on general settings.

= 6.0.4 =

- Add new option for the shipment history map to display in result page.

= 6.0.3 =

- Fixed display shipment serialize value.

- Create plugin based CSS based on Bootstrap template to fix CSS compatibility with Bootstrap 3.x.x and below.

- Fixed popup close button for view shipment NOT clickable.

- Update plugin button classes.

= 6.0.2 =

- Fixed track form mobile reposive layout.

= 6.0.1 =

- Fixed pre display track result data.

- Update CSS compatibility with Bootstrap 3.x.x and below

- Add new filter for the registered shipper query

- Fixed Shipment status error on save.

- Fixed WPCargo Client role missing on Client account plugin deactivation.

- Fixed registered shipper data missing on shipment update.

- Add Bulk update for registered shipper.

= 6.0.0 =

- Fixed language translation.

- Fixed duplicate create shipment number.

- Merge client account add on function.

- Add admin shipment status email notification.

- Update plugin style with bootstrap based styles.

- Fixed date and time format for the date and time picker fields.

- Add new shotcode [wpcargo_account] for the client front end dashboard.

- Add new user role "WPCargo Client".

- Fixed email notification header error.

- Add new filter for the shipment owner in the shipment table list.

- Fixed email shortcodes for the {site_name}, {site_url}, and {admin_email} errors.

- Update the Email shotcode tags into actual shipment meta keys.

- Fixed SMS add ons hook error.

- Add new settings for the shipment number suffix.

- Update the track result template and fixed mobile responsive layout.

= 5.3.1 =

- Fixed autogenerate Shipment Number bug when updating shipment.

= 5.3.0 =

- Add new function to allow admin to decide the number of digits for the Shipment Title number.

- Allow auto generate shipment number even without shipment prefix.

- Fixed language translation in track form placeholder.

= 5.2.3 =

- Fixed Shipment History bug when no Wpcargo Settings is available.

- Add Shipment History Map Tab in WPCargo settings navigation.

- Fixed Navigation Tab wpcargo base color.

= 5.2.2 =

- Fixed the Email notification BCC and CC using shortcode.

- Add shipment filter for shipment category in shipment table

- Add class to shipment status for CSS customization

- Add class to shipment history class for CSS customization

- Fixed shipment history WPML comaptibility

- Fixed error on Shipment history Map

= 5.2.1 =

- Fixed the User timezone bug

- Create new user fields to set specific user timezone

= 5.2.0 =

- Newly added feature for Shipment History Google Map Tracker

- Add bulk and quick edit functionality in Shipment table

- Fixed minor bugs

= 5.1.0 =

- Add filters to shipment history and multiple package section header

- Fixed the Shipment history delete button bug

- Update the shipment status section, Remove the required attribute by default in all form fields and make it required when the shipment status option is not empty.

= 5.0.7 =

- Add option to enable User Timezone in general settings

= 5.0.6 =

- Fixed the script error on admin edit.php page

- Update the date and time default value based on current user localization.

= 5.0.5 =

- Add new Email settings for the Email Cc and Bcc.

= 5.0.4 =

- Fixed CSV format to SLYK format issue in exporting shipment data.

- Fixed the Select Option auto save bug in export shipment form.

- Add pre field value for the shipment history fields for the date, time and location.

= 5.0.3 =

- Fixed email notification bug.

- Add new email notification setting "Select Shipment Status to send email Notification"

- Fixed Color theme in report page

- Fixed Shipment History Shipment Status option bug

= 5.0.2 =

- Fixed the shipment history table list error when no settings are set.

- Remove the duplication of the Carrier field data.

- Update Styles for mobile responsive

- Update the Report Select option data to be form label.

= 5.0.1 =

- Fixed the shipment history display settings error.

= 5.0.0 =

- Add print label functionaly for the shipment.

- Add some styling for the data display consistency.

- Add option to Display Shipment History in result Page (General Settings).

- Update Shipment hitory template. Removed the add shipment history and add admin restriction for the user role to update shipment history (General Settings).

- Remove the Shipment Status in the Shipment fields.

- Merge the Shipment Status with the Shipment History form fields ( note: Add shipment History form above Publish Button ).

- Fixed bug with the Custom Field add on compatibilty

- Add the followig Filters for shipment data customization

- "wpcargo_status_option" - accepts one parameter ( must be array value ). this will affect the wpcargo status options.

- "wpc_shipper_name_table_data" - accept string ( metakey ). This will replace the Shipper name column in the Shipment table.

- "wpc_receiver_name_table_data" - accept string ( metakey ). This will replace the Receiver name column in the Shipment table.

- "wpc_report_search_shipper_name_metakey" - accept string ( metakay ). This will change the shipment metakey to be search in Senders name in Report page.

- "label_template_url" - Accept file Path. This will replace the Shipment label template.


== Upgrade Notice ==

Just upgrade via Wordpress.