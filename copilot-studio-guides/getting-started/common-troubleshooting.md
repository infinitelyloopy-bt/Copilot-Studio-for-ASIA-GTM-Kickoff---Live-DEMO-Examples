# Common Troubleshooting Guide

## 🚨 Most Common Issues and Quick Fixes

### 1. "I can't access Copilot Studio"

**Symptoms:**
- Login page won't load
- "Access denied" messages
- Can't see the create button

**Solutions:**
✅ **Check your URL**: Make sure you're going to https://copilotstudio.microsoft.com
✅ **Verify permissions**: Contact your IT admin to ensure you have Copilot Studio licenses
✅ **Try a different browser**: Use Chrome, Edge, or Firefox
✅ **Clear browser cache**: Clear cookies and cached data
✅ **Check environment**: Make sure you're in the correct organization environment

---

### 2. "My agent doesn't use the knowledge source I added"

**Symptoms:**
- Agent gives generic responses
- Doesn't reference your website or documents
- Says "I don't have information about that"

**Solutions:**
✅ **Wait for processing**: Knowledge sources take 2-5 minutes to be indexed
✅ **Check the URL**: Ensure your website URL is correct and accessible
✅ **Verify content**: Make sure the website actually contains the information you're asking about
✅ **Update instructions**: Add specific instructions to reference the knowledge source
✅ **Test with exact content**: Ask questions about content you know exists on the website

**Example fix for instructions:**
```
When answering questions, always check the Australian Smart Traveller website first 
and reference this official source in your responses.
```

---

### 3. "Knowledge source says 'Failed to process'"

**Symptoms:**
- Red error message when adding knowledge source
- "Processing failed" status
- Knowledge source won't load

**Solutions:**
✅ **Check website accessibility**: Ensure the website is publicly accessible (not behind login)
✅ **Verify URL format**: Use full URL including https://
✅ **Try again later**: Server issues sometimes resolve themselves
✅ **Check file formats**: For uploads, ensure files are PDF, DOCX, PPTX, or TXT
✅ **Reduce file size**: Large files (>200MB) may fail to process

---

### 4. "My agent is too slow to respond"

**Symptoms:**
- Long delays before responses
- Timeout errors
- Users complaining about wait times

**Solutions:**
✅ **First queries are slower**: Initial responses take longer as the system learns
✅ **Reduce knowledge sources**: Too many sources can slow processing
✅ **Simplify instructions**: Shorter, clearer instructions process faster
✅ **Check internet connection**: Slow connections affect response time
✅ **Peak usage times**: Try testing during off-peak hours

---

### 5. "Agent gives wrong or outdated information"

**Symptoms:**
- Information contradicts your knowledge source
- Dates or facts are incorrect
- Responses seem generic

**Solutions:**
✅ **Update knowledge source**: Refresh or re-add the knowledge source
✅ **Check source content**: Verify your knowledge source has current information
✅ **Improve instructions**: Be more specific about using recent information
✅ **Test with specific questions**: Ask about content you know is current
✅ **Consider multiple sources**: Cross-reference with additional reliable sources

---

### 6. "Can't publish my agent"

**Symptoms:**
- Publish button is grayed out
- Error messages during publishing
- Published agent not accessible

**Solutions:**
✅ **Save first**: Always save your agent before attempting to publish
✅ **Complete required fields**: Ensure name and description are filled
✅ **Check permissions**: Verify you have publishing rights in your organization
✅ **Test first**: Use the Test panel to ensure agent works before publishing
✅ **Wait and retry**: Sometimes publishing fails temporarily

---

### 7. "Users can't access my published agent"

**Symptoms:**
- Shared link doesn't work
- Users get "access denied" errors
- Agent not showing up in Teams

**Solutions:**
✅ **Check sharing settings**: Verify agent is published to the correct audience
✅ **Verify permissions**: Ensure users have appropriate licenses
✅ **Test the link**: Try the link yourself in an incognito/private browser
✅ **Check channel settings**: Ensure correct channels are enabled (Teams, Web, etc.)
✅ **Wait for propagation**: Changes can take 10-15 minutes to take effect

---

## 🔧 Step-by-Step Debugging Process

### When Your Agent Isn't Working:

**Step 1: Basic Checks**
1. Is your agent saved?
2. Are there any error messages visible?
3. Does the Test panel work?

**Step 2: Knowledge Source Verification**
1. Go to Knowledge → Check status (should show "Ready")
2. Click on your knowledge source → Verify details
3. Test with a question you know is on the website

**Step 3: Instructions Review**
1. Read your instructions out loud
2. Are they clear and specific?
3. Do they mention using the knowledge source?

**Step 4: Test Systematically**
1. Ask basic questions ("What can you help with?")
2. Ask specific knowledge questions
3. Try different phrasings of the same question

**Step 5: Publishing Check**
1. Save all changes
2. Test in the Test panel first
3. Publish to a small group initially
4. Verify shared links work

---

## 🌐 Browser and Technical Issues

### Supported Browsers
✅ **Fully supported:**
- Microsoft Edge (recommended)
- Google Chrome
- Mozilla Firefox

❌ **Not recommended:**
- Internet Explorer
- Older browser versions
- Mobile browsers for editing

### Browser Settings
✅ **Enable:**
- JavaScript
- Cookies
- Local storage

❌ **Disable temporarily:**
- Ad blockers (can interfere with functionality)
- Strict privacy settings
- VPN (if causing access issues)

---

## 📱 Mobile and Access Issues

### Mobile Limitations
- **Editing**: Use desktop/laptop for creating agents
- **Testing**: Mobile testing has limited functionality
- **Publishing**: Some features not available on mobile

### Network Issues
- **Corporate firewalls**: May block certain features
- **VPN connections**: Can cause slow performance
- **Proxy servers**: May interfere with knowledge source processing

---

## 🔍 Advanced Troubleshooting

### Check Agent Analytics
1. Go to **Analytics** in your agent
2. Look for error patterns
3. Identify common failed queries
4. Use insights to improve instructions

### Knowledge Source Deep Dive
1. **Manual verification**: Visit your knowledge source URL directly
2. **Content check**: Search for specific information manually
3. **Update frequency**: Check when content was last updated
4. **Robot.txt**: Ensure website allows crawling

### Performance Optimization
1. **Streamline instructions**: Remove unnecessary text
2. **Organize knowledge**: Group related information together
3. **Test regularly**: Monitor performance over time
4. **User feedback**: Ask users about their experience

---

## 📞 When to Get Help

### Contact IT Support When:
- You can't access Copilot Studio at all
- License or permission issues
- Network connectivity problems
- Organization-wide access issues

### Contact Microsoft Support When:
- Knowledge sources consistently fail to process
- Persistent technical errors
- Platform-wide performance issues
- Billing or subscription questions

### Self-Help Resources:
- **Microsoft Learn**: Comprehensive documentation
- **Community Forums**: User discussions and solutions
- **YouTube**: Video tutorials
- **Agent Templates**: Working examples to reference

---

## 📝 Error Message Quick Reference

| Error Message | Most Likely Cause | Quick Fix |
|---------------|-------------------|-----------|
| "Access denied" | Permissions issue | Contact IT admin |
| "Processing failed" | Invalid knowledge source | Check URL/file format |
| "Agent not found" | Publishing issue | Re-publish agent |
| "Timeout error" | Network/performance | Retry after a few minutes |
| "Invalid format" | File type issue | Use supported formats (PDF, DOCX, etc.) |
| "Quota exceeded" | Usage limits reached | Contact admin or upgrade plan |

---

## 🎯 Prevention Tips

### Best Practices to Avoid Issues:
1. **Save frequently** - Don't lose your work
2. **Test before publishing** - Catch issues early
3. **Start simple** - Add complexity gradually
4. **Document changes** - Keep track of what works
5. **Regular maintenance** - Check and update knowledge sources
6. **User feedback** - Monitor how people use your agent

### Monthly Maintenance Checklist:
- [ ] Test agent with common questions
- [ ] Check knowledge sources are still accessible
- [ ] Review analytics for error patterns
- [ ] Update instructions based on user feedback
- [ ] Verify published links still work

---

**🔔 Remember**: Most issues are simple fixes! Don't hesitate to try the basic solutions first - they solve 80% of common problems.