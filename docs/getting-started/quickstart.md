<div style="background:#fff; border-radius:16px; box-shadow:0 4px 16px rgba(0,0,0,0.05); padding:24px; max-width:700px; margin:auto; font-family:Roboto;">
  <h2 style="color:#0097b2;">📤 Submit Your dApp to Kasparex</h2>
  <p>Ready to go live? Fill out this short form to get your dApp listed and connected to the ecosystem.</p>
  <form id="submitDappForm" style="display:flex; flex-direction:column; gap:16px;">
    <label>🎯 dApp Title:<br><input type="text" name="title" required style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>
    
    <label>📝 Short Description:<br><textarea name="description" required rows="2" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></textarea></label>

    <label>🧩 Embed-Ready Widget Code:<br><textarea name="widgetCode" required rows="6" placeholder="Paste your full HTML block here" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc; font-family:monospace;"></textarea></label>

    <label>🔗 Live Preview URL (optional):<br><input type="url" name="previewUrl" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>

    <label>🔐 Smart Contract Hash:<br><input type="text" name="contractHash" placeholder="Optional" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>

    <label>💸 Revenue Share Model:<br>
      <select name="revshare" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;">
        <option value="yes">Yes – Shared with Kasparex</option>
        <option value="no">No – 100% to developer</option>
      </select>
    </label>

    <label>📂 Dev Group URL:<br><input type="url" name="devGroup" required style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>

    <label>📸 Preview Image URL:<br><input type="url" name="image" placeholder="Link to a screenshot or banner" style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>

    <label>📬 Developer Contact (X / Email):<br><input type="text" name="contact" required style="width:100%; padding:8px; border-radius:8px; border:1px solid #ccc;"></label>

    <button type="submit" style="background:#0097b2; color:#fff; padding:12px 24px; border:none; border-radius:12px; font-size:16px; cursor:pointer;">🚀 Submit dApp</button>
  </form>
</div>

<script>
document.getElementById("submitDappForm").addEventListener("submit", function(event) {
  event.preventDefault();
  alert("✅ Submission received! The Kasparex team will review your dApp within 1–3 days.");
});
</script>


🧩 Official Kasparex dApp Listing Process
(Step-by-step for Builders, Dev Teams, and Community Moderation)

🧱 1. Ideation & Planning
Define the problem your dApp solves and its intended users.

Follow the UaaS (Utility-as-a-Service) structure:

Modular utility

Easily embeddable

Token-agnostic or KRC-20 specific

Review Kasparex UI standards:

Clean UI, white background

Rounded corners, light shadow

Roboto font

Buttons: #0097b2 background, white text

Info icons for explanations

Responsive design (mobile+desktop)

💻 2. Development
Start with a Kasparex widget template (available via Dev Groups).

Use Velo (for Wix) or clean HTML/CSS/JS structure.

Minimize external dependencies. Keep it lightweight.

Add functionality first. Beautify it later based on UI specs.

🔐 3. Kaspa Smart Contract Integration
Simulate or deploy Kaspa smart contracts using official syntax.

Use the following typical dApp contract patterns:

Wallet signature verifications

NFT/token gating

Action triggers (like vote, claim, etc.)

Hash timestamp records

Include revenue-sharing logic (optional):

Example: 90% to builder wallet, 10% to Kasparex treasury.

🧪 4. Testing in Dev Groups Playground
🔧 Dev Groups Role:
Every builder or dev team that creates a dApp is required to moderate and manage a dedicated Dev Group for:

Feedback gathering

Feature requests

Early access links

Bug reports

Live changelogs

🧪 Testing Procedure:
Post your dApp to your own Dev Group using the pinned “Testing Panel Template.”

Include:

❇️ Summary

🔗 Preview/embed link

📸 Screenshots or video/GIF demo

🧪 Contract test scenario

❓ Feedback poll (optional)

Test with your team + community before submitting to main listing.

📤 5. Submit dApp to Kasparex
📩 Use /submit-dapp Panel
(or share in Dev Group if form isn’t live)

📥 Submission Template:
markdown
Copy
Edit
🔹 Widget Title:  
🔹 One-Line Summary:  
🔹 Author/Dev Team:  
🔹 Preview URL (if live):  
🔹 Embed Code (HTML block):  
🔹 Features & Utilities:  
🔹 Smart Contract Hash (if applicable):  
🔹 Revenue Share Setup (yes/no):  
🔹 Dev Group URL (your moderator hub):  
🔹 Screenshot/Promo Image:  
🧾 6. Review & Approval
Review Criteria:
✅ UI/UX compliance with Kasparex standards

✅ No harmful or broken scripts

✅ Fully functional logic

✅ Smart contract calls validate properly

✅ Embed code is working standalone

✅ Dev Group is active and moderated

⏱️ Review time: 1–3 days
🛠️ Fix request turnaround: 24–48h

🚀 7. Listing & Launch on Kasparex.com
📣 What you get:
Public listing under “Explore dApps”

Embed-ready widget preview page

“Copy Widget” panel with configuration

Links to your Dev Group for support/community

Featured badge eligibility if:

You have a live Dev Group

Weekly community activity

Quality verified by Kasparex editors

💬 8. Post-Launch Moderation
As the builder/dev team, you're responsible for:

Moderating your dApp’s Dev Group

Responding to support requests

Posting changelogs or upgrades

Maintaining uptime and security

Updating documentation

🛡️ You are the official representative of your dApp on Kasparex.

📂 📋 Templates & Samples
📌 Dev Group Pinned Post Template:
markdown
Copy
Edit
📌 Welcome to the [dAppName] Dev Group!

🛠️ Description:
A [short summary of your dApp's utility and use case].

💡 Features:
- [Feature 1]
- [Feature 2]
- [Feature 3]

🧪 Test or Preview:
[link to demo or embed]

📩 Feedback:
Please drop bugs, ideas, or requests in comments below.

🧑‍💻 Dev Team: @[builder]  
📅 Launch Status: Testing / Live on Kasparex  
📝 Submission Form (Copyable for now)
markdown
Copy
Edit
🎯 dApp Title:
📝 Short Description:
🧩 Full Widget Code (embed):
🔗 Live Preview or Test Page:
🔐 Smart Contract Hash (if any):
💸 Revenue Share Model (yes/no):
📂 Dev Group Link:
📸 Screenshot or Preview Image:
📬 Dev Contact:
