# Setting Up Access to GitHub

<em> This document describes how to set up access to GitHub in Domino.</em>
> Note: This document would have contained a few images and screenshots for partiular UI items, but for company IP protection these images are not available.

## Why Git?
Git is an important tool for collaboration on the [Product] and in Domino. It provides you with a method for checkin in and out code changes in a cloud-based repository. Using Git, you can save any projects you are working on and share them with others to work as a team on particular tasks.

## Accessing GitHub with Personal Access Tokens
<ol>
  <li> Visit [link redacted] after you have access to Domino.</li>
  <li> Sign in to your GitHub account. An account should already exist for you to sign in via SSO. If you run into any issues with this, please contact your administrator.</li>
  <li> Select your profile icon in the ribbon.</li>
  <li> Click the <b>Settings</b> option in the drop-down.</li>
  <li> Select <b>Developer settings</b> in the left-hand menu.</li>
  <li> Select <b>Personal access tokens</b> from the menu that appears.</li>
  <li> Click the <b>Generate new token</b> button. </li>
  <li> Give your personal access token an easily identifiable name, different from any other tokens you may have, if applicable.</li>
  <li> Select the box for the <b>repo</b> scope.</li>
  <li> Click the <b>Generate Token</b> button to generate your token.</li>
  <li> Copy the token to your clipboard.</li>
  <li> In a new window, open Domino.</li>
  <li> Click your username in the bottom of the left-hand menu and select <b>Account Settings</b>.</li>
  <li> In the <b>Git Credentials</b> section, select <b> Add Credentials.</b> The <b>Add Git Credentials</b> appears. </li>
  <li> Enter a nickname for you credentials and set the <b>Git Service Provider</b> to <b>GitHub Enterprise</b></li>
  <li> In the <b>Domain</b> field, enter [redacted domain] and set the Access Type to <b>Personal Access Token</b></li>
  <li> Paste your personal access token in the <b>Personal Access Token</b> field.</li>
  <li> Click <b>Save</b> to add your GitHub credentials to Domino.</li>
</ol>
