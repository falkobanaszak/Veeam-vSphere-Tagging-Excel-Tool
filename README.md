# Veeam-vSphere-Tagging-Excel-Tool
An excel tool to tag your VMs with a vSphere Tag out of a dropdown menu

This tool is very self explaing and straight forward, so have fun with it :)

![Here it is :) ](/Veeam-vSphere-Tagging-Excel.png)

# Veeam-vSphere-Tagging-Excel-Tool as HTML5

I have also done a ChatGPT HTML5 version of this tool, which you can access and use here :)
[vSphere HTML 5 Tagging Tool on virtualhome.blog](https://www.virtualhome.blog/vSphere-Tagging-Tool.html)
Here is a screenshot on how this tool looks like:

![HTML 5 ChatGPT version](/vSphere-Tagging-Tool-HTML5-GitHub.png)

# How to use the HTML 5 tool ?

- Create a .txt file with all your VM’s you want to tag in a single line
- Select Choose File and import that .txt file and hit “Import VM Names”
- Use the text field in the middle to add your tags, whereby one line equals one tag and hit the button “Load vSphere Tags”
- Select the tag for each VM and hit the button “Generate Commands” which will give you PowerCLI ready commands to tag your VM’s
- PRO TIP: When you want to tag 5K VM’s with a single tag, make sure to only provide one tag in the description field, as it gets auto-selected in the dropdown menu for mass tagging operations.

![How to Use the vSphere Tagging HTML5 Tool](/vSphere-Tagging-Tool-HTML5-How-To-Use.png)
