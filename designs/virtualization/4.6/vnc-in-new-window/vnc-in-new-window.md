---
parent: Virtualization
version: 4.6
---
# VNC in a new window / tab

## In the Administrator console

The Console tab allows the user to connect an in-browser or desktop-based Graphical and/or Serial console to the virtual machine.
We’ll add a new button ‘Open Console’.
Users will be able to change the console type using the dropdown selector. The Graphical VNC console is selected by default and will open in a separate window or tab of the console view when clicking the ‘Open console’ button. The default will be set to open the console in a new window. Users will be able to drag the tab to be a new window.
The Expand action makes the console viewport fill the current window’s full width and height.

![open from the new button](img/Open-console-1c.png)

Another way to open the VNC Console can be done via the kebab dropdown menu.

![open from the kebab menu](img/Open-console2.png)

## In the Developer console

In the developer console we’ll have the same option to open the console of the topology view.

![open from the topology view](img/vm-topology-actions-open-console.png)

As well as from the Actions dropdown menu.

![open from the actions drop down](img/helm-release.png)

# Design a VNC console in a new tab 

We'll add a dismissble inline info notification explaining about the console tab features.
Users will be able to toggle between the 2 tabs or tab/ window: their original OpenShift cluster and the other OS they have opened.
The info notification text is:

######Consoles tab

The Console tab allows the user to connect an in-browser or desktop-based Graphical and/or Serial console to the virtual machine.
You can change the console type using the dropdown selector. The Graphical VNC console is selected by default and will open in a separate window/tab of the console view when clicking the ‘Open console’ button. You can drag the new tab into a new browser window.

![console opens in new tab](img/Detached3-new-tab.png)

## Design a VNC console in a new window

When the console opens in a new window 

![console opens in new window](img/Detached3-new-window.png)
