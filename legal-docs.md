from pathlib import Path

pp = """# Privacy Policy – Robot Constitution

Last updated: 2025-12-04

Welcome to Robot Constitution (“we”, “the Site”). This Privacy Policy explains how we collect, use, and protect personal data in accordance with GDPR and applicable regulations.

## 1. Data Controller
Robot Constitution  
Email: robot-constitution@gmail.com  
Domain: robot-constitution.com

## 2. Data We Collect
### 2.1. Data Provided Voluntarily
- Name and email when contacting us

### 2.2. Automatically Collected Data
- IP address (anonymized when possible)  
- Device and browser type  
- Technical logs  
- Technical and analytics cookies

## 3. Purposes of Processing
- Responding to user requests  
- Improving website functionality  
- Anonymous statistical analysis  
- Legal compliance

## 4. Cookies
See our Cookie Policy for details.

## 5. Legal Basis
Consent, legitimate interest, and legal obligations.

## 6. Data Retention
Data is kept only as long as necessary for the purposes above.

## 7. User Rights
Access, rectification, deletion, restriction, objection, and data portability.  
You may request these rights by emailing robot-constitution@gmail.com.

## 8. Data Transfers
No data is transferred outside the EU unless using GDPR-compliant services.

## 9. Security
We apply technical and organizational measures to protect personal data.

## 10. Changes to This Policy
Updates may occur and will be published on this page.
"""

cp = """# Cookie Policy – Robot Constitution

Last updated: 2025-12-04

## 1. What Cookies Are
Cookies are small text files used to improve your browsing experience.

## 2. Types of Cookies We Use
### Technical Cookies
Required for website operation.

### Analytics Cookies
We may use Google Analytics with anonymized IP.

### Third-Party Cookies
Embedded services (e.g. social media, video players) may set cookies.

## 3. Managing Cookies
Cookies can be managed through the banner or your browser settings.

## 4. Contact
robot-constitution@gmail.com
"""

cs = """# About Us – Robot Constitution

Robot Constitution is a project dedicated to defining, exploring, and sharing ethical principles, user rights, and responsibilities related to artificial intelligence.

Our goals include:
- Promoting awareness of responsible AI use  
- Providing accessible educational content  
- Exploring governance, transparency, and accountability in emerging technologies  

Contact: robot-constitution@gmail.com
"""

tc = """# Terms & Conditions – Robot Constitution

Last updated: 2025-12-04

## 1. Purpose of the Service
Robot Constitution provides informational and educational content.  
It does not offer professional, legal, or technical advice.

## 2. Intellectual Property
All content on the site is owned by Robot Constitution unless otherwise stated.  
Reproduction without permission is prohibited.

## 3. Acceptable Use
Users agree not to:
- Use the site for illegal activities  
- Attempt to breach website security  
- Copy or republish content without authorization  

## 4. Limitation of Liability
Robot Constitution is not responsible for:
- Errors or inaccuracies  
- Damages resulting from use of the site  
- External websites linked from our pages  

## 5. External Links
We have no control over third-party content.

## 6. Changes
We may update these Terms. Updates will be published on this page.

## 7. Contact
robot-constitution@gmail.com
"""

full = "\n\n---\n\n".join([pp, cp, cs, tc])

path = "/mnt/data/legal-docs-en.md"
Path(path).write_text(full)

path
