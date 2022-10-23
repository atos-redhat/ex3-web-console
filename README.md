# Ex. 3. OpenShift Web Console

## Steps to do

1. Create the new application from a `Basic Spring Boot` template.
    * Select the `Developer` perspective from the list at the top of the left menu.
    * Click From `Catalog` to display a list of technology templates. 
    * Enter `Spring` in the `Filter by keyword` field.
    * After filtering, click the `Basic Spring Boot template` to display the dialog box. Click `Create` to display the Import from Git page.
    * Press `Create`.

2. Switch back to the `Administrator` perspective for the remainder of the exercise.

3. Examine the logs for the build of the application. In the `Builds` menu, click `Builds` to display a list of recent builds for your project.

4. Use the navigation bar on the left side of the OpenShift web console to locate information for the application's OpenShift and Kubernetes resources:
    * Workloads/Deployments
    * Builds/BuildConfigs
    * Networking/Services

5. Select `Networking` on the navigation bar and press `Routes`. In the `Routes` menu find the route of your application and click on the link in the Location column to check if the application is running.

