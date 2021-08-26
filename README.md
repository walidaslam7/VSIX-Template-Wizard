# CustomWizardVSIX
### Use wizards with project templates

Visual Studio provides the IWizard interface that, when implemented, enables you to run custom code when a user creates a project from a template.

Project template customization can be used to display custom UI that collects user input to customize the template, add additional files to the template, or any other action allowed on a project.

The IWizard interface methods are called at various times while the project is being created, starting as soon as a user clicks OK on the New Project dialog box. Each method of the interface is named to describe the point at which it is called. For example, Visual Studio calls RunStarted immediately when it starts to create the project, making it a good location to write custom code to collect user input.

Repo contains basic implementation and user inputs form for custom wizards using VSIX extension and Populate before staring the Main Project application.

[This Microsoft Link](https://docs.microsoft.com/en-us/visualstudio/extensibility/creating-custom-project-and-item-templates?view=vs-2019) contains all Steps that has followed to created this project.
