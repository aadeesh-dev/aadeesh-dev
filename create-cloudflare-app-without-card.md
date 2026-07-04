# 🚀 Create a Cloudflare Application Without a Credit Card (Hidden Method)

> **Author's Note:** This is an undocumented, hidden process. It took over 3 hours of research, analyzing 18 different YouTube tutorials, and consolidating scattered knowledge to finally uncover this workaround at 12:14 AM on May 12, 2026. None of the existing videos explicitly outlined this exact method.

If you are trying to bypass the credit card requirement when creating an application in Cloudflare Zero Trust, follow these exact steps to access the hidden creation page.

## 📋 Step-by-Step Guide

1. **Access Zero Trust**
   Log in to Cloudflare and navigate to the **Zero Trust** dashboard.

2. **Navigate to Policies**
   From the left sidebar, click on **Policies**, and then select **Access Controls**.

3. **Locate the 'Allow Me' Policy**
   Find the policy named **Allow me policy** (or your equivalent default access policy).

4. **Open the Sidebar Popup**
   Click on **View more** next to the policy. This will open a popup sidebar on the right side of your screen.

5. **Find Applications in Overview**
   Inside the sidebar, look under the **Overview** section until you see **Applications**.

6. **View the Application Details**
   Click on the **3 dots** (options menu) next to an application, and select **View**.

7. **The URL Hack (Crucial Step)**
   Look at your browser's address bar. You will see a URL containing a specific ID number. 
   
   *Delete everything after that number* and append the following path to the URL:
   
   ```text
   /one/access-controls/apps/add
