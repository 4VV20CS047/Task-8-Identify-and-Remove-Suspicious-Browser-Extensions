# 🔍 Identify and Review Browser Extensions (Task 8)

## Overview
This task focused on identifying and reviewing all installed browser extensions in Mozilla Firefox to ensure that no suspicious or malicious add-ons were present. This helps in improving browser security, protecting against malicious activity, and maintaining performance.

## Steps Performed
1. Navigated to the Firefox profile directory:

2. Examined the `extensions.json` file to gather details of installed extensions.
3. Used Python to parse the JSON and extract:
- Extension name
- Extension ID
- Version
4. Reviewed each extension for:
- Developer reputation
- Permissions requested
- User necessity (whether the extension is useful/required)
- Potential security/privacy risks
5. Categorized extensions into **Kept (Safe)** and **Suspicious/Removed**.

---

## Extensions Identified

### Kept Extensions
| Extension Name           | ID                            | Version  | Reason Kept |
|--------------------------|-------------------------------|----------|-------------|
| Form History Control (II) | formhistory@yahoo.com         | 2.5.1.0  | Trusted form history manager, no suspicious activity. |
| Form Autofill            | formautofill@mozilla.org      | 1.0.1    | Default Firefox extension, safe. |
| New Tab                  | newtab@mozilla.org            | 140.0.0  | Default Firefox extension, safe. |
| Picture-In-Picture        | pictureinpicture@mozilla.org | 1.0.0    | Default Firefox extension, safe. |
| Add-ons Search Detection | addons-search-detection@mozilla.com | 2.0.0 | Mozilla’s own extension, safe. |
| Web Compatibility Interventions | webcompat@mozilla.org   | 140.8.0  | Default system extension. |
| System theme — auto      | default-theme@mozilla.org     | 1.4.1    | Official Mozilla theme. |
| Light Theme              | firefox-compact-light@mozilla.org | 1.3.2 | Trusted Mozilla theme. |
| Dark Theme               | firefox-compact-dark@mozilla.org | 1.3.3 | Trusted Mozilla theme. |
| Firefox Alpenglow        | firefox-alpenglow@mozilla.org | 1.5     | Trusted Mozilla theme. |
| FoxyProxy Standard       | foxyproxy@eric.h.jung         | 7.5.1   | Popular proxy management tool, verified developer. |
| uBlock Origin            | uBlock0@raymondhill.net       | 1.60.0  | Trusted ad blocker, improves security/privacy. |

---

### Suspicious Extensions Removed
| Extension Name | Status   | Reason for Removal |
|----------------|----------|--------------------|
| None           | N/A      | No suspicious extensions were found during review. |

---

## Risks of Malicious Extensions
- **Data Theft**: Capture sensitive data such as keystrokes, passwords, and browsing history.  
- **Ad Injection**: Inject ads and trackers into browsing sessions.  
- **Privacy Violation**: Monitor user behavior without consent.  
- **Performance Issues**: Slow down browser and system performance.  

---

## Conclusion
- ✅ All installed extensions in Firefox were identified and analyzed.  
- ✅ No suspicious or malicious extensions were found.  
- ✅ Safe and useful extensions such as **FoxyProxy** and **uBlock Origin** were kept for enhanced browsing security.  

