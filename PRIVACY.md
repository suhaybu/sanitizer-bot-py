# Privacy Policy

Last updated: February 17, 2025

## Overview

Sanitizer Bot ("the Bot") is committed to protecting user privacy. This Privacy Policy explains how we handle information when you use our Discord bot.

## Information We Process

The Bot processes the following information:
- Message content containing URLs from supported platforms (Twitter/X, Instagram, TikTok)
- Basic Discord message metadata required for bot functionality

## How We Use Information

The Bot:
1. Reads messages in channels where it has been granted access
2. Processes messages only to identify and convert supported platform links
3. Responds with converted links that are embed-friendly
4. Manages server-specific settings through Redis (only stores server configuration, not user data)

## Information We DO NOT Collect

The Bot does not:
- Store or log any user messages
- Track user behavior or analytics
- Collect personal information
- Maintain message history
- Store parsed URLs
- Create user profiles
- Share data with third parties

## Data Storage

- Server Settings: The Bot stores only server-specific configuration in Redis (sanitizer mode, delete permissions, embed visibility settings)
- Message Processing: All message processing is done in-memory and immediately discarded
- No Logs: The Bot does not maintain logs of processed messages or user interactions

## Third-Party Services

The Bot interacts with:
- FxTwitter for Twitter/X links
- QuickVids API for TikTok and Instagram links
- DDInstagram as a fallback for Instagram links

These services are used solely for link conversion and do not receive any user data beyond the URLs being converted.

## User Rights

Users have the right to:
- Review the bot's source code on GitHub
- Configure server-specific settings
- Remove the bot from their server at any time
- Request clarification about data handling

## Data Security

We maintain data security by:
- Processing all data in-memory
- Using secure API connections
- Not storing sensitive information
- Following Discord's security best practices

## Changes to Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last updated" date at the top of this policy.

## Open Source

The Bot is open source under the MIT License. Users can:
- Inspect the code to verify privacy practices
- Deploy their own instance of the bot
- Contribute improvements to privacy features

## Contact

For privacy-related questions, users can:
- Open an issue on GitHub
- Contact the maintainers through Discord
- Reach out via Twitter [@suhayb_u](https://twitter.com/suhayb_u)

## Compliance

While the Bot is designed to respect user privacy, it is not specifically designed to comply with any particular privacy regulation (GDPR, CCPA, etc.) as it does not collect or store personal data.

---

This Privacy Policy should be read alongside our Terms of Service. By using the Bot, you acknowledge that you have read and understood this Privacy Policy.
