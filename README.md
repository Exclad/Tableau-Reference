# Tableau Documentation

## Tableau Permissions

### Nested Asset Permissions
Based on our testing, it is essential to apply folder-level permissions first to ensure that these permissions are inherited by all contained objects (workbooks, data sources, etc.). Ensure that Asset Permissions are locked, so that it applies to nested projects.

![Nested permission: Enable this first to make sure the asset permission follows project permission](https://github.com/user-attachments/assets/2ef83333-7118-45aa-adf8-25073881923c)

### Project-level Permission
#### Overview

Has 2 permission rules: [View](#view) and [Publish](#publish)

![Project-level permission types summary](https://github.com/user-attachments/assets/d7e183d9-2e5a-43cf-8e0d-cff4dcf5f5a8)

#### View
**Without View**: The folder is not visible to the user.

**With View**: The folder is visible to the user.

![Project-level: View permission comparison](https://github.com/user-attachments/assets/abaef3a1-4856-46b0-91eb-3074dc813ce6)

#### Publish
**Without Publish**: User cannot publish objects (workbooks, data sources, etc.) into the folder.

**With Publish**: User can publish objects (workbooks, data sources, etc.) into the folder.

![Project-level: Without Publish permission](https://github.com/user-attachments/assets/2f1c7612-c78e-43ba-a168-24618e7eca12)

![Project-level: With Publish permission](https://github.com/user-attachments/assets/1578b360-9ca5-4db3-bb2b-0155b16ba639)


