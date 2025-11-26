---
layout: doc
title: Connecting Cloud Storage
---
<p>Abookio supports a variety of cloud storage providers, allowing you to stream your audiobooks directly from your personal cloud.</p>

<h2>Supported Providers</h2>
<ul>
  <li>Box</li>
  <li>Dropbox</li>
  <li>Google Drive</li>
  <li>OneDrive</li>
  <li>pCloud</li>
</ul>

<h2>Provider-Specific Information</h2>

<h3>Google Drive</h3>
<p>Google Drive integration uses the native <strong>Google File Picker</strong> as required by Google.</p>
<ul>
  <li>Audiobooks must be selected individually.</li>
  <li><strong>Tip:</strong> To select multiple files at once, use a <strong>two-finger tap</strong> gesture in the picker.</li>
</ul>

<h3>pCloud</h3>
<p>pCloud has a specific folder structure requirement for third-party apps.</p>
<ul>
  <li>After adding your account in Abookio, you must move your audiobooks into the following folder:
    <br><code>My pCloud/Applications/Abookio</code>
  </li>
  <li>This folder is automatically created by pCloud once the account has been set up in the app.</li>
</ul>

<h3>Box, Dropbox, and OneDrive</h3>
<div style="background-color: #f8f9fa; border-left: 4px solid #007AFF; padding: 15px; margin: 20px 0;">
  <strong>Important Note on Folder Scanning:</strong>
  <p style="margin-bottom: 0;">Abookio scans a maximum of <strong>one level down</strong> from the selected folder.</p>
</div>

<p><strong>Supported Structure:</strong><br>
<code>Selected Folder/Audiobook A</code></p>

<p><strong>Not Supported:</strong><br>
<code>Selected Folder/Fiction/Audiobook B</code> (This is two levels down)</p>
