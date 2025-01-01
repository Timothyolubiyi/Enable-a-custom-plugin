# Enable-a-custom-plugin
You start by checking the owner settings for who can add and manage their own custom plugins and who can add and manage custom plugins for everyone in the organization. Once you have configured the owner settings, you upload the file for your custom plugin. Uploading the files adds the plugin capability to Copilot.

**Before you start**

For this exercise, you'll be using a sample .yaml file, 'KQL_DefenderExample.yaml.'

Select the link **KQL_DefenderExample.yaml** to access the sample file. [Sample files/KQL_DefenderExample.yaml](https://github.com/MicrosoftLearning/SC-5006-Get-started-with-Microsoft-Copilot-for-Security/blob/master/Sample%20files/KQL_DefenderExample.yaml)

Select the Download raw file download raw file icon icon. Save the file on your local computer, as you will need it later.

Alternatively, because this is a simulation, you can create the file named 'KQL_DefenderExample.yaml.' Because this is a simulation, the contents of the file you create won't matter. The system capabilities and prompt responses shown in the simulation, however, are based on the actual file.

**Task 1: Update owner settings for custom plugins**

In this task, you configure Copilot so that Copilot owners and contributors can add and manage their own custom plugins and for everyone in the organization.

Open the simulated environment by selecting this link: Microsoft Security Copilot.

Select the Home menu (hamburger) icon

Select Owner settings.

Under Plugins for Security Copilot,

Set "Who can add and manage their own custom plugins" to Contributors and owners.
Set "Who can add and manage custom plugins for everyone in the organization" to Contributors and owners.
Return to the landing page. Select Microsoft Security Copilot next to the home menu (hamburger) icon.

**Task 2: Upload the file for your custom plugin**

In this task, you upload the file named, KQL_DefenderExample.yaml, that you downloaded in the 'Before you start' section of this exercise.

From the prompt bar on the Copilot landing page, select the sources icon.

On the Manage Sources window, scroll down until you get to the Custom plugins. Select the Add plugin add plugin button button. This opens the Add a plugin window.

In the Add a plugin window, ensure the setting for Who can use this plugin is set to Just me.

For this exercise, select Security Copilot Plugin as this is the format for the .yaml file of your custom plugin.

From the upload box that appears, select Upload file, then select the file you previously downloaded to your local computer, KQL_DefenderExample.yaml then select Add.

On the custom plugins page, the plugin has been added and is enabled. Note the private tag.

Select the Settings icon. The settings icon shows basic plugin information. Note the name and brief description. This is a basic sample plugin so there are no configuration parameters to configure. If there were API keys or sign-in credentials required for the plugin, this is where they would be configured, like the exercise where you configured the Microsoft Sentinel plugin. Here you can also delete the plugin. Select Cancel to exit the page.

Close the manage sources window by selecting the X on the top right of the window.

**Task 3: Test the custom plugin**

In this task, you verify the capability enabled by the plugin can be accessed from the prompts icon and you test it.

From the prompt bar, select the Prompts icon.

Select See all system capabilities.

Scroll all the way down until you get to My sample Defender KQL plugin. Listed below the plugin name is the capability (prompt) enabled by the plugin. Select Get Latest Emails by Recipient to run the prompt. For future reference you can search by this capability (prompt) name.

Enter email address of a user whose email you need to audit: **nosv32@woodgrove.ms**.

As with any prompt, you can select the response and pin it the pin board, you can share it, edit it, and more.

**Review**

In this exercise, you enabled a custom plugin by uploading the .yaml file for the plugin and then tested the capability supported by the plugin.
