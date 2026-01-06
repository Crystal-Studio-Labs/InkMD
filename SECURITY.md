<div align="center">

<img src="https://img.icons8.com/id/Xf8iRj4hB0l0/color/200" alt="Security Shield" width="120" height="120"/>

# 🔒 Security Policy

### *We take the security of InkMD and our users seriously.*

<p align="center">
  <strong>Transparency • Integrity • Speed</strong>
</p>

<!-- Security Status Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Security-Audited-2ea44f?style=for-the-badge&logo=security&logoColor=white" alt="Audited"/>
  <img src="https://img.shields.io/badge/Vulnerabilities-0%20Known-007EC6?style=for-the-badge&logo=snyk&logoColor=white" alt="Vulnerabilities"/>
  <img src="https://img.shields.io/badge/Response%20Time-%3C24h-F7B93E?style=for-the-badge&logo=speedtest&logoColor=black" alt="Response Time"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OWASP-Compliant-purple?style=flat-square" alt="OWASP"/>
  <img src="https://img.shields.io/badge/CSP-Enabled-blue?style=flat-square" alt="CSP"/>
  <img src="https://img.shields.io/badge/XSS-Protected-green?style=flat-square" alt="XSS Protection"/>
  <img src="https://img.shields.io/badge/Safe_Harbor-Active-orange?style=flat-square" alt="Safe Harbor"/>
</p>

</div>

---

## 🛡️ Supported Versions

We actively maintain and provide security updates for the following versions. Please ensure you are running a supported version to stay protected.

<div align="center">

| Version | Status | Security Updates | End of Life |
| :---: | :---: | :---: | :---: |
| **v1.0.x** | <img src="https://img.shields.io/badge/✅_Active-success?style=flat-square"/> | **Full Support** | *TBD* |
| **v0.9.x** | <img src="https://img.shields.io/badge/⚠️_Maintenance-yellow?style=flat-square"/> | Critical Only | Mar 2026 |
| **< v0.9** | <img src="https://img.shields.io/badge/❌_Unsupported-critical?style=flat-square"/> | None | Dec 2025 |

</div>

---

## 🚨 Reporting a Vulnerability

We value the contributions of the security research community and welcome responsible disclosure.

### 🚫 Step 1: Do NOT Publicly Disclose
Please **do not** discuss the vulnerability in public issues, forums, social media, or other channels until we have acknowledged the issue and released a fix.

### 📧 Step 2: Contact Us Privately
Please send a detailed report to our security team.

<div align="center">

<a href="mailto:connect.crystalstudio@gmail.com">
  <img src="https://img.shields.io/badge/📧_EMAIL_US-connect.crystalstudio@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Security Team" />
</a>

</div>

**Please include in your report:**
*   Type of vulnerability (e.g., XSS, CSRF, Injection).
*   Step-by-step instructions to reproduce the issue.
*   New or context-specific proof-of-concept (PoC) code or screenshots.
*   Impact of the vulnerability.

---

## 🔐 Architecture & Defense

InkMD is designed with a **"Defense in Depth"** strategy, prioritizing client-side data isolation.

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🏛️ Client-Side Isolation</h3>
      <p>InkMD operates as a <b>Local-First</b> application. </p>
      <ul>
        <li><b>No Server Database:</b> We do not store your documents.</li>
        <li><b>Memory Only:</b> Data resides in browser memory/Local Storage.</li>
        <li><b>Sanitized Render:</b> All markdown rendering is sanitized to prevent XSS.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ Security Headers</h3>
      <p>We implement strict security headers on our host:</p>
      <ul>
        <li><code>Content-Security-Policy</code> (Strict)</li>
        <li><code>X-Frame-Options: DENY</code></li>
        <li><code>X-Content-Type-Options: nosniff</code></li>
        <li><code>Referrer-Policy: strict-origin</code></li>
      </ul>
    </td>
  </tr>
</table>

---

## ⚖️ Safe Harbor Policy

We support safe and legal security research. We pledge **not to pursue legal action** against researchers who:

*   Example: Engage in testing within the scope of this policy.
*   Example: Avoid compromising user privacy or disrupting service.
*   Example: Adhere to the disclosure laws of their jurisdiction.

### ⛔ Out of Scope
*   DDoS or Denial of Service attacks.
*   Social Engineering (Phishing) of staff.
*   Physical attacks against data centers or offices.

---

## 🏆 Hall of Fame

We would like to thank the following individuals for responsibly disclosing vulnerabilities and helping make InkMD safer for everyone.

| Year | Researcher | Vulnerability Type | Status |
| :---: | :--- | :--- | :---: |
| 2026 | *Your Name Here* | - | - |

---

<div align="center">

**© 2026 Crystal Studio Development**

Made with ❤️ by [Shuvranshu Sahoo](https://github.com/shuvranshu)

[Terms of Service](#) • [Privacy Policy](#) • [Security](SECURITY.md)

</div>
