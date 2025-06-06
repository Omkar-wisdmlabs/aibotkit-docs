# Adding Chatbots to Your Website

## Methods to Add Chatbots

### Widget Mode

* Configure position, initial state, and display conditions.
* Enable the global widget in AI BotKit > Settings.
* Select the chatbot to display.

IMAGE

### Page-Specific Widget

* Use shortcode in page/post content:

```
[ai_botkit_widget id="YOUR_CHATBOT_ID"]
```

IMAGE

### Inline Mode

* Embed chatbot directly using shortcode

```
[ai_botkit_chat id="YOUR_CHATBOT_ID"]
```

### Gutenberg Editor

{% stepper %}
{% step %}
Add a new block
{% endstep %}

{% step %}
Search for "AI BotKit Chat"
{% endstep %}

{% step %}
Select your chatbot and customize its appearance
{% endstep %}
{% endstepper %}

### Classic Editor

Paste the shortcode where you want the chat to appear

### Customization Parameters

id (required): The chatbot's unique ID.
