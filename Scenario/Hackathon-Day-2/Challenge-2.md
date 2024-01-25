# Challenge 02: GitHub Advanced Security - Implement Code Security Enhancements

### Estimated Time: 60 minutes

### Introduction:
In this previous challenge, you did a successful hosting of the application using GitHub repository and GitHub Actions for Continuous Integration and Continuous Delivery. In this challenge, you are a DevSecOps engineer tasked with ensuring the security of the Contoso Traders application hosted on GitHub. In this challenge, your goal is to mitigate risks in dependencies and secure sensitive data using advanced security features provided by GitHub. 

You need to focus on completing the implementation of the below-mentioned security features.

**Code Scanning**: Code scanning is a feature that you use to analyze the code in a GitHub repository to find security vulnerabilities and coding errors. Any problems identified by the analysis are shown in GitHub. You can use code scanning to find, triage, and prioritize fixes for existing problems in your code. Code scanning also prevents developers from introducing new problems

**CodeQL**: CodeQL is the code analysis engine developed by GitHub to automate security checks. You can analyze your code using CodeQL and display the results as code scanning alerts.

**Repository security advisories**: Repository security advisories allow repository maintainers to privately discuss and fix a security vulnerability in a project. 

## Accessing GitHub

1. To access the and login to GitHub, open the edge browser from inside the environment and navigate to **[GitHub](https://github.com/)**.

2. Sign in to GitHub by clicking on the **Sign in** button from the top right corner of the GitHub home page.

3. On the **Sign into GitHub tab** you will see a login screen, enter the following email/username and then click on **Next**.

   - **Email/Username:** 

1. Now enter the following password and click on **Sign in**.

   - **Password:** 


## Challenge Objectives:

> **Note**: Use the same GitHub repository which you created in the last challenge.

1. **Implement Code Scanning and CodeQL:**
 
   - Enable Code scanning for the repository.
   - Configure CodeQL analysis in the workflow to the existing GitHub.
   - Resolve the generated alerts if any.

2. **Implement Repository security advisories:**
   -  Set up Repository security advisories features for App.js package. Use `devsecops/src/TailwindTraders.Ui.Website/src/App.js` path while configuring the affected products.

  
## Success criteria:
To complete this challenge successfully:

   - Verify the implementation of setting up Code Scanning and CodeQL via alerts.
   - Configure the Repository security advisories feature and create temporary private fork.


## Additional Resources:

Here are a few documentation and guides to assist you in completing the challenge.
- [About GitHub's Advanced Security](https://docs.github.com/en/code-security/getting-started/github-security-features)
- [About GitHub's Advanced Security](https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql)
- [Code Scanning with GitHub CodeQL](https://learn.microsoft.com/en-us/training/modules/code-scanning-with-github-codeql/)

## Challenge Validations: [WIP]

1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 
 
    ![](../media/validate01.png "Validation")
 
1. If the validation status displays **Success** for all the validation steps, **congratulations!**. This means that you have successfully completed the challenge.
 
     ![](../media/validate02.png "Validation")
1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.
 
     ![](../media/validate03.png "Validation")
 
1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.
     ![](../media/validate04.png "Validation")
 
1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.


## Conclusion
Congratulations on successfully completing the **GitHub Advanced Security - Implement Code Security Enhancements** challenge. You've taken crucial steps to ensure the security and integrity of your codebase, especially when dealing with sensitive customer data. As you continue developing the e-commerce platform, consider regularly reviewing and updating your security measures. Stay informed about new security features and best practices offered by GitHub to ensure that your repository remains resilient to emerging threats. In this next challenge, you will explore and implement more GitHub advanced security features.