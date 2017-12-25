# Asus-F450v 
**Summary**

##Language:
* English
* Chinese

-------
**Specs :**


```c
Method (_Q0E, 0, NotSerialized)  
{
    If (ATKP)
    {
        \_SB.ATKD.IANE (0x20)
    }
}
Method (_Q0F, 0, NotSerialized)
{
    If (ATKP)
    {
        \_SB.ATKD.IANE (0x10)
    }
}
```
