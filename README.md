# Request personal information

This is the source code for the Request personal information service built using MOJ Form Builder.

See the [handbook for Form Builder](https://ministryofjustice.github.io/fb-guide-and-runbook/#form-builder-guide-and-runbook) for more information.

To edit it, you need to install the [Form Builder Console](https://github.com/ministryofjustice/fb-editor-console-electron) application. This can also be installed from MOJ D&T Self Service if you have an MOJ Mac laptop.

## Setting up the form for development
Prerequisites include an MOJ Mac Laptop and a Github account that’s in the MOJ organisation. Ask to be added to the Request your Personal Information team on Github if you want to be able to create pull requests against the repository.

1. Once you have the Console installed and running, you need to connect the Console application to Github using a personal access token. You can create a token by going to your GitHub account and navigate to Settings > Developer Settings > Personal access tokens and following the directions there.

2. Once you have created your token, add it to the Form Builder Console using the tab under Settings.

3. Add the form to the Console by choosing Add an existing form from the main navigation in the Console, and specify the GitHub URL for this repository
4. The form should show up in the list of forms in the Console. Click Start to open the form for editing in a browser window.
5. When you have finished editing the form, you can commit your changes to a new branch and issue a pull request against the repository.

