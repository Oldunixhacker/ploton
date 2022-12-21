# Ploton UI

Firefox's Proton UI is great:

* Icon to remind you of Microsoft Edge
* Simple user interface
* Almost fits the Windows 11 user interface

but there are some flaws:

* Is it a tab or a button?
* No icons
* Harder to see the highlight colors on tabs

This Firefox theme addresses the issue.

## Optional features

These can be enabled in `about:config` with these booleans.

* **Photon-styled tabs** `ploton.photonTabs`
  
  Ploton by default modifies Proton's tab look to remove bottom curves and replace them with
  a Chromium-like style. You can make it actually replicate tabs used in Photon by enabling
  this boolean option.

* **Icons** `ploton.menuIcons`
  
  Enable icons like Photon's interface.

* **GTK icon scheme (Linux)** `ploton.systemIcons`
  
  Use the system icon scheme. Based on the option from Firefox GNOME theme.

* **Bottom tabs** `ploton.preQuantumTabs`
  
  Use bottom tabs, similar to Firefox before the Quantum engine was used.

   * **Subfeature: Extend tabs to max width** `ploton.preQuantumTabs.extendedTabs`
   
     Makes tabs extend to the maximum width possible, like GNOME apps. Text
     will also be centered.
