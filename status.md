---
layout: default
---

# System Status

<div class="status-table">
  <div class="status-row header">
    <div class="status-cell">Service</div>
    <div class="status-cell">Status</div>
  </div>
  <div class="status-row">
    <div class="status-cell">Website</div>
    <div class="status-cell"><span class="status-icon operational">🟢</span></div>
  </div>
  <div class="status-row">
    <div class="status-cell">Cloud Storage</div>
    <div class="status-cell"><span class="status-icon operational">🟡</span></div>
  </div>
  <div class="status-row">
    <div class="status-cell">Backup storage</div>
    <div class="status-cell"><span class="status-icon operational">🟢</span></div>
  </div>
  <div class="status-row">
    <div class="status-cell">Email</div>
    <div class="status-cell"><span class="status-icon operational">🟢</span></div>
  </div>
</div>

<div class="status-legend">
  <div><span class="status-icon operational">🟢</span> Operational</div>
  <div><span class="status-icon issues">🟡</span> Minor Issues</div>
  <div><span class="status-icon outage">🔴</span> Outage</div>
</div>

<p class="last-updated">Last updated: <span id="current-date-time"></span></p>

<script>
  document.getElementById('current-date-time').textContent = new Date().toLocaleString();
</script>
