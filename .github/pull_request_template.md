<!--- Provide a general summary of your changes in the Title above -->

# Description
<!--- Describe your changes in detail -->
<!--- Why is this change required? What problem does it solve? Any specific requirements regarding rollout?-->

# Related Issue
<!--- This project only accepts pull requests related to open issues -->
<!--- If suggesting a new feature or change, please discuss it in an issue first -->
<!--- If fixing a bug, there should be an issue describing it with steps to reproduce -->
<!--- Please link to the issue here: -->

# Checklist
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] I have followed the PR process as described [here](https://docs.skyscrapers.eu/coding_guidelines/git/#pull-requests)
- [ ] My code has been tested: 
  - [ ] Locally (please provide details if applicable)  
  - [ ] In this PR using Atlantis 
- [ ] My code is ready to be applied.  
  - [ ] contains breaking changes 

> [!TIP]
> - If you’ve made any changes to the IaC, you can manually trigger Atlantis to test your changes.
> - Changes to the code in the `terraform/live` folder will automatically trigger Atlantis.
> - If you’ve made changes to the code in the `terraform/modules` folder, you can manually trigger Atlantis by commenting on the PR with: 
`atlantis plan -d terraform/live/<environment>/<project>`.
This command will trigger a plan for the specified project within the specified environment.
