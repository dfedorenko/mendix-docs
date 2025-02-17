---
title: "Maia Chat"
linktitle: "Chat"
url: /refguide/maia-chat/
weight: 5
description: "Describes the features in Maia Chat."
aliases:
    - /refguide/mendix-chat/
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

## 1 Introduction 

{{% alert color="info" %}}
MendixChat was rebranded to Maia Chat and released in GA in Studio Pro 10.12.0.
{{% /alert %}}

{{% alert color="info" %}}
Maia Chat does not use any project, customer, or company information. It only uses the data that you have entered in the Chat. Please do not enter any personal or sensitive data!
{{% /alert %}}

Maia Chat is a built-in chat interface powered by Generative AI in Studio Pro. Developers can ask questions about app development in Mendix, including how to apply concepts, best practices, and development patterns. It is built based on large language models (LLMs), using data from [Mendix Docs](https://docs.mendix.com/), [Mendix Community](https://community.mendix.com/), and [Mendix Academy](https://academy.mendix.com/).

## 2 Using Maia Chat

{{% alert color="info" %}}
To use Maia Chat, internet connection is required and make sure you are signed in to Studio Pro.
{{% /alert %}}

There are two ways to access Maia Chat: 

* You can click the {{% icon name="sparkles" %}} icon at the top right bar of Studio Pro
* Or you can go to the **View** menu and click **Maia**

The Chat interface appears at the right side of Studio Pro under the **Maia** tab:

{{< figure src="/attachments/refguide/modeling/mendix-ai-assistance/maia-chat/maia-chat-interface.png" width="300px">}}

### 2.1 An Example of Interacting with Maia Chat

You can start using Maia Chat by clicking one of the demo questions. You can also start by asking your own question in the chatbox. 

The following steps present an example of how you can interact with Maia Chat by asking your own question:

1. Type the following question in the chatbox: `When should I use a calculated attribute?`.
2. Press <kbd>Enter</kbd> or the **Ask** button to send the question. You will then see the following:
    * An answer generated by Maia Chat
    * A copy icon ({{% icon name="copy" %}}) which allows you to copy the given answer to a clipboard (this option was added in 10.7.0)
    * Feedback icons
    * Top relevant references from various resources like Mendix documentation, Mendix Community, and Academy learning paths

        {{< figure src="/attachments/refguide/modeling/mendix-ai-assistance/maia-chat/maia-chat-example.png" width="350px" >}}

        {{% alert color="info" %}}In Studio Pro 10.7.0 and above, you can also see the Mendix version of the references, the level required if the reference comes from Mendix Academy, and the date and answer status if the reference comes from the Mendix Community{{% /alert %}}

3. To give your feedback on the given answer, click the thumbs up icon ({{% icon name="thumbs-up" %}}) or the thumbs down icon ({{% icon name="thumbs-down" %}}). 

4. To provide a more detailed feedback, click the add feedback icon ({{% icon name="notes-paper-edit" %}}). A detailed **Feedback** section shows below the given answer:

    * You can rate the **correctness**, **completeness**, and **readability** of the provided answer.
    * You can add additional explanation text in the **Additional feedback** text box if you want to. 

        {{< figure src="/attachments/refguide/modeling/mendix-ai-assistance/maia-chat/feedback-section.png" width="250px" >}} 

5. Click the **Submit feedback** button to send your feedback. Afterwards, you will be brought back to the main chat interface where you can continue asking new questions.

6. If you want to clear the messages to start a new conversation in a clean state, navigate to the top of the interface and click **New chat** (this option was added in 10.7.0).

### 2.2 Asking Follow-Up Questions

In Studio Pro 10.8.0 and above, Maia Chat supports asking follow-up questions based on your previous question and the answer you have received. For example, you can ask it to summarize the latest answer you received by typing the following in the chat: *Can you summarize that?*.

## 3 Keyboard Support

You can use the following shortcut keys in Maia Chat, including on the feedback page:

| Key | Description |
| --- | --- |
| <kbd>Enter</kbd> or <kbd>Ctrl</kbd> + <kbd>Enter</kbd> | Send your question in the chat. |
| <kbd>Shift</kbd> + <kbd>Enter</kbd> | Add a new line to your question. |
| <kbd>Delete</kbd> | Delete the selected text. |
| <kbd>Ctrl</kbd> + <kbd>C</kbd> | Copy the selected text to the clipboard. |
| <kbd>Ctrl</kbd> + <kbd>X</kbd> | Cut the selected text to the clipboard. |
| <kbd>Ctrl</kbd> + <kbd>V</kbd> | Paste the text of the clipboard. |
| <kbd>Ctrl</kbd> + <kbd>Z</kbd> | Undo the previous action. |
| <kbd>Ctrl</kbd> + <kbd>Y</kbd> | Redo the previous action. |

{{% alert color="info" %}}
The shortcut keys for the Delete, Copy, Cut, Paste, Undo, and Redo actions are available from Studio Pro 10.11.0 and above, and are currently supported only in Windows.

In Studio Pro 10.6, <kbd>Enter</kbd> can only be used to add a new line, not to send the question. You can use <kbd>Ctrl</kbd> + <kbd>Enter</kbd> or the **Ask** button to send the question. 
{{% /alert %}}
