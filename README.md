# 📝 testarium-issues

The official Testarium GitHub page for submitting issues

## 🎯 What is a Good GitHub Issue?

A well-written GitHub issue helps maintainers and contributors understand and address problems efficiently. Good issues are:

- **Clear and concise** 💬 - Get to the point without unnecessary details
- **Reproducible** 🔄 - Include steps others can follow to see the same problem
- **Well-structured** 📋 - Organized with headers and formatting
- **Actionable** ✅ - Provide enough information for someone to fix it

## 📚 How to Write a Proper GitHub Issue

### 1. **Choose a Descriptive Title** 🏷️

Your title should summarize the issue in one line:

✅ **Good:** "Login button doesn't respond on mobile Safari"  
❌ **Bad:** "Button broken" or "Help!!!"

### 2. **Provide Context** 📖

Start with a brief description of what you were trying to do and what went wrong:

```markdown
I was trying to log into the application using the login button on the homepage, 
but nothing happens when I click it on mobile Safari.
```

### 3. **Include Steps to Reproduce** 🔢

List the exact steps someone can follow to see the issue:

```markdown
**Steps to Reproduce:**
1. Open the application on mobile Safari (iOS 16)
2. Navigate to the login page
3. Enter valid credentials
4. Click the "Login" button
5. Observe that nothing happens
```

### 4. **Describe Expected vs. Actual Behavior** 🎭

Be clear about what should happen versus what actually happens:

```markdown
**Expected Behavior:** 🎯
The user should be redirected to the dashboard after clicking login.

**Actual Behavior:** ❌
The button doesn't respond to clicks. No error message is shown.
```

### 5. **Add Environment Details** 💻

Include relevant system and version information:

```markdown
**Environment:**
- Browser: Safari 16.0
- Device: iPhone 13
- OS: iOS 16.1
- App Version: 2.4.0
```

### 6. **Include Screenshots or Videos** 📸

Visual evidence helps others understand the issue quickly:

```markdown
![Screenshot of the issue](screenshot.png)
```

### 7. **Add Error Messages or Logs** 🐛

If applicable, include any error messages or console logs:

```markdown
**Console Error:**
```
Uncaught TypeError: Cannot read property 'click' of undefined
```
```

### 8. **Suggest Possible Solutions** 💡

If you have ideas on how to fix it, share them (but this is optional):

```markdown
**Possible Solution:**
The click event listener might not be properly attached on mobile devices.
Consider using touch events or checking the event binding code.
```

## ✨ Best Practices

### Do's ✅

- **Search first** 🔍 - Check if someone already reported the issue
- **One issue per report** 1️⃣ - Don't combine multiple unrelated problems
- **Use labels** 🏷️ - Add appropriate labels (bug, enhancement, question, etc.)
- **Be respectful** 🤝 - Remember there are people on the other side
- **Follow up** 💬 - Respond to questions and update if the issue is resolved
- **Use markdown formatting** ✍️ - Make your issue easy to read

### Don'ts ❌

- **Don't be vague** - "It doesn't work" isn't helpful
- **Don't SHOUT** - Avoid ALL CAPS or excessive punctuation!!!
- **Don't demand** - Request politely; maintainers are often volunteers
- **Don't post sensitive data** 🔒 - Remove passwords, tokens, or personal info
- **Don't spam** - Bumping issues repeatedly doesn't help

## 📋 Issue Template Example

Here's a complete example you can follow:

```markdown
## 🐛 Bug Report

**Title:** Search functionality returns incorrect results for special characters

### Description
The search feature doesn't properly handle special characters like @, #, or &.
When searching for terms containing these characters, no results are returned
even though matching items exist.

### Steps to Reproduce
1. Navigate to the search page
2. Enter a search term with special characters (e.g., "user@email")
3. Press Enter or click Search
4. Observe the results

### Expected Behavior 🎯
Search should return all items matching "user@email"

### Actual Behavior ❌
Search returns "No results found" even though matching items exist

### Environment 💻
- Browser: Chrome 118.0
- OS: Windows 11
- App Version: 3.2.1

### Screenshots 📸
[Attach screenshot here]

### Additional Context
This issue started after the v3.2.0 update. The search worked fine
in v3.1.5.

### Possible Solution 💡
The search input might need to escape special characters before
querying the database.
```

## 🎨 Using Emojis

Emojis make issues more readable and engaging! Here are some useful ones:

- 🐛 Bug reports
- ✨ Feature requests
- 📝 Documentation
- 🔧 Maintenance/refactoring
- ⚡ Performance improvements
- 🔒 Security issues
- ❓ Questions
- 💡 Ideas/suggestions
- 📸 Screenshots
- ✅ Resolved/completed
- ❌ Problem/error
- 🎯 Expected behavior
- 💻 Environment/technical details
- 🔍 Investigation needed

## 🤝 Contributing

Good issues help everyone! By following these guidelines, you make it easier
for maintainers to understand and fix problems quickly.

**Remember:** A well-written issue is the first step toward a solution! 🚀

---

📬 **Questions?** Feel free to open an issue (following the guidelines above!)
and we'll be happy to help.
