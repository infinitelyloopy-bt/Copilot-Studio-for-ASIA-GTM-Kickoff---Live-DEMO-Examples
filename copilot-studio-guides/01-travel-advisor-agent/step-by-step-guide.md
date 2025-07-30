# Step-by-Step Guide: Creating an Australian Travel Advisor Agent

## 📋 Prerequisites Checklist

Before you start, make sure you have:
- [ ] Access to Microsoft Copilot Studio (https://copilotstudio.preview.microsoft.com/)
- [ ] Access to Microsoft Copilot Studio (https://copilotstudio.microsoft.com)
- [ ] Permission to create agents in your organization
- [ ] A web browser (Chrome, Edge, or Firefox recommended)

## 🚀 Step 1: Access Microsoft Copilot Studio

1. **Open your web browser** and navigate to: https://copilotstudio.microsoft.com
2. **Sign in** with your Microsoft work or school account
3. **Select your environment** (usually your organization's name) from the dropdown at the top

## 🎯 Step 2: Create a New Agent

1. **Click "Create"** in the left navigation menu
2. **Select "New agent"** from the options
3. **Choose "Skip to configure"** (we'll set up everything manually for better control)

## ✏️ Step 3: Configure Basic Agent Settings

### Agent Name and Description
1. **Agent Name**: Type `Australian Travel Advisor`
2. **Description**: Copy and paste this text:
	An intelligent travel advisor that provides up-to-date safety information and travel advice for international destinations using official Australian government sources.

### Agent Instructions
3. **Instructions**: Copy and paste this text:
	You are an Australian Travel Advisor agent that helps users get reliable, up-to-date travel information and safety advice. You should:
	
	- Provide current travel advisories and safety information for international destinations
	- Help users understand travel risks and safety considerations
	- Offer advice on health requirements, entry restrictions, and local conditions
	- Always reference official Australian government travel advice
	- Be helpful and informative while emphasizing the importance of checking for the most current information
	- If asked about specific travel dates, consider seasonal factors and current conditions
	- Encourage users to register with Smartraveller.gov.au for travel updates
	
	Always maintain a professional, helpful tone and provide practical, actionable advice.

4. **Click "Create"** to create your agent

## 🌐 Step 4: Add the Australian Smart Traveller Website as Knowledge Source

### Navigate to Knowledge Section
1. **Click "Knowledge"** in the left menu of your agent
2. **Click "Add knowledge source"**
3. **Select "Public websites"** from the options

### Add the Smart Traveller Website
4. **Website URL**: Enter exactly: `https://www.smartraveller.gov.au`
5. **Website Name**: Type `Australian Smart Traveller`
6. **Description**: Type `Official Australian government travel advice and safety information`

### Confirm and Add
7. **Click "Add"** to add the knowledge source
8. **Wait** for the system to process the website (this may take 2-3 minutes)
9. **Verify** that you see "Australian Smart Traveller" listed under your knowledge sources

## 🔧 Step 5: Configure Agent Settings

### General Settings
1. **Click "Settings"** in the left menu
2. **Go to "General"** tab
3. **Agent language**: Ensure "English" is selected
4. **Conversation starts**: Set to "A greeting"

### Security Settings
5. **Click "Security"** tab
6. **Authentication**: Keep as "No authentication" (for public use) or select "Authenticate with Microsoft" (for internal use only)

### Advanced Settings
7. **Click "Advanced"** tab
8. **Web search**: Turn this **ON** (this allows the agent to get more current information when needed)
9. **Generative answers**: Ensure this is **ON**

## 🧪 Step 6: Test Your Agent

### Test in the Test Panel
1. **Click "Test"** button in the top right corner
2. **Type this test question**: 
	I want to plan a travel to South Korea in August 2025. Is it safe for me to go there and are there any considerations I need to be aware of?
3. **Press Enter** and wait for the response
4. **Verify** that the agent provides information about South Korea travel advice

### Additional Test Questions
Try these additional questions to ensure your agent is working properly:

	What are the current travel warnings for Thailand?

	Are there any health requirements for traveling to Japan?

	What should I know about traveling to Indonesia during monsoon season?

## 📊 Step 7: Review and Refine

### Check Agent Performance
1. **Review the responses** - Are they helpful and accurate?
2. **Check knowledge source usage** - Does the agent reference Smart Traveller information?
3. **Test edge cases** - Try asking about lesser-known countries

### Make Adjustments (if needed)
If responses aren't satisfactory:
1. **Go back to "Instructions"** and refine the prompt
2. **Check "Knowledge"** to ensure the website was properly indexed
3. **Re-test** after making changes

## 🚀 Step 8: Publish Your Agent

### Publish for Testing
1. **Click "Publish"** in the top right corner
2. **Select "Publish"** to make it available
3. **Choose your publication scope**:
   4. **Teams and Copilot**: For internal Microsoft Teams use
   5. **Web**: For web-based access
   6. **Mobile app**: For mobile access

### Get Shareable Link
4. **After publishing**, click "Channels" in the left menu
5. **Select "Custom website"** 
6. **Copy the provided URL** to share with your team

## ✅ Step 9: Final Testing

### Test the Published Agent
1. **Open the shareable link** in a new browser tab
2. **Test with the sample questions** from Step 6
3. **Verify everything works as expected**

### Share with Your Team
4. **Send the link** to your colleagues
5. **Provide them with sample questions** to test
6. **Gather feedback** for future improvements

## 🎉 Congratulations!

You've successfully created an Australian Travel Advisor Agent! Your agent can now:
- ✅ Provide up-to-date travel advice using official Australian government sources
- ✅ Answer questions in natural language
- ✅ Help users make informed travel decisions
- ✅ Reference current travel advisories and safety information

## 🔄 Next Steps

1. **Monitor usage** through the Copilot Studio analytics
2. **Gather user feedback** and refine instructions if needed
3. **Consider adding more knowledge sources** for comprehensive travel advice
4. **Explore additional features** like conversation flows for specific use cases

## 🆘 Troubleshooting

### Common Issues and Solutions

**Problem**: Agent doesn't reference Smart Traveller website
- **Solution**: Check that the knowledge source was properly added and indexed. Try removing and re-adding the website.

**Problem**: Responses are too generic
- **Solution**: Refine the agent instructions to be more specific about referencing the knowledge source.

**Problem**: Can't access the published agent
- **Solution**: Check your publishing settings and ensure you have the correct permissions.

**Problem**: Agent takes too long to respond
- **Solution**: This is normal for the first few queries as the system learns. Performance typically improves with use.

### Need More Help?

- Check the `getting-started/common-troubleshooting.md` file for additional support
- Visit the Microsoft Copilot Studio documentation
- Contact your IT administrator for permissions issues

---

**🎯 Pro Tip**: Bookmark the agent URL and add it to your browser favorites for quick access to travel advice!