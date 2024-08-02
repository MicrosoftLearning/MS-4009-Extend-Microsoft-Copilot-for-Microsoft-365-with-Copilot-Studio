# Exercise: Create a conversational action

In this exercise, you will create a conversational action that provides information about a fictional organizational project titled "Project ABC".

Exercise tasks:

- Create a conversational action in Copilot Studio
- Publish a conversational action to Microsoft Copilot
- Test your conversational action in Microsoft Copilot

## Task 1: (Optional) Test the default experience

To begin, attempt to ask a question about project ABC in Microsoft Copilot for Microsoft 365.

1. Open **Microsoft Teams**.

1. Select **Chat** in the sidebar.

1. Select **Copilot** in the chat menu.

1. In the message compose box, enter `Who should I contact for questions about Project ABC?`

1. Note that Microsoft Copilot for Microsoft 365 does not currently have any information about Project ABC.

## Task 2: Create a new conversational action

First, configure the name, solution, and schema for a new conversational action in Microsoft Copilot.

1. On the side navigation pane, select **Copilots**.

1. Under **Microsoft** select **Copilot for Microsoft 365**. The Overview page for Copilot for Microsoft 365 appears.

1. In the **Actions** pane select **+ Add action**.

1. Select **Conversational** to create a conversational action.

1. In the **name** field, enter `Project ABC` and accept the default solution and schema.

1. Select **Create** to proceed. Your new conversational action is created. This will take several seconds. When it is done, you are dropped into the conversational authoring canvas.

## Task 3: Configure the topic

Next, configure the name and trigger for the topic.

1. In the conversational actions authoring pane, navigate to the **Topics** tab.

1. Select the **Topic name** text box at the top of the pane and enter `Project ABC info` to name the topic.

1. In the **Trigger** node within the topic, select the text box under the text "Describe what the topic does" then enter `Answers questions and provides information about Project ABC, including questions about objectives, points of contact, and rollout timeline.`.

## Task 4: Send a message

Next, add a node to the topic to send a message about Project ABC.

1. Under the Trigger node, select the **+** icon to add a new node.

1. In the menu that is displayed, select **Send a message**.  A new message node is created.

1. In the message node, select the text box and enter `Project ABC is an initiative aimed at improving the culture and engagement within the company.  Objectives of the project include improved morale, increased employee survey results, and improved culture ratings.  For more information about Project ABC, contact Devon Torres.`.

1. Select **Save** above the authoring canvas to save the changes.

## Task 5: Publish the action

Next, publish the action for use in Microsoft Copilot for Microsoft 365.

1. From the conversational action page, select **Publish**.

1. On the **Publish Plugin** page, select **Publish**.

1. On the **Publish latest content?** page, select **Publish**.  Publishing may take a couple of minutes.  A notification will be displayed at the top of the window when publishing has completed.

## Task 6: Test the action

Finally, test the action in Microsoft Copilot for Microsoft 365.

1. Open **Microsoft Teams**.

1. Select **Chat** in the sidebar.

1. Select **Copilot** in the chat menu.

1. In the message compose box, enter `Who should I contact for questions about Project ABC?`

1. Note that Microsoft Copilot for Microsoft 365 returns information about Project ABC using the conversational action.

You can customize or expand this conversational action with additional nodes.  For example, you could create a new **Generative answers** node and upload a file, expanding the knowledge available to the action.