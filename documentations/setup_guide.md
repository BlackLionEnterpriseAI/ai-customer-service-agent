# Setup Guide

1. Choose your platform:
   - ManyChat, GHL, website chat, WhatsApp, etc.

2. Import or recreate the conversation flow:
   - Greeting
   - FAQ lookup
   - Escalation logic
   - End of conversation

3. Insert prompts:
   - Copy `system_prompt.txt` into your AI configuration.
   - Copy `tone_prompt.txt` and `fallback_prompt.txt` as needed.

4. Add FAQ content:
   - Work with the client to fill `scripts/faq_examples.txt` with real answers.

5. Integration:
   - Connect your CRM/helpdesk (see integrations folder).

6. Test:
   - Run several test conversations.
   - Check escalation, FAQs, and tone.

7. Deploy:
   - Turn the bot live on the website, IG, FB, or WhatsApp.
