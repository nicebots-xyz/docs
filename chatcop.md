---
title: ChatCop Bot Documentation
description: Docs for ChatCop
published: true
date: 2024-01-07T22:09:44.923Z
tags: 
editor: markdown
dateCreated: 2023-11-26T20:34:44.687Z
---

# Welcome
Welcome to the ChatCop Bot Documentation. This guide will help you quickly set up and efficiently use the ChatCop Discord bot for moderation purposes.


As you follow this guide, you’ll learn how to tailor ChatCop to meet your server’s specific moderation needs and discover all the powerful features it has to offer. If you have questions or need further assistance, check out the [Feedback and Support](#feedback-and-support) section on how to get in touch with us or join the official support server.

## Quick Setup

Follow these steps to get ChatCop up and running in no time:

1.  **Add ChatCop to Your Server**: Use [this invitation link](https://paill.at/ILFe2) to add the bot to your desired server.
2.  **Run Initial Configuration**: Type `/mod config start` in your server’s chat to begin the setup wizard.
3.  **Moderate With Default or Custom Settings**: After the initial setup, ChatCop will start moderating with default settings, which you can customize as needed.

## Configuration

Configuring ChatCop is crucial for ensuring that the bot’s moderation actions fit with your server culture and rules. This section of the documentation explains how you can adjust the bot’s behavior to reflect the needs and norms of your community.

### Initial Configuration

-   **Access Configuration**: Use the `/mod config start` command to access the configuration menu and set up initial settings.
-   **Notification Channel**: Specify a channel for the bot to send moderation notifications.

### Advanced Configuration

-   **Enabling/Disabling Moderation**: You have control over the bot’s moderation features and can turn them on or off as needed using `/mod enable` or `/mod disable`.
-   **Warning and Deletion Thresholds**: Use the `/mod config warn` and `/mod config delete` commands to set precise thresholds for various toxic behaviors, like profanity or spam.
-   **Set Logs Channel**: Use `/mod config channel` to direct where the bot will send moderation logs.
-   **Ignore Role**: With the `/mod config ignore_role` command, you can make ChatCop ignore users with a specific role for automatic moderation. This is useful for exempting moderators, VIPs, or specific groups from automatic moderation. Toggle the ignore function for a role by running the command once to activate and again to deactivate. Use `/mod config info` to view current settings. 

In the next sections, you’ll learn about the commands you can use to interact with ChatCop and how to manage moderation actions effectively.

## Commands

Using ChatCop effectively involves understanding the various commands you can use to control its behavior and moderation capabilities. This section will outline each command, provide a description, and offer examples of their usage.

### Core Commands

-   `/mod config start`: Initiates the setup wizard to configure the bot for first-time use.
-   `/mod config info`: Displays the bot’s current configuration settings.
-   `/mod help`: Shows a list of all the commands and their descriptions.

### Moderation Threshold Commands

-   `/mod config warn key:value`: Set the threshold for issuing a warning based on a specific type of behavior.
-   `/mod config delete key:value`: Set the threshold for deleting messages based on a specific type of behavior.

### Log and Channel Configuration

-   `/mod config channel`: Sends a wizard for assigning the channel for the bot to post moderation logs.
-   `/mod history user:user`: See the history of all the actions taken upon a user. This is a premium command, see more under [Premium](#premium).

### Moderation Controls

-   `/mod enable`: Enables the bot’s automatic moderation features.
-   `/mod disable`: Disables the bot’s automatic moderation features.

### Role management
-   `/mod config ignore_role`: Use this command to make ChatCop ignore users with a specific role for automatic moderation. This is particularly useful for exempting certain roles like moderators or VIP members from automated moderation actions. To activate or deactivate this setting for a role, simply run the command with the role specified. You can always see the current status with `/mod config info`.This is a premium command, see more under [Premium](#premium).

### Voting Commands

-   `/vote info`: See how to vote, and your number of premium tokens.
-   `/vote give`: Give two day of premium subscription to the server you run the command in in exchange of one token.

More information under [Premium](#premium).

Each command includes options and parameters that allow for fine control over how ChatCop moderates your server. Understanding and utilizing these commands will empower you to maintain a positive and healthy community.


## Moderation Actions

ChatCop offers a set of moderation tools that automatically handle inappropriate activities on your server according to predefined thresholds and settings.

### Warnings

Messages meeting certain thresholds of toxicity will trigger ChatCop to delete messages, guiding the users towards healthier interaction patterns.

<discord-messages class="discord-messages">
            <discord-message profile="chatcop" highlight>
                <discord-reply slot="reply" profile="deleted-message"><discord-italic>original message was deleted</discord-italic></discord-reply>
                <discord-embed slot="embeds" color="#ed4245" embed-title="Your message got moderated"
                    thumbnail="https://nicebots.xyz/static/assets/featured-bots/ChatCop/profile-picture.png">
                    <discord-embed-description slot="description">
                        Your message was moderated by automoderation. If you believe this was a mistake, please contact the server moderators.
                    </discord-embed-description>
                </discord-embed>
            </discord-message>
        </discord-messages>

### Message Deletion

ChatCop detects and removes messages that violate specified thresholds of toxic behavior like treath or insult, supporting a safer chat environment.

### Timeouts and User Bans

Upon larger infractions, **you** can temporarily restrict user abilities to post messages (timeouts) or, if necessary, remove users from the server thanks to the easy to use buttons below the infraction notifications.

<discord-messages class="discord-messages">
                <discord-message profile="chatcop">
                    <discord-embed slot="embeds" color="#ed4245" embed-title="Deleted message" class="w-full">
                        <discord-embed-description slot="description">
                            <discord-mention>Wumpus</discord-mention>'s message <a href="#" class="italic">Shut up! You are an idiot!</a> in <discord-mention type="channel">general</discord-mention> was deleted.<br>Here are the reasons:<br>
                        </discord-embed-description>
                        <discord-embed-fields slot="fields">
                            <discord-embed-field field-title="TOXICITY">
                                0.9391453
                            </discord-embed-field>
                            <discord-embed-field field-title="INSULT">
                                0.9191143
                            </discord-embed-field>
                        </discord-embed-fields>
                    </discord-embed>
                    <discord-action-row slot="components">
                        <discord-button type="destructive">Timeout 10m</discord-button>
                        <discord-button type="destructive">Timeout 1h</discord-button>
                        <discord-button type="destructive">Timeout 6h</discord-button>
                        <discord-button type="destructive">Timeout 1d</discord-button>
                        <discord-button type="destructive">Kick</discord-button>
                    </discord-action-row>
                    <discord-action-row slot="components">
                        <discord-button type="primary">Warn in DMs</discord-button>
                        <discord-button type="primary">See user history</discord-button>
                    </discord-action-row>
                </discord-message>
            </discord-messages>


### User History Tracking

ChatCop keeps a detailed history of each user’s actions in regard to moderation, allowing server administrators to review previous infractions and actions taken by the bot. This ensures transparency and lets admins make informed decisions for future moderation policies.

This is a premium command, please see [Premium](#premium) to know more.

## Premium

Some commands or features, known as *premium*, need your guild to have an active premium state to work. For this you have two options:

1. Vote for us on top.gg then redeem your tokens in the server you want to upgrade as explained in `/vote info`.
2. *coming soon* Subscribe actively to our service monthly.

## Feedback and Support

If you encounter issues with ChatCop or have suggestions to improve the bot, consider using the following channels for assistance or to share your feedback:

-   [**Discord Support Server**](https://paill.at/sbE4f): The best place for support is our official Discord server. Here, you can get immediate help from the community and the support team.
-   **Email**: For more in-depth inquiries or to convey detailed feedback, email us at [hello@nicebots.xyz](mailto:hello@nicebots.xyz).

Your feedback is valuable as it helps improve ChatCop for everyone. Thank you for contributing to a better moderation experience.

## Frequently Asked Questions (FAQs)

This section addresses some of the most common questions and concerns users might have when using ChatCop.

### General Questions

-   **Q: How do I add ChatCop to my server?**  
    A: Follow [this link](https://paill.at/ILFe2) to invite ChatCop to your server.
    
-   **Q: How can I change the moderation settings?**  
    A: Use the `/mod config` commands to access and modify various moderation settings such as thresholds and notification channels.
    

### Moderation

-   **Q: What does it mean when a message is deleted?**  
    A: ChatCop automatically deletes messages that surpass the configured deletion thresholds for toxic behavior.
    
-   **Q: Can I undo a moderation action taken by ChatCop?**  
    A: While actions like message deletions cannot be undone, you can disable message deletion by setting the delete values to 1 with `/mod config delete`.
    

### Troubleshooting

-   **Q: What if ChatCop is moderating too strictly or too leniently?**  
    A: Fine-tune the warning and deletion thresholds using the `/mod config` commands to adjust how sensitively ChatCop responds to potential infractions.
    
-   **Q: ChatCop is not working as expected, what should I do?**  
    A: Ensure ChatCop has the necessary permissions in your server settings, and that the bot is enabled using `/mod enable` and a notification channel is set with `/mod config channel`. For further assistance, reach out on the [support server](https://paill.at/sbE4f).