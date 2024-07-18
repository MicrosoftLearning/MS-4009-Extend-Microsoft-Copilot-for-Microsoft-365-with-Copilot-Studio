# Exercise 1: Create an AI Builder prompt

In this exercise, you learn:

- How to write a good prompt
- How to create the prompt in Copilot Studio
- How to test the prompt

## How to write a good prompt

Earlier in this module, you already learned some basics of prompt engineering. A great resource to learn more about prompt engineering is reading the prompt engineering guide from the AI Builder team. The prompt engineering guide can be found [here](https://aka.ms/learn-ai-builder-prompting-guide).

## Elements in a good prompt

The prompt engineering guide from the AI Builder team has a great set of elements that should be part of your prompt.

As you can see, it has the following elements:

- **Task**: an **instruction** telling the Generative Pre-trained Transformer (GPT) model the task to be performed
- **Context**: describe the **data** that is acted on, along with any input **variables**
- **Expectations**: convey to GPT **goals** and **expectations** on the response
- **Output**: help GPT format the **output** the way you want

:::image type="content" source="../Media/4-prompt-engineering-guide.png" alt-text="A screenshot of the prompt ingredients page of the AI Builder prompt engineering guide. The tasks, context, expectations and output are highlighted as prompt ingredients.":::

## Task 1: <task title>

1. Numbered step
2. Numbered step
3. etc.

## Task n: <task title>

## Summary / Check your work

<summary/verification steps>

## Write the prompt

In this exercise, you write a prompt that helps you create a professional development plan based on career milestones.

> [!IMPORTANT]
> When creating a prompt, you don’t have to start from scratch. Although it is very helpful to know how to write a good prompt it can be helpful to start with something that already gets you halfway there.
> There are prompt samples already available on the [Microsoft Adoption Sample Solution Gallery](https://aka.ms/power-prompts). In this exercise we will use the [Professional Development Plan Prompt sample](https://adoption.microsoft.com/sample-solution-gallery/sample/pnp-powerplatform-prompts-professional-development/).

Let’s add all the prompt ingredients:

- **Task** – Design a professional development plan.
- **Context** – For someone aiming to achieve the following career [milestones].
- **Expectations** – The plan should include goals and objectives, resources, and tools and a timeline for activities.
- **Output** – Format the plan to be concise and actionable and present the information in a clear easy-to-follow manner suitable for a junior level employee.

Together, that would be the following prompt:

Design a professional development plan for someone aiming to achieve the following career [milestones]. The plan should include goals and objectives, resources, and tools and a timeline for activities. Format the plan to be concise and actionable and present the information in a clear easy-to-follow manner suitable for a junior level employee.

## Create the prompt in Copilot Studio

Now that you finished writing the prompt, it’s time to add it in Copilot Studio.

1. Sign in to **[Copilot Studio](https://copilotstudio.microsoft.com)**.
1. Sign in to [Copilot Studio](https://copilotstudio.microsoft.com).
1. In the left pane, select **Library**
1. Select the **Add an item** button
1. Select **Copilot for Microsoft 365**
1. In the *New action* screen, select **Prompt**. This will open the AI Builder prompt builder.
1. Enter “Professional Development Plan” as the **name** of the prompt.
1. Enter “Design a professional development plan for someone aiming to achieve the following career [milestones]. The plan should include goals and objectives, resources and tools and a timeline for activities. Format the plan to be concise and actionable and present the information in a clear easy-to-follow manner suitable for a junior level employee.” as the **prompt**.

    > [!NOTE]
    > Notice that there is an information bar at the top that indicates your prompt should have at least one dynamic value

1. Select **Input** on the right side of the screen to open up that section.
1. Select the **Add input** button to add an input.
1. Use `milestones` as the name of your input.
1. Add the following text as the sample data:

      ```text
      * Become medior in 3 years
      * Have 3 top reviews in a row
      * Become a manager in 10 years
      ```

1. Select **[milestones]** in the prompt section with your cursor.
1. Select **Insert**.
1. Select **milestones**.

      This will change **[milestones]** in a dynamic value.

1. Next, we are ready to test our prompt!

## Check your work

1. Select **Test prompt** below the prompt section. This will test the prompt with the sample data you added before.

    > [!NOTE]
    > This will send the prompt to the AI model and show the response in the AI response section. It enables you to see how the LLM responds and to see if you’re happy with the results.

1. When you’re happy with the AI response that shows, you can hit **Finalize prompt** to save the prompt.

    In the next window - you can review the plugin description and the inputs description.

1. Change the input description of milestones to:

      ```text
      The career milestones that the user wants to achieve
      ```

1. Select **Create prompt action** to finish creating your prompt action.

This is the end of the exercise, you have written your prompt, you created it in Copilot Studio and you have tested it! Continue with the next exercise to see how it can be used in Copilot for Microsoft 365!
