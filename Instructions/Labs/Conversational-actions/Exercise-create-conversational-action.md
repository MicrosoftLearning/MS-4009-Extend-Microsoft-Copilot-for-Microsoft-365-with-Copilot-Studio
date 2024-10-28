# Exercise: Create a conversational action

In this exercise, you will create a conversational action that provides information about a fictional organizational project titled "Project ABC".

Exercise tasks:

- Create a conversational action in Copilot Studio
- Publish a conversational action to Microsoft Copilot
- Test your conversational action in Microsoft Copilot

## Task 1: (Optional) Test the default experience

To begin, ask a question about project ABC in Microsoft 365 Copilot.

1. Open **Microsoft Teams** and sign in with your work or school account.

1. Select **Chat** in the sidebar.

1. Select **Copilot** in the chat menu.

1. In the message compose box, enter `Who should I contact for questions about Project ABC?`

1. Note that Microsoft 365 Copilot does not currently have any information about Project ABC.

## Task 2: Create a new conversational action

First, configure the name, solution, and schema for a new conversational action in Microsoft Copilot.

1. In your web browser, navigate to [Copilot Studio](https://copilotstudio.microsoft.com) and sign in with your work or school account, if prompted.  Select **skip** to skip any welcome messages.

    **Note:** The first time you open Copilot Studio, it may display a chat interface to create your first copilot. If this happens, select the **…** menu at the top right (next to the **Create** button) then select **Cancel copilot creation** and then **leave** to leave the chat interface and view the Copilot Studio home page.
1. Select **Library** in the left navigation. Here, you can view a list of existing actions and connectors and create a new one.
1. Select **Add an item** at the top.  A menu lists 2 options for extending Copilot for Microsoft 365.
:::image type="content" source="../Media/extend copilot options.png" alt-text="Window lists 2 options for extending Copilot: create a copilot or create an action.":::
1. Select **New action**.

1. Select **Conversational** to create a conversational action.

1. In the **name** field, enter `Project ABC` and accept the default solution and schema.

1. Select **Create** to proceed. Your new conversational action is created. This will take several seconds. When it is done, you are dropped into the authoring canvas to continue configuring your action.

## Task 3: Configure the topic

Next, configure the name and trigger for the topic.

1. In the conversational actions authoring pane, navigate to the **Topics** tab.

1. Select the **Topic name** text box at the top of the pane, which defaults to the name `"Untitled"` and enter `Project ABC info` to name the topic.

1. In the **Trigger** node within the topic, select the text box under the text "Describe what the topic does" then enter `Answers questions and provides information about Project ABC, including questions about objectives, points of contact, and rollout timeline.`.

## Task 4: Send a message

Next, add a node to the topic to send a message about Project ABC.

1. Under the Trigger node, select the **+** icon to add a new node.

1. In the menu that is displayed, select **Send a message**.  A new message node is created.

1. In the message node, select the text box and enter `Project ABC is an initiative aimed at improving the culture and engagement within the company.  Objectives of the project include improved morale, increased employee survey results, and improved culture ratings.  For more information about Project ABC, contact Devon Torres.`.

1. Select **Save** above the authoring canvas to save the changes.

## Task 5: Publish the action

Next, publish the action for use in Microsoft 365 Copilot.

1. Select **Publish** at the top of the page.

1. On the **Publish Plugin** page, select **Publish**.

1. On the **Publish latest content?** page, confirm that the Project ABC Info plugin is enabled and select **Publish**.  Publishing may take a couple of minutes.  A notification will be displayed at the top of the window when publishing has completed.

## Task 6: Enable and test the action

Finally, test the action in Microsoft 365 Copilot.

1. Open **Microsoft Teams**.

1. Select **Chat** in the sidebar.

1. Select **Copilot** in the chat menu.

1. In the message compose area, select the **Manage Copilot response** button.

1. In the flyout, search for **Copilot Studio** then select **Add** to add Copilot Studio.
 
2. The **Project ABC info** action should now be listed in the flyout.  Confirm that **Project ABC info** is enable then close the flyout.

:::image type="content" source="../Media/projectABCInfo-action-enabled.png" alt-text="Screenshot of the Project ABC Info action listed in the "Manage Copilot response" flyout in Teams.":::

3. In the message compose box, enter `Who should I contact for questions about Project ABC?`

4. Note that Microsoft 365 Copilot returns information about Project ABC by invoking the conversational action.

You can customize or expand this conversational action with additional nodes.  For example, you could create a new **Generative answers** node and upload a file, expanding the knowledge available to the action.

**Note:** Remember the following when testing your action in Copilot:
- Copilot will always rewrite your answers with its own voice. It's not possible, in this preview, to have the content passed through unchanged to the end user.
- The description of your conversational action is critical to how reliably it will be invoked. The description teaches the orchestrator what your action is good at and what answers it can provide. Be sure to use clear prose when writing the description, and consider experimenting with changes to get the best outcome.
- Following these steps accurately does not guarantee that Copilot will return the expected results each time.  Copilot will determine when to invoke your plugin and how to return the results.

## (Optional) Challenge: Create your own!

Apply what you've learned to create, publish, and test a new conversational action for a scenario of your choice.  Review the steps in this exercise as needed.