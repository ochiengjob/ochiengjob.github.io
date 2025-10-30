---
title: Lab Challenges
icon: fas fa-flask
order: 4
---

<div class="labs-grid">

<!-- Lab 1 -->
<div class="card">
  <h3>🔐 Network Packet Capture & Analysis</h3>
  <p><strong>Problem:</strong> Identify suspicious packets from live traffic data.</p>
  <p><strong>Approach:</strong> Used Wireshark and Kali Linux to capture and filter packets.</p>
  <p><strong>Tools:</strong> Wireshark, Kali Linux</p>
  <p><strong>Key Lesson:</strong> Learned to recognize TCP anomalies and suspicious behavior patterns.</p>
  <a href="#" class="btn btn-sm btn-primary">View Report</a>
</div>

<!-- Lab 2 -->
<div class="card">
  <h3>🧰 Password Cracking Simulation</h3>
  <p><strong>Problem:</strong> Demonstrate password vulnerability testing.</p>
  <p><strong>Approach:</strong> Used Hashcat with custom wordlists to test password strength.</p>
  <p><strong>Tools:</strong> Hashcat, Crunch, Kali Linux</p>
  <p><strong>Key Lesson:</strong> Showed how strong passphrases and salts resist brute-force attacks.</p>
  <a href="#" class="btn btn-sm btn-primary">View Report</a>
</div>

<!-- Lab 3 -->
<div class="card">
  <h3>🧩 File Forensics CTF</h3>
  <p><strong>Problem:</strong> Extract hidden data from image files.</p>
  <p><strong>Approach:</strong> Used Binwalk and Steghide for deep file inspection.</p>
  <p><strong>Tools:</strong> Binwalk, Steghide, Kali Linux</p>
  <p><strong>Key Lesson:</strong> Discovered how steganography conceals sensitive information.</p>
  <a href="#" class="btn btn-sm btn-primary">View Report</a>
</div>

</div>

<style>
.labs-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
}
.card {
  background-color: var(--card-bg);
  border-radius: 12px;
  box-shadow: var(--shadow);
  padding: 1rem 1.2rem;
  transition: transform 0.2s ease-in-out;
}
.card:hover {
  transform: scale(1.03);
}
.btn {
  display: inline-block;
  margin-top: 0.6rem;
  padding: 0.3rem 0.8rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
}
.btn-primary {
  background-color: var(--btn-bg);
  color: var(--btn-text);
}
</style>
