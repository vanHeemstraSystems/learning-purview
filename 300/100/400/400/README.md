# 400 - Create a simple sensitivity label (if you have access)

## Prerequisites

- You need appropriate permissions like Sensitivity Label Administrator, Compliance Administrator, or similar roles in the Microsoft Purview portal
- You ned a valid Microsoft 365 license that supports sensitivity labels

## Steps to Create a Simple Sensitivity Label 

### 1. Access Sensitivity Labels

Sign in to the Microsoft Purview portal > Solutions > Information Protection > Sensitivity labels

### 2. Create a New Label

On the Sensitivity labels page, select **+ Create a label** to start the new sensitivity label configuration 

### 3. Define Basic Information

- **Name**: The name admins see (e.g., “Confidential”)
- **Display Name**: What users see in apps like Word, Outlook (e.g., “Confidential - Internal Only”)
- **Description**: Help text explaining when to use this label

### 4. Define the Scope

Select scope options that determine where the label can be used (e.g., Files & other data assets, Emails, Meetings) 

### 5. Configure Protection Settings (Optional for Simple Label)

For a basic label, you can skip encryption and just use it for classification. Follow the prompts through:

- Encryption settings (can leave as “None” for simple classification)
- Content marking (headers, footers, watermarks - optional)
- Auto-labeling settings (optional)

### 6. Review and Create

Complete the wizard and create your label.

### 7. Publish the Label

After creating labels, go to Information Protection > Publishing policies, select **Publish label**, and create a policy that makes your label available to users 

You’ll need to specify which users/groups can see and use this label.

**Important:** Changes take about 15 minutes to propagate, and newly published labels can take up to 24 hours to appear in users’ Office apps 

