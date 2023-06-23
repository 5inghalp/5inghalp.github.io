## Verma Lab Test Blogpost

lalalal Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

### This is a header

#### Some T-SQL Code

```tsql
~/group/projects/simulation_encoding/sim_updated.R --maf1=0.1 --maf2=0.1 --eff1=0,0.5,1 --eff2=0,0.5,1 --case=5000 --control=15000 --model= 0,0,0,1 > model_maf0.1_additive_case5000con15000_model0_0_0_0.1
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
