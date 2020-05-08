# 🔓 Get-ModernCredential

The real 'Windows Credential' dialog for PowerShell

Could have just published this on the PowerShell Gallery, but I'm not 100% about publishing a module that only exports 1 Cmdlet.

# 💾 Usage guide

To use, download the _Get-ModernCredential.dll_ file and import with
`Import-Module .\Get-ModernCredential.dll`
Afterwards you can simply call Get-ModernCredential

It returns a PSCredential object, same as _Get-Credential_, and if you don't provide anything, it throws an error...like _Get-Credential_.

.... ok it's basically just Get-Credential but it looks sexy

# 🖼 Screenshots

![Wow, so pretty](/images/shot1.png)
![Omg, return data](/images/shot2.png)
