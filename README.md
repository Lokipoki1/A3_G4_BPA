# A3_G4_BPA

## 📦 Camunda8 Deployment Instructions

To set up this project, please follow these steps for the model and forms:

1. **Camunda Model Deployment**
   - Navigate to the **`Camunda8/model/`** directory.
   - Download the model files.
   - Deploy the model in camunda modeler.

2. **Camunda Forms Deployment**
   - Navigate to the **`Camunda8/Forms/`** directory.
   - Download the form files.
   - Deploy the forms in camunda modeler.

3. **UIPAth Model Deployment**
   - Navigate to the **`UIPath/`** directory.
   - Download the files
   - Put all the files in target folder of your choice
   - Open the project.json file in UIPath Studio
---

## ⚙️ Configuration Variables

**Camunda 8**
When starting a new Camunda8 process instance, please include the following parameters:

```json
{
  "nameApplicant": "Applicant Name",
  "surnameApplicant": "Applicant Surname",
  "birthApplicant": "14 december, 2025",
  "emailApplicant": "applicant email"
}
```

**UIPAth**

For the initialization of the UIPath process, please set up the variables to the define paths:

homePath: Folder cointaining the Contract Folders and where the folder for each applicant will be created.
downloadPath: Default folder to which your browser downloads files.

These variables are defined on the scope of the first open application element.

## 🎥 Video

Click the link to watch the walkthrough video: https://drive.google.com/file/d/1ihJAGzpOA4fAq8SdjQl-xQFPtdQjcWZ7/view?usp=sharing
