# Contributor's Guide

Welcome to provide feedback, report bugs, and submit pull requests. You can click [issue](https://github.com/eryajf/awesome-ops/issues) to submit.

If you are collaborating on GitHub for the first time, you can refer to: [Collaborative Development Process](https://howtosos.eryajf.net/en/HowToStartOpenSource/01-basic-content/03-collaborative-development-process.html)

📢 Prerequisite: Please note that the submitted project must be a GitHub project, otherwise the other fields in the table will not be displayed correctly.

1. The README of this project is automatically generated by an action, please do not edit this file.

2. The files in README are taken from the `items/*/*.yaml` files. If you want to add a new project, please copy a file in the corresponding category, and then fill it in according to its content specifications:

```yaml
kind: OpenLDAP
owner: eryajf
repo: go-ldap-admin
desc: '🌉 OpenLDAP 后台管理项目，采用 Golang+Vue 实现'
desc_en: '🌉 OpenLDAP background management project based on Golang+Vue'
```

- The above four fields are all required, otherwise it will cause rendering failure.
- `kind:` used to classify the project according to this field, usually consistent with the name of the parent directory.
- `owner:` the username of the repository or the name of the organization. 📢 Note: If the value of this field is all numbers, please enclose it in double quotation marks. Otherwise, the action will fail.
- `repo:` the name of the repository. 📢 Note: If the value of this field is all numbers, please enclose it in double quotation marks. Otherwise, the action will fail.
- `desc:` briefly introduce the project in a few words. Please note that this content should not contain any special characters like |, as it will be presented as a column in the table.
- `desc_en:` briefly describe the project in English. Please note that this content should not contain any special characters like |, as it will be presented as a column in the table.

3. If you are unsure how to categorize a project, or if the project currently does not have a corresponding category, you can try creating a category directory first before adding the project.