# Twilio SMS Compliance Templates

Boilerplate legal documents for Twilio SMS messaging compliance (US regulations).

## What's Included

- **Privacy Policy** (`privacy-policy.md`) - Required data collection and usage disclosure
- **Terms of Service** (`terms-of-service.md`) - SMS program terms including opt-in/opt-out

## How to Use

1. **Copy these templates** to your project
2. **Replace placeholders** with your actual information:
   - `[YOUR_PROGRAM_NAME]` - Name of your SMS service
   - `[YOUR_EMAIL]` - Your support email
   - `[YOUR_PHONE_NUMBER]` - Your Twilio phone number
   - `[YOUR_WEBSITE]` - Your website URL
   - `[DESCRIBE YOUR USE CASE]` - What your SMS service does
   - `[DESCRIBE FREQUENCY]` - How often users receive messages
   - `[OPT_IN_KEYWORD]` - Keyword for SMS opt-in (if applicable)

3. **Host these documents** publicly (GitHub Pages, your website, etc.)
4. **Link to them** in your Twilio campaign registration

## Required Twilio Campaign Fields

When registering your SMS campaign with Twilio, you'll need:

### How do end-users consent? (40-2048 chars)

Example:
```
Users provide explicit consent by configuring their phone number in the application settings.
They acknowledge that they will receive automated SMS notifications about agent task completion,
system alerts, and important updates. Users can opt-out at any time by replying STOP to any message.
```

### Privacy Policy URL

Link to your hosted `privacy-policy.md` (must be publicly accessible)

### Terms and Conditions URL

Link to your hosted `terms-of-service.md` (must be publicly accessible)

### Opt-in Keywords (max 255 characters)

If applicable: `Subscribe, Start` (leave blank if not using keyword opt-in)

### Opt-in Message (20-320 characters)

Example:
```
You are now opted-in to SMS notifications from [YOUR_PROGRAM_NAME]. Reply HELP for help, STOP to cancel. Msg&data rates may apply.
```

## US Compliance Requirements

These templates cover:

- ✅ Clear opt-in consent language
- ✅ Data collection and usage disclosure
- ✅ No third-party marketing sharing
- ✅ **HELP** and **STOP** instructions (in bold)
- ✅ Message frequency disclosure
- ✅ Message/data rates disclaimer
- ✅ Program description
- ✅ Contact information
- ✅ Privacy and data retention policies

## Hosting on GitHub Pages

To make these publicly accessible:

```bash
# Enable GitHub Pages in repo settings > Pages > Source: main branch
# Your documents will be available at:
# https://YOUR_USERNAME.github.io/YOUR_REPO/privacy-policy
# https://YOUR_USERNAME.github.io/YOUR_REPO/terms-of-service
```

## License

CC0 1.0 Universal (Public Domain)

Use these templates freely for your Twilio SMS compliance needs.
