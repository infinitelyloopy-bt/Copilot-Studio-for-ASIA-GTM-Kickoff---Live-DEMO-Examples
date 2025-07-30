# Step-by-Step Guide: Creating a Microsoft Fabric Sales Expert Agent

## 📋 Prerequisites Checklist

Before you start, make sure you have:
- [ ] Access to Microsoft Copilot Studio (https://copilotstudio.preview.microsoft.com/)
- [ ] Access to Microsoft Copilot Studio (https://copilotstudio.microsoft.com)
- [ ] Permission to create agents in your organization
- [ ] A web browser (Chrome, Edge, or Firefox recommended)
- [ ] Basic familiarity with Microsoft Fabric (helpful but not required)

## 🚀 Step 1: Access Microsoft Copilot Studio

1. **Open your web browser** and navigate to: https://copilotstudio.microsoft.com
2. **Sign in** with your Microsoft work or school account
3. **Select your environment** (usually your organization's name) from the dropdown at the top

## 🎯 Step 2: Create a New Agent

1. **Click "Create"** in the left navigation menu
2. **Select "New agent"** from the options
3. **Choose "Skip to configure"** (we'll set up everything manually for sales optimization)

## ✏️ Step 3: Configure Basic Agent Settings

### Agent Name and Description
1. **Agent Name**: Type `Microsoft Fabric Sales Expert`
2. **Description**: Copy and paste this text:
	A sales-focused AI expert that helps field salespeople and go-to-market managers with Microsoft Fabric customer conversations, positioning, pricing, and competitive responses using official Microsoft documentation.

### Agent Instructions
3. **Instructions**: Copy and paste this text:
	You are a Microsoft Fabric Sales Expert designed specifically for field salespeople and go-to-market managers. Your role is to help sales teams have confident, informed conversations with customers and prospects about Microsoft Fabric.
	
	SALES-FOCUSED APPROACH:
	- Always frame responses in terms of business value and customer outcomes
	- Use simple, customer-friendly language (avoid technical jargon)
	- Provide competitive positioning when relevant
	- Include ROI and cost-benefit perspectives
	- Suggest follow-up questions sales reps can ask customers
	
	RESPONSE STYLE:
	- Keep responses concise but comprehensive
	- Lead with the most important business benefit
	- Use bullet points for easy scanning
	- Include specific examples when possible
	- End with actionable next steps for the salesperson
	
	KEY FOCUS AREAS:
	- Business value and ROI of Microsoft Fabric
	- Pricing and licensing guidance for different scenarios
	- Competitive positioning against other data platforms
	- Industry-specific use cases and success stories
	- Addressing common customer objections
	- Technical capabilities explained in business terms
	
	ALWAYS REFERENCE: Use the official Microsoft Fabric documentation as your primary source and mention when information comes from Microsoft's official docs to build credibility.
	
	Remember: You're supporting sales conversations, not technical implementations. Focus on helping sales teams sell effectively.

4. **Click "Create"** to create your agent

## 🌐 Step 4: Add Microsoft Fabric Documentation as Knowledge Source

### Navigate to Knowledge Section
1. **Click "Knowledge"** in the left menu of your agent
2. **Click "Add knowledge source"**
3. **Select "Public websites"** from the options

### Add the Microsoft Fabric Documentation
4. **Website URL**: Enter exactly: `https://learn.microsoft.com/en-us/fabric/`
5. **Website Name**: Type `Microsoft Fabric Official Documentation`
6. **Description**: Type `Official Microsoft Fabric documentation covering platform capabilities, pricing, licensing, and technical details`

### Confirm and Add
7. **Click "Add"** to add the knowledge source
8. **Wait** for the system to process the website (this may take 5-10 minutes due to the size of the documentation)
9. **Verify** that you see "Microsoft Fabric Official Documentation" listed under your knowledge sources with "Ready" status

## 🔧 Step 5: Configure Agent Settings for Sales Use

### General Settings
1. **Click "Settings"** in the left menu
2. **Go to "General"** tab
3. **Agent language**: Ensure "English" is selected
4. **Conversation starts**: Set to "A greeting"

### Security Settings
5. **Click "Security"** tab
6. **Authentication**: Select "Authenticate with Microsoft" (to ensure only your sales team can access)

### Advanced Settings
7. **Click "Advanced"** tab
8. **Web search**: Turn this **ON** (allows access to latest Fabric updates and competitive information)
9. **Generative answers**: Ensure this is **ON**

## 🧪 Step 6: Test Your Agent with Sales Scenarios

### Test Customer Value Questions
1. **Click "Test"** button in the top right corner
2. **Type this sales-focused test question**: 
	How do I explain Microsoft Fabric's value to a CTO who's currently using Snowflake and Tableau?
3. **Press Enter** and wait for the response
4. **Verify** that the agent provides business-focused positioning advice

### Test Pricing Questions
Try this pricing-related question:
	A customer has 500 Power BI users - what's the most cost-effective Fabric licensing approach?

### Test Competitive Positioning
Try this competitive question:
	How does Fabric compare to AWS data platforms for a retail customer?

## 📊 Step 7: Fine-Tune for Sales Excellence

### Check Response Quality
1. **Review the responses** - Are they sales-focused and business-oriented?
2. **Verify official sourcing** - Does the agent reference Microsoft documentation?
3. **Test objection handling** - Try common customer objections

### Refine Instructions (if needed)
If responses are too technical or not sales-focused enough:
1. **Go back to agent settings**
2. **Edit the Instructions** to emphasize business value more
3. **Add specific guidance** about your sales process or industry focus
4. **Re-test** after making changes

## 🎯 Step 8: Add Sales Team Context (Optional)

### Customize for Your Organization
You can enhance the agent by adding context about your specific sales scenarios:

1. **Edit Instructions** to include:
	ADDITIONAL CONTEXT:
	- Our primary competitors are [list main competitors]
	- Our typical customers are [describe your customer profile]
	- Key objections we hear are [list common objections]
	- Our sales process focuses on [describe your approach]

## 🚀 Step 9: Publish Your Sales Agent

### Publish for Testing
1. **Click "Publish"** in the top right corner
2. **Select "Publish"** to make it available
3. **Choose your publication scope**:
   4. **Teams and Copilot**: For Microsoft Teams integration
   5. **Web**: For web-based access
   6. **Both**: For maximum accessibility

### Get Shareable Link
4. **After publishing**, click "Channels" in the left menu
5. **Select "Custom website"** 
6. **Copy the provided URL** to share with your sales team

## ✅ Step 10: Sales Team Rollout

### Test with Sales Team
1. **Share the agent link** with a small group of sales reps first
2. **Provide training** on how to use the agent effectively
3. **Gather feedback** on response quality and usefulness

### Create Sales Team Guidelines
Provide your team with these usage tips:
	BEST PRACTICES FOR USING THE FABRIC SALES EXPERT:
	
	✅ DO:
	- Ask specific customer scenarios
	- Request competitive positioning help
	- Get pricing guidance for customer situations
	- Use it to prepare for customer meetings
	- Ask for objection handling advice
	
	❌ DON'T:
	- Use it for technical implementation details
	- Share customer-specific confidential information
	- Rely solely on the agent - verify critical details
	- Use outdated pricing information without checking latest docs

## 🎉 Congratulations!

You've successfully created a Microsoft Fabric Sales Expert Agent! Your sales team can now:
- ✅ Get instant, accurate information about Microsoft Fabric
- ✅ Position Fabric effectively against competitors
- ✅ Handle customer pricing and licensing questions confidently
- ✅ Access business-focused explanations of technical capabilities
- ✅ Prepare for customer meetings with up-to-date information

## 🚀 Advanced Sales Team Features

### Integration Options
1. **Microsoft Teams**: Pin the agent in your sales team channels
2. **CRM Integration**: Consider integrating with your CRM system
3. **Mobile Access**: Sales reps can access via mobile for field use
4. **Bookmarks**: Add to browser favorites for quick access

### Training Program
Create a sales enablement program:
1. **Onboarding**: Include agent training in new hire onboarding
2. **Role-Playing**: Use agent responses in sales training scenarios
3. **Best Practices**: Share successful agent interaction examples
4. **Regular Updates**: Keep team informed about new Fabric features

## 🔄 Ongoing Maintenance

### Monthly Review Tasks
- [ ] Test agent with new competitive scenarios
- [ ] Update instructions based on sales team feedback
- [ ] Verify knowledge source is still current
- [ ] Review analytics for usage patterns
- [ ] Add new competitive positioning as needed

### Quarterly Enhancements
- [ ] Add new Fabric features and capabilities
- [ ] Update pricing information if changed
- [ ] Incorporate successful sales objection responses
- [ ] Expand industry-specific use cases

## 🆘 Troubleshooting for Sales Teams

### Common Sales-Specific Issues

**Problem**: Agent responses are too technical for customer conversations
- **Solution**: Refine instructions to emphasize business language and customer value

**Problem**: Pricing information seems outdated
- **Solution**: Check that web search is enabled and knowledge source is current

**Problem**: Competitive positioning isn't strong enough
- **Solution**: Add specific competitive guidance to the agent instructions

**Problem**: Sales team isn't using the agent
- **Solution**: Provide training and show specific use cases relevant to their deals

### Sales Manager Support
- Monitor agent usage through analytics
- Gather feedback from sales team regularly  
- Update agent based on common customer questions
- Share successful usage examples with the team

---

**🎯 Pro Tip for Sales Managers**: Create a "Question of the Week" where you ask the agent a common customer question and share the response with your sales team. This builds familiarity and demonstrates value!