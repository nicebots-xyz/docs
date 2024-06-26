---
title: ChatCop Bot Wiki
description: Wiki on how to use the ChatCop discord bot
published: true
date: 2024-06-26T18:52:35.200Z
tags: 
editor: markdown
dateCreated: 2024-04-13T17:42:30.968Z
---

# ChatCop Wiki

Welcome to the updated and comprehensive ChatCop Bot Documentation. Here, we provide detailed guidance to help you seamlessly integrate ChatCop into your Discord server, ensuring a safe, respectful, and engaging community environment. ChatCop, with its sophisticated moderation capabilities, offers a wide range of customizable settings to match your server's unique culture and rules. Whether you're looking to fine-tune automatic moderation or leverage manual controls for specific situations, this documentation will assist you every step of the way.

## Introduction

ChatCop is an advanced Discord moderation bot designed to automate and enhance the moderation process on your server. It utilizes sophisticated algorithms to detect and act upon various forms of inappropriate content, helping maintain a positive and inclusive community atmosphere. From spam and toxicity to more nuanced behavioral moderation, ChatCop offers a plethora of features tailored to your server's needs.

With the introduction of ChatCop Boost, our premium subscription plan, we've expanded our feature set to include even more powerful tools for server administrators who require additional control and customization. These features, marked with a 🚀 emoji throughout this documentation, are designed to elevate your moderation capabilities to new heights.

Our commitment to continuous improvement means that your feedback directly influences future updates and features. We invite you to become an active participant in the ChatCop community, helping us shape the future of Discord moderation.

## Quick Setup

Setting up ChatCop on your server is a straightforward process designed to get you up and running in no time. Follow these steps to quickly integrate ChatCop into your community:

1. **Invite ChatCop to Your Server**: Begin by adding ChatCop to your server using [this invitation link](https://paill.at/Lk03X). The link will guide you through the necessary permissions ChatCop requires to effectively moderate your server.

2. **Initiate the Setup Wizard**: Once ChatCop is part of your server, it's time to configure it to suit your moderation needs. Type `/mod config start` in a server channel to launch the interactive setup wizard. This step-by-step guide will help you through the initial configuration process, covering basic settings such as moderation sensitivity and notification preferences.

3. **Customize Your Settings**: With the initial setup complete, ChatCop will begin moderating your server using its default settings. However, every community is unique, and we encourage you to dive into the various configuration options available to tailor ChatCop's behavior to your server's specific requirements. This includes adjusting moderation thresholds, setting up log channels, and more.

4. **Explore Advanced Features with ChatCop Boost**: For servers requiring advanced moderation tools and greater customization, consider exploring ChatCop Boost. This premium subscription unlocks a suite of powerful features designed to give you unparalleled control over your server's moderation. From role-specific moderation exemptions to detailed user history tracking, ChatCop Boost empowers you to maintain a safe and welcoming community with ease.

By following these simple steps, you'll have ChatCop configured and ready to assist with your server's moderation tasks, allowing you to focus on building and engaging with your community.

## Commands Overview

ChatCop is equipped with a wide array of commands designed to give you full control over the moderation of your server. These commands are categorized for ease of use, ensuring you can quickly find and execute the specific function you need. Below, we provide detailed explanations of each command category and its associated commands.

### Configuration Commands

Configuration commands allow you to tailor ChatCop to your server's specific needs, from setting basic moderation parameters to customizing advanced behaviors. Each command under this category is designed to fine-tune how ChatCop operates within your community.

- `/mod config start`: Initiates the ChatCop setup wizard, guiding you through the initial configuration process. This is the first step in customizing ChatCop to align with your server's moderation policies.

- `/mod config thresholds [mode: warn/delete] [type: spam/toxicity/etc.] [value]`: Adjusts the sensitivity thresholds for various types of content, such as spam or toxicity. These thresholds determine when ChatCop should issue warnings or delete messages. You can specify whether the threshold applies to warnings (`warn`) or deletions (`delete`) and the type of content it pertains to.

- `/mod config channel [channel]`: Designates a specific channel where ChatCop will post moderation logs and notifications. This keeps your team informed about moderation actions and significant events.

- `/mod config ignore_role [role]` 🚀: Excludes members with a specified role from ChatCop's automatic moderation. This is particularly useful for roles such as moderators or VIPs whom you wish to exempt from certain auto-moderation rules.

- `/mod config ping_mods [on/off]` 🚀: Toggles the feature to notify moderators every time ChatCop takes a moderation action. This ensures your moderation team is always in the loop and can respond swiftly to incidents.

- `/mod config reply_on_delete [on/off]` 🚀: Enables or disables automatic replies from ChatCop when it deletes a message. This helps communicate the reason for deletion to the community, maintaining transparency in moderation actions.

- `/mod config advanced_warn [type: spam/toxicity/etc.] [value]` 🚀: Sets custom warning thresholds for specific behaviors, offering fine-grained control over when users receive warnings.

- `/mod config advanced_delete [type: spam/toxicity/etc.] [value]` 🚀: Establishes custom deletion thresholds for particular types of content, allowing for precise moderation based on your community standards.

### Misc Commands

Miscellaneous commands provide additional functionalities and access to information about ChatCop and its features.

- `/mod help`: Displays a comprehensive list of all available ChatCop commands, including a brief description of each. This is your go-to resource for quick command reference.

### ChatCop Boost Commands

ChatCop Boost commands unlock the full potential of ChatCop's moderation capabilities. These advanced features, accessible through a Boost subscription, offer unparalleled control and customization for server administrators.

- `/boost vote info`: Provides information on how to support ChatCop through community voting and the benefits it brings, including access to ChatCop Boost features.

- `/boost vote give`: Give two days of boost features to your server after voting for it with `/boost vote info`

- `/boost subscribe`: Offers details on subscribing to ChatCop Boost, including pricing and the additional features it unlocks. This command also guides you through the process of activating your ChatCop Boost subscription.

🚀 **Legend:** Commands marked with a 🚀 emoji are exclusive to ChatCop Boost subscribers, offering advanced features for enhanced server moderation.

With these commands at your disposal, you're equipped to leverage ChatCop's full suite of moderation tools, ensuring a safe and engaging environment for your community. Whether you're fine-tuning automatic moderation settings or accessing advanced features through ChatCop Boost, this command guide will help you maintain control over your server's discourse.
## Feedback and Support

Your experience with ChatCop and the safety of your community are our top priorities. If you encounter any issues or have suggestions for improvements, we're here to help and listen. Below are the channels through which you can seek support or provide feedback:

- **Discord Support Server**: Join our [official Discord server](https://paill.at/sbE4f) for immediate support and assistance. This platform allows you to interact directly with our support team and fellow ChatCop users, ensuring you get the help you need promptly.

- **Email Support**: For more detailed inquiries or to share in-depth feedback, you can reach out to us via email at [hello@nicebots.xyz](mailto:hello@nicebots.xyz). Our team is dedicated to providing thorough responses to all your questions and concerns.

We encourage you to utilize these resources not only for support but also to share your experiences and suggestions. Your feedback is invaluable in shaping the future of ChatCop, helping us enhance its capabilities and ensure it meets the evolving needs of Discord communities.

## Frequently Asked Questions (FAQs)

### General Questions

- **Q: How do I get started with ChatCop on my server?**
  - A: Simply invite ChatCop to your server using [this invitation link](https://paill.at/Lk03X), and use the `/mod config start` command to begin the setup wizard. This will guide you through the initial configuration process.

- **Q: Can ChatCop moderate messages in real-time?**
  - A: Yes, ChatCop is designed to monitor and moderate chat messages in real-time, based on the thresholds and settings you've configured.

- **Q: Is ChatCop capable of moderating voice chats?**
  - A: ChatCop primarily focuses on text chat moderation. Monitoring voice chats involves different challenges and privacy concerns, which are currently beyond ChatCop's scope.

### Configuration and Usage

- **Q: How do I customize ChatCop's moderation settings for my server?**
  - A: Use the `/mod config` commands to adjust various settings such as moderation thresholds, log channels, and more. This allows you to tailor ChatCop's behavior to your server's specific needs.

- **Q: Can ChatCop ignore specific roles or channels during moderation?**
  - A: Yes, with ChatCop Boost, you can use the `/mod config ignore_role` command to exempt specific roles from automatic moderation. Channels can be managed by adjusting the bot's permissions within your server settings.

- **Q: How can I view a user's moderation history?**
  - A: ChatCop Boost subscribers can use the `/mod history user` command to access a detailed log of a user's infractions and actions taken by ChatCop.

### ChatCop Boost

- **Q: What additional features does ChatCop Boost offer?**
  - A: ChatCop Boost provides advanced features such as role-specific moderation exemptions, mod notifications, user history tracking, and customizable thresholds for warnings and deletions.

- **Q: How can I subscribe to ChatCop Boost or access it for free?**
  - A: You can subscribe to ChatCop Boost using the `/boost subscribe` command. Alternatively, you can support ChatCop through community voting and redeem voting rewards for ChatCop Boost access as explained in the `/boost vote info` command.

### Troubleshooting

- **Q: What should I do if ChatCop is not moderating as expected?**
  - A: First, ensure that ChatCop has the necessary permissions in your server. Check your configuration settings with `/mod config info` and adjust as needed. If issues persist, reach out for support on our [Discord server](https://paill.at/sbE4f) or via email.

- **Q: How can I report a bug or suggest a feature for ChatCop?**
  - A: We welcome bug reports and feature suggestions! Please share them on our [Discord support server](https://paill.at/sbE4f) or send us an email. Your input helps us improve ChatCop for everyone.

These FAQs are designed to address common questions and concerns about ChatCop. However, if your question isn't covered here or you need further assistance, please don't hesitate to contact us through the support channels provided. We're committed to ensuring your experience with ChatCop is as smooth and effective as possible.