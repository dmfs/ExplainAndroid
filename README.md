# Explain Android

A collection of resources that Android apps need in order to explain certain things to the user, for instance why and how to disable app hibernation for apps
that need it.

The goal of this library is to provide ready to use, localized resources to address all sorts of scenarios that an app developer might need to address.

## Supported scenarios


### Disable [App Hibernation](https://developer.android.com/topic/performance/app-hibernation)

Apps that work primarily in the background may need to ask the user to disable app hibernation to keep working even if the user doesn't interact with the app.

#### Resources

| Type | Name | Description         |
|------|------|---------------------|
| string | explain_android_title_disable_app_hibernation     | Title of a dialog that prompts the user to disable app hibernation |
| string | explain_android_button_go_to_hibernation_settings | Title of button that takes the use to the app hibernation settings |
| string | explain_android_prompt_disable_app_hibernation | Prompt the user to disable app hibernation |
| string | explain_android_prompt_disable_app_hibernation_instructions | Instructions on how to disable app hibernation |
| string | explain_android_prompt_disable_app_hibernation_reasoning | Generic and brief explanation on what app hibernation is any why it might break this app |


TODO: consider adding screenshots that help the user through the process


## License

Copyright 2022 dmfs GmbH


Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

