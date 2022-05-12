# Mumble-URL-Fix-Window
A quick repo to explain how to get Mumble links working in Windows 10/11

# Download the registry file mumble.reg
[mumble.reg](https://raw.githubusercontent.com/rTiGd2/Mumble-URL-Fix-Window/main/mumble.reg)
> Right click the link above and save it somewhere. If your browser wants to save as .txt (or does save as .txt) then remove the .txt (the file needs to end in .reg to enable double clicking to install it.)

In File Explorer find where you saved mumble.reg and double click on it to install the registry entry. This will ask you if you wish to make the changes, feel free to not accept if you are worried but it is required for the fix.

After you have made the registry change you can now click on mumble:// links - The first time you do this you will most likely have your web browser ask if you want to run mumble, do what you want but if you don't say yes, it won't work.

> For example, in Firefox, tick the box shown as 1 and then select mumble shown as 2
![Firefox](/assets/Mumble-step-1.png)

> If you are a Goon then reach out to Sillat/Midnight Space Monkey if you need some extra clarification.

If you are worried about the contents on the .reg file, you can view it in a text editor such as notepad++ and verify the contents as being the same as the issue in the mumble incident reporting this problem found here: https://github.com/mumble-voip/mumble/issues/5473#issuecomment-1018438938
