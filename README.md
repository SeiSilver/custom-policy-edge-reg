# Custom Policy for Microsoft Edge Registry

The `custom-policy-edge-reg` repository provides custom policies for configuring Microsoft Edge browser settings using the Windows Registry.

## Table of Contents
- [Custom Policy for Microsoft Edge Registry](#custom-policy-for-microsoft-edge-registry)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Installation](#installation)
  - [Policy Config](#policy-config)

## Overview

Custom your own edge policy without manually config it

## Installation

To apply custom policies from this registry:

1. Clone or download this repository to your local machine.

2. Double-click on the desired `.reg` file to import it into the Windows Registry.

3. Follow any prompts to confirm the changes.

4. Restart Microsoft Edge browser to apply the new policies.

## Policy Config

| Policy Name                  | Description                                                              | Values                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| SearchSuggestEnabled         | Enables or disables the search suggestions feature in the address bar.   | `0` - Disable search suggestions <br> `1` - Enable search suggestions                                     |
| LocalProvidersEnabled        | Controls the use of local providers for search suggestions.              | `0` - Disallow local providers <br> `1` - Allow local providers                                           |
| ConfigureDoNotTrack          | Specifies whether to send the Do Not Track (DNT) signal in HTTP headers. | `0` - Do not send the DNT signal <br> `1` - Send the DNT signal                                           |
| AutofillAddressEnabled       | Enables or disables the autofill feature for addresses.                  | `0` - Disable autofill for addresses <br> `1` - Enable autofill for addresses                             |
| AutofillCreditCardEnabled    | Enables or disables the autofill feature for credit card information.    | `0` - Disable autofill for credit card information <br> `1` - Enable autofill for credit card information |
| EdgeShoppingAssistantEnabled | Controls the availability of the Edge Shopping Assistant feature.        | `0` - Disable Edge Shopping Assistant <br> `1` - Enable Edge Shopping Assistant                           |
| UserFeedbackAllowed          | Specifies whether to allow user feedback collection.                     | `0` - Disallow user feedback <br> `1` - Allow user feedback                                               |

Feel free to use this table format in your README file. Adjustments can be made as per your preferences or specific requirements.

---

Feel free to adjust the content to better suit your needs or add more detailed instructions if necessary.