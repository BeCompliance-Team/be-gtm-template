# Be.Aliant CMP - Google Tag Manager Template

The official Google Tag Manager (GTM) custom template for **Be.Aliant** (by BeCompliance). 

This template provides a seamless, codeless integration between the Be.Aliant Consent Management Platform (CMP) and **Google Consent Mode v2**.

## 🚀 Features

* **Out-of-the-box Consent Mode v2:** Automatically sets the native GTM `default` consent state before any Google tags fire.
* **Privacy by Default:** Sets `ad_storage`, `analytics_storage`, `ad_user_data`, and `ad_personalization` to `denied` initially.
* **Secure Injection:** Safely injects the Be.Aliant CMP script using GTM's sandboxed JavaScript APIs.
* **Native Integration:** Fully compatible with GTM's "Consent Initialization" trigger to prevent data leakage.
* **Debug Support:** Outputs clear initialization logs to the GTM Preview console for easy troubleshooting.

## 🛠️ Installation Guide

1. In your Google Tag Manager workspace, navigate to **Templates** > **Tag Templates** > **Search Gallery**.
2. Search for **Be.Aliant** and click **Add to workspace**.
3. Go to **Tags** > **New** and select the **Be.Aliant** tag template.
4. In the configuration panel, enter your **Be.Aliant Client ID** (this is the unique Banner ID provided in your BeCompliance dashboard).
5. Open the **Triggering** section and select the **Consent Initialization - All Pages** trigger. *(Note: It is crucial to use this specific trigger to ensure the default command fires before any other tags).*
6. Save the tag and publish your GTM container.

## ⚙️ Configuration Fields

* **Client ID (Required):** Your unique alphanumeric identifier. Example: `ae3e2166-c2c3-4726-848a-1d28fb5ab1a7`.

## 📚 Documentation & Support

If you need help setting up Basic or Advanced Consent Mode, or generating your Client ID, please refer to our official resources:

* **Setup Guide & Documentation:** [Be.Aliant Google Consent Mode Documentation](https://testegoogle.becompliance.com/lgpd/cookies/public-info/google-consent-mode)
* **Official Website:** [becompliance.com](https://becompliance.com)
* **Dedicated Google Support:** [google-support@becompliance.com](mailto:google-support@becompliance.com)

---
*Developed and maintained by the Be.Aliant/BeCompliance tech team.*
