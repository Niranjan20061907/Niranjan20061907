<div align="center">
  <h1 style="font-size: 3.5rem; font-weight: bold; margin-bottom: 0;">NIRANJAN K</h1>
  <h3 style="font-weight: normal; margin-top: 0;">SOFTWARE ENGINEER | CYBERSECURITY | SYSTEMS PROGRAMMING</h3>

  <p>
    <a href="https://www.linkedin.com/in/niranjan-krishnarajarajan-768625332/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:k.niranjan2006@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/Niranjan20061907">
      <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
    </a>
  </p>

  <br />

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=3F8CFF&center=true&vCenter=true&width=650&lines=Building+Secure%2C+Air-Gapped+Systems;Hardening+Windows+%2F+OT+%2F+SCADA+Endpoints;Full-Stack+%2B+Systems-Level+Engineering;CIS+Benchmark+Compliance+Automation" alt="Typing SVG" />

</div>

<br />

---

### 👋 **About Me**

I'm a **B.Tech Computer Science** student at **NIT Rourkela**, focused on **software engineering** with a strong specialization in **cybersecurity and systems-level programming**. I recently completed an **OT Security & Industrial Networking internship at Rockwell Automation**, where I built a full-stack compliance and hardening tool for air-gapped industrial systems. I'm also a **Robotics Software Engineer** on **Team Tiburon**, NIT Rourkela's Autonomous Underwater Vehicle (AUV) team.

I like working close to the OS — registry internals, service hardening, process control — and shipping tools that are genuinely usable by non-experts, not just proof-of-concepts.

<br />

### 🛡️ **Featured Project — WinHardener**

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>🛡️ WinHardener</h3>
      <p><i>CIS Windows 11 Hardening & Compliance Tool</i></p>
      <a href="https://github.com/Niranjan20061907/WinHardener">
        <img src="https://img.shields.io/badge/View_Code-Repository-2ea44f?style=for-the-badge&logo=github" />
      </a>
    </td>
    <td width="50%">
      <b>The Problem:</b> Manual CIS compliance auditing on standalone, air-gapped OT/ICS Windows endpoints (HMIs, historians, engineering stations) is slow, error-prone, and doesn't scale.
      <br /><br />
      <b>The Solution:</b>
      <ul>
        <li>Built during my OT Security internship at <b>Rockwell Automation</b>.</li>
        <li>Full-stack, zero-dependency, <b>air-gapped</b> Flask app — no CDNs, no internet required at runtime.</li>
        <li>Maps to <b>57 controls</b> from the CIS Microsoft Windows 11 Benchmark v5.0.0 (password policy, account lockout, local policy, system services).</li>
        <li>Applies all remediations in <b>under 10 seconds</b> via <code>secedit</code>, <code>reg.exe</code>, and <code>sc.exe</code> through Python <code>subprocess</code>.</li>
        <li><b>RBAC</b> with hashed authentication — Admin (full remediation) vs Guest (read-only audit).</li>
        <li><b>PDF compliance reporting</b> (fpdf2) and JSON audit logging for every policy change.</li>
      </ul>
    </td>
  </tr>
</table>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Windows_Registry-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/CIS_Benchmark-v5.0.0-2ea44f?style=flat-square" />
</p>

<br />

### 💻 **Tech Stack**

<table width="100%">
<tr>
<td valign="top" width="33%">

**Languages**
<img src="https://skillicons.dev/icons?i=python,cpp,js,html,css,solidity" />

</td>
<td valign="top" width="33%">

**Backend & Systems**
<img src="https://skillicons.dev/icons?i=flask,fastapi,nodejs,git" />
<br/><i>subprocess/winreg · secedit, reg.exe, sc.exe · RBAC & hashed auth</i>

</td>
<td valign="top" width="33%">

**ML / Data**
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,pandas" />
<br/><i>Deep RL (PPO) · GBM market simulators · time-series regression</i>

</td>
</tr>
<tr>
<td valign="top" width="33%">

**Security / Networking**
<br/>
Wireshark · OT/ICS & SCADA hardening · CIS Benchmark compliance · air-gapped deployment · Windows Group Policy internals · VMware P2V

</td>
<td valign="top" width="33%">

**Web / Blockchain**
<img src="https://skillicons.dev/icons?i=nextjs,solidity" />
<br/><i>Smart contracts · off-chain indexing</i>

</td>
<td valign="top" width="33%">

**Tools**
<img src="https://skillicons.dev/icons?i=git,github,docker,vscode" />

</td>
</tr>
</table>

<br />

### 🚀 **Other Projects**

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>🤖 Deep RL Derivative Hedging</h3>
      <p><i>Autonomous Option Hedging Agent</i></p>
      <a href="https://github.com/niranjan20061907/rl-derivative-hedging">
        <img src="https://img.shields.io/badge/View_Code-Repository-2ea44f?style=for-the-badge&logo=github" />
      </a>
    </td>
    <td width="50%">
      <ul>
        <li>Custom <code>Gymnasium</code> environment simulating market friction and transaction costs.</li>
        <li>Trained a <b>PPO agent</b> to learn optimal hedging bands beyond classic Black-Scholes delta-hedging.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>📉 Order Flow Imbalance (OFI)</h3>
      <p><i>Market Microstructure Signal Research</i></p>
      <a href="https://github.com/niranjan20061907/order-flow-imbalances">
        <img src="https://img.shields.io/badge/View_Code-Repository-2ea44f?style=for-the-badge&logo=github" />
      </a>
    </td>
    <td width="50%">
      <ul>
        <li>Engineered an OFI feature pipeline from raw limit order book tick data.</li>
        <li>Linear/logistic regression models forecasting multi-horizon returns.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>💸 Flowmint</h3>
      <p><i>DeFi Revenue Tokenization Platform</i></p>
      <a href="https://github.com/niranjan20061907/flowmint">
        <img src="https://img.shields.io/badge/View_Code-Repository-2ea44f?style=for-the-badge&logo=github" />
      </a>
      <br/>
      <a href="https://flowmint-f75h.onrender.com">
        <img src="https://img.shields.io/badge/Live_Demo-Deploy-FF5722?style=flat-square&logo=html5" />
      </a>
    </td>
    <td width="50%">
      <ul>
        <li><b>Solidity</b> smart contracts for revenue splitting and token minting.</li>
        <li><b>FastAPI</b> backend for off-chain indexing, <b>Next.js</b> dashboard for real-time tracking.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<br />

### 🌊 **Team Tiburon — Autonomous Underwater Vehicle Team**

Robotics Software Engineer at NIT Rourkela's AUV team, working on autonomy software for underwater competition robots.

<br />

### 📊 **GitHub Analytics**

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Niranjan20061907&show_icons=true&theme=radical&hide_border=true&count_private=true" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Niranjan20061907&layout=compact&theme=radical&hide_border=true" height="150" alt="languages graph" />
</div>
