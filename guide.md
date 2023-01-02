---
markdown-version:
tool-type: theia
branch: lab-3240-instruction
version-history-start-date: '2022-12-27T04:56:28Z'
---

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0251EN-SkillsNetwork/labs/m6_final/images/IDSNlogo.png" width="200" height="200">
<br>

# Lab 4: Run and test Your App

**Estimated time needed:** 20 mins

In this lab, you will test the completed online course app by running it locally on Django dev server.

If your Theia workspace has been reset and you want to continue from what you have done previously,
please `git clone` or pull from your created GitHub repository.

## Objectives

This lab contains the following tasks:

1.  Run the online course Django app on local server
2.  Submit your GitHub repository URL

# Environment setup

If your Theia workspace has been reset and you want to continue from what you have done previously,
please `gitclone` or pull from your created GitHub repository.

*   Set up the Python runtime if Theia workspace has been reset.

```
python3 -m pip install -U -r requirements.txt
```

{: codeblock}

# Task: Run and test your online course app

Note that you may need to perform models migrations for a new Theia environment.

*   Run Django development server and check if you see an example section in course detail page:

```
python3 manage.py runserver
```

{: codeblock}

*   Then click on the Skills Network button on the left, it will open the **"Skills Network Toolbox"**.

Then click the **Other** then **Launch Application**. From there you should be able to enter the port `8000` and launch.

If you need to refresh your memory about how to run Django app locally, you may refer to this lab:

[Create Your First Django App](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0251EN-SkillsNetwork/labs/m4\_django_app/lab1\_first_django_app.md.html)

# Task: Perform integration testing

Test the updated `onlinecourse` app to make sure no unexpected errors or crashes and the app
works as designed.

You can create a new course with valid questions and choices and try to pass/fail the course to test.

# Task: Submit the screenshots

Make screenshots for the following pages:

1.  The updated course details page with the no questions answered in the exam section
2.  The updated course details page with all questions answered in the exam section
3.  The new exam submission and result page and show a FAILED exam result
4.  The new exam submission and result page to show a SUCCESS exam result

# Task: Submit the URL of your GitHub repository containing the source code and assets

Submit the URL of your GitHub repository for peer reviews.

## Author(s)

<h4> [Yan Luo](linkedin.com/in/yan-luo-96288783) <h4/>

## Changelog

| Date        | Version | Changed by | Change Description      |
| ----------- | ------- | ---------- | ----------------------- |
| 04-Dec-2020 | 1.0     | Yan Luo    | Initial version created |
| 11-Nov-2022 | 1.1     | Yan Luo    | Removed Cloud Foundry   |
|             |         |            |                         |
|             |         |            |                         |

## <h3 align="center"> Â© IBM Corporation 2020. All rights reserved. <h3/>