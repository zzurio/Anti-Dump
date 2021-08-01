# AntiDump
### A simple Anti-Dump to slow down and annoy attackers.

## Usage
1) Copy the class into your mod or loader.
2) Rename any instances of `dummy/class/path` to your mod package. 
3) Use the `check` function in `FMLPreInitializationEvent`. 

## Example:
```java
    @Mod.EventHandler
    public void init(FMLPreInitializationEvent event) {
        AntiDump.check();
    }
```

As mentioned in the [Falcon Forge](https://github.com/x4e/falcon-forge) repository, every one of these techniques can be bypassed, it is about slowing down and annoying the attacker as much as possible. 

This was ported to a single class because I wanted to reduce the amount of classes and make it more simple. 

## Credits
Thank you [BinClub](https://github.com/binclub/) for the original [Falcon Forge](https://github.com/x4e/falcon-forge) Anti-Dump. 
