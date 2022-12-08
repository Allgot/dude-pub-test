For debugging 'prosyslab/dude'
=============
# 1. Test with @v1.0.0
```
Error: I cannot find the root of the current workspace/project.
If you would like to create a new dune project, you can type:
    dune init project NAME
Otherwise, please make sure to run dune inside an existing project or
workspace. For more information about how dune identifies the root of the
current workspace/project, please refer to
https://dune.readthedocs.io/en/stable/usage.html#finding-the-root
```
  
## Added `dune-project` into my repo:
```
Error: Program "./dup_scan.exe" not found!
```
  
## Added `dup_scan.ml` into my repo:
```
Error: Program "./dup_scan.exe" not found!
```
  
## Added `dune` into my repo:
Success!
  
## Report:
Therefore, we can conclude that **action does not contain `dune-project`, `dune` and `dup_scan.ml`** which are essential for scanning.

# 2. Test with @v1.0.1
```
Entering directory '/'
Error: Path "sys/bus/pnp/drivers/i8042 aux" has already been scanned. Cannot
scan it again through symlink "sys/bus/pnp/drivers/i8042 aux/00:02/driver"
```

# 3. Test with @v1.0.2
same.

# 4. Test with @v1.0.3