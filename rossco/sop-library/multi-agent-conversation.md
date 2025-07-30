
# 🧠 SOP: Talking to Multiple Agents + Creating SharePoint Sites with HUEY

## 📍 Purpose
This Standard Operating Procedure (SOP) explains how any team member can interact with multiple AI agents (like HUEY and Edith Marie) and how to instruct HUEY to set up a SharePoint site for your needs.

---

## 🧑‍💼 Who This Is For
- Interns, managers, owners (Ross, Jeff)
- Advisors and collaborators
- Anyone authorized to use internal GPT agents

---

## 🤖 Agents Involved
- **@huey** – AI expert in SharePoint, Office 365, and internal tools
- **@edith-marie** – FTIR machine expert and training guide
- (Others may be added in the future)

---

## 🪜 Steps to Run a Multi-Agent Conversation

### ✅ 1. Choose Your Conversation Format
You can use either:
- GitHub markdown files (e.g. builder-chat.md, edith-marie.md)
- ChatGPT/OpenAI with `@agent-name >> your message` format

### ✅ 2. Tag Agents Clearly
Use the `@` tag format to direct a message to a specific agent.

#### Example:
```
@huey >> Create a SharePoint site for the FTIR training dashboard.
@edith-marie >> What files should go in the FTIR training dashboard?
```

### ✅ 3. Wait for Each Agent’s Response
You can ask multiple agents in the same conversation, just tag them individually.

---

## 🏗️ Having HUEY Create a SharePoint Site

### 🛠️ Step-by-Step Instruction Template

```
@huey >> Create a new SharePoint site called 'FTIR Training Hub'.
Include:
- A homepage with a welcome message
- A section for SOPs
- A document library called 'FTIR Files'
- Access for: Jeff, Ross, Interns (read-only)
```

### 📝 HUEY Will Guide You to:
- Set up the structure
- Add pages/libraries
- Apply correct permissions
- Integrate Loop or List views if needed

---

## ✅ Reminders
- Always include the agent name with @ when messaging
- Keep messages short and clear (under 2,000 characters for GPTs)
- You can include follow-up instructions like:
  `@huey >> Add a calendar to the FTIR Training Hub.`

---

## 📂 Save All Conversations
- Paste useful conversations back into the GitHub markdown files for team sharing
- Example: Copy a good HUEY response to `rossco/sop-library/sharepoint-guide.md`

---

**Last updated:** 2025-07-30  
Maintained by: System Admin (you)
