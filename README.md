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

### Data Sources-level Permission
#### Overview

Has 8 permission rules: View, Connection, Download, Overwrite, Save As, Move, Delete, Set Permission

![Data Sources Level permission types summary](https://github.com/user-attachments/assets/140ed971-2149-423b-8e7b-2ec4da8983ae)

#### View
**Without View**: User cannot see the data source.

**With View**: User can see the data source.

![Data Sources Level: Without View permission](https://github.com/user-attachments/assets/8049892e-4aec-4270-8b57-f62fce0d332b)

![Data Sources Level: With View permission](https://github.com/user-attachments/assets/f30c4daf-c108-440f-af77-0fd9b08465a0)

#### Connection
**Without Connection**: Option to create a workbook with the data source is grayed out.

**With Connection**: User can directly create a workbook with the data source.

![Data Sources Level: Without Connection permission](https://github.com/user-attachments/assets/2c913762-7e63-4b31-ad23-d5c39b65d2a7)

![Data Sources Level: With Connection permission](https://github.com/user-attachments/assets/a8aa035f-794a-4237-a724-73df9cb3fd29)

#### Download data
**Without Download**: Option to download the data source is grayed out.

**With Download**: User can download the published data source.

![Data Sources Level: Without Download permission](https://github.com/user-attachments/assets/7d9fd074-4329-40a0-a930-3e739d329929)

![Data Sources Level: With Download permission](https://github.com/user-attachments/assets/d3c0bb10-1513-4add-b0c0-e0b43570ea5a)

#### Overwrite
**Without Overwrite**: User will encounter an error when trying to overwrite the pre-existing data source.

**With Overwrite**: User can overwrite the pre-existing data source.

![Data Sources Level: Without Overwrite permission](https://github.com/user-attachments/assets/2f50a702-f4e9-4a72-bd0a-4404271bd047)

![Data Sources Level: With Overwrite permission](https://github.com/user-attachments/assets/74ac25a9-b8e6-4f29-b677-414154d32e7a)

#### Save As
Think of this permission as a Save As function in Windows. You open an already published datasource, make your changes for yourself and want to save it for your own use. 

**Without Save As**: User cannot "Publish As" or "Save As" a published data source; the option is grayed out.
**With Save As**: User can "Publish As" or "Save As" a published data source.

![Data Sources Level: Without Save As permission](https://github.com/user-attachments/assets/bc1926a1-0d50-4d08-be48-e3d471cd9a83)

![Data Sources Level: With Save As permission](https://github.com/user-attachments/assets/7cd65a75-d022-4186-83df-1a69b04f2e44)

#### Move
**Without Move**: User cannot move items to other folders.

**With Move**: User can move items to other folders.

![Data Sources Level: Without Move permission](https://github.com/user-attachments/assets/cb94a594-d013-4a47-9b74-85d0f4495365)

![Data Sources Level: With Move permission](https://github.com/user-attachments/assets/5126d722-7dd9-4a33-b8d1-99217178b1a6)

#### Delete
**Without Delete**: User cannot delete items.

**With Delete**: User can delete items.

![Data Sources Level: Without Delete permission](https://github.com/user-attachments/assets/bcb241e5-f438-48d5-be17-a1916449f54e)

![Data Sources Level: With Delete permission](https://github.com/user-attachments/assets/0b3c8b19-d880-4568-9b77-860c22fe4e08)

#### Set Permission
**Without Set Permissions**: User cannot set any permissions for the item.

**With Set Permissions**: User can set permissions for the item.

![Data Sources Level: Without Set Permission permission](https://github.com/user-attachments/assets/4d05d257-72fc-4b05-9481-07f4fd9e3f4a)

![Data Sources Level: With Set Permission permission](https://github.com/user-attachments/assets/cd0d1946-5316-44d5-a0ba-9beb8f85e9bd)


### Workbooks-level Permission
#### Overview

Workbook level permissions are only slightly different from datasource permissions. They include:
View, Filter, View Comment, Add Comment, Download Image/PDF, Download Summary Data, Share Customized, Download Full Data, Web Edit, Run Explain Data, Download/Save A Copy, Overwrite, Create/Refresh Metrics, Move, Delete, Set Permissions.

![Workbooks-Level Permission Types Summary](https://github.com/user-attachments/assets/8fcca50e-a2b4-4ddd-8557-8aa1a3650dfb)

#### View
**Without View**: Workbook is not visible.

**With View**: Workbook is visible.

![Workbooks Level: View Permission](https://github.com/user-attachments/assets/2f59ca3b-7352-46bb-ba51-78851e70f1f5)

#### Filter
**Without Filter**: User cannot filter the dashboard (to keep/exclude values).

**With Filter**: User can filter the dashboard.

![Workbooks Level: Filter Permission](https://github.com/user-attachments/assets/189119cb-d3a8-4c35-8fa5-292b430046ba)

#### View Comments & Add Comments
**Without View Comments & Add Comments**: Comment button is not visible in the workbook.

**With View Comments**: User can view comments made on the workbook but cannot add comments until Add Comments permission is granted.

![Workbooks Level: Without Comment Permission](https://github.com/user-attachments/assets/1a42ce16-3a85-44bf-8d5d-dc566f946995)

![Workbooks Level: /With Comment Permission](https://github.com/user-attachments/assets/2bb67acf-a043-4463-878f-bcdf3306f8a7)

#### Download (Image/PDF +  Summary Data +  Full Data + Save a Copy)
**Without Download Permissions**: User cannot download the workbook as an image, PDF, summary data, full data, or the workbook itself.

**With Download Image/PDF Permissions**: User can download the workbook as an image or PDF.

**With Download Summary Data Permissions**: User can download only the summary data of the workbook.

**With Download Full Data Permissions**: User can download the full data of the workbook.

**With Save a Copy Permissions**: User can download the workbook.

![Workbooks Level: Without Download Permission](https://github.com/user-attachments/assets/ae5ee01c-dcc6-46a2-a076-b56247e17347)

![Workbooks Level: Download Permission](https://github.com/user-attachments/assets/4f69869b-ac6e-4c82-aec7-08753c16b574)

#### Share Customized
**Without Share Customized**: User can create a custom view but cannot make it visible to other users in Tableau Cloud.
**With Share Customized**: User can make their customized view visible to other users in Tableau Cloud.

![Workbooks Level: Share Customized](https://github.com/user-attachments/assets/331edd5a-9894-494e-8ad9-d76b9d9986d2)

#### Web Edit
**Without Web Edit**: User cannot edit the workbook in Tableau Cloud.

**With Web Edit**: User can edit the workbook in Tableau Cloud.

![Workbooks Level: Without Edit Permission](https://github.com/user-attachments/assets/8e8d9fff-d744-4741-86b6-c58fe565920f)

![Workbooks Level: With Edit Permission](https://github.com/user-attachments/assets/3871961d-7923-4f64-a299-effef837dbdf)

#### Run Explain Data
**Without Run Explain Data**: User cannot use the Explanation feature under Data Guide in Tableau Cloud.

**With Web Edit**: User can use the Explanation feature under Data Guide in Tableau Cloud.

![Workbooks Level: Without Run Explain Data permission](https://github.com/user-attachments/assets/92edbc11-d045-4409-bb1c-cc59c96fe3e9)

![Workbooks Level: With Run Explain Data permission](https://github.com/user-attachments/assets/f69e5c0e-861f-42aa-8e6d-d34eb5967bfb)

