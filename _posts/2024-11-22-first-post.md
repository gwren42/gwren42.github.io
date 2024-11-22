## First Post
---
This GitHub Pages account was set up 11/22/24 using <a href="https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html">instructions provided by Chad Baldwin.</a>


#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
