# BattleCON Spreadsheets

*Last Updated November 5, 2017.*

This page contains technical and logistical details for the BattleCON Spreadsheet System (henceforth "System"), available at http://bit.ly/BaCON-Sheet. The System is operated and maintained by `rngesus-wept (admin@rngesus.net)`. It is built on top of Google Sheets; any use of the System also implicitly acknowledges the Terms and Conditions et cetera of Google Sheets.

The purpose of the System is to provide a structured implementation of the BattleCON Fighting System in Google Sheets. The vast majority of what it does is fancy text manipulation.

At a high level the System comprises two spreadsheet documents, each bearing its own Google Apps Script code. The link above points at the core spreadsheet for the System (henceforth "System Core"). The System Core holds all the character data for the BattleCON Fighting System. It exposes a single function which creates a match between two such characters. The match ("Match Sheet") based on a duplicate of a template spreadsheet ("System Template"), which carries its own Google Apps Script code. Thus the data represented in a Match Sheet comprises:
  * structured data duplicated from the System Template,
  * structured data copied from a subset of the System Core, and
  * Apps Script Code duplicated from the System Template.

The System Template Code facilitates the manipulation of the structured data in the System Template and the copied structured data from the System Core.

## Privacy Policy

Using The System requires a Google login and the use of Google Sheets. By using it you implicitly acknowledge that Google's policies apply on top of the System-specific policies described herein. You also acknowledge that you are using the Internet to collaboratively edit a document, with all the hazards that entails, including the perils of interacting with other people.

The System Core generates System documents under your identity, and uses information you provide to set sharing permissions on the documents it creates. Aside from the information you directly provide it (email addresses and characters), the only information it collects is a timestamp.

The System Template (and as a result, the Match Sheet you duplicate from it) requires scripted Docs access in order to modify itself -- it does not identify or interact with any other documents associated with your account. It modifies itself under your identity. It does record information you provide directly to it (string inputs) in a document-local fashion.

### Service Providers

We may employ third-party companies or individuals for reasons related to the provision and maintenance of the System. If we do, any information we have collected (your email addresses) will be accessible to them. They are obligated not to disclose or use any of that information for purposes outside of the System.

### Changes

We may update this Privacy Policy from time to time. These changes are effective immediately, after they are posted on this page. The System Core will be updated to include a notification whenever such a change occurs.
