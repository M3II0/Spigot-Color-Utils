# Tutorial
Learn how to use this utility

# Support
- Using reflections, so it should support every version above (1.7/1.8)

NOTE: If you use Gradient/HEX under 1.16, text won't be colorized!

# Colorizing classic text

```java
ColorUtils.colorize("&aLegacy text")
```
Examples:

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/e4391da7-fe02-458e-801f-f5c2a64ea5b5)

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/0a03fd17-2189-4dad-9094-64ca66b82240)


# Colorizing gradient (Hex Usage)

```java
ColorUtils.colorize("<#FF6600>Gradient colorized text</#9DFF8A>")
```
Examples:

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/661e2e07-29ac-4d0e-8c5b-30c0c9ef4303)

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/a69f4083-7a64-4f9d-9ad1-e595a6a07d16)

# Colorizing gradient (Legacy Usage)

```java
ColorUtils.colorize("<&a>Gradient with legacy codes!</&c>")
```
Examples:

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/e72bbf4e-b3fa-45be-a258-5b1d62aa8f9b)


# Colorizing gradient (Changing format in gradient text)

```java
ColorUtils.colorize("<#FF6600>&lBold text &nUnderlined Text</#9DFF8A>")
```
Examples:

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/e930a292-c07d-4537-a78b-0891289f7450)

# Colorizing gradient (Creating exception in gradient text)
(Create color exception, and continue in gradient)

```java
ColorUtils.colorize("<#FF6600>Colorized text &cEXCEPTION &rcontinue in gradient!</#9DFF8A>")
```
Examples:

![image](https://github.com/M3II0/Spigot-Color-Utils/assets/73041364/7a8ba645-35dd-44b1-b678-8dc53aeae01c)

# Removing colors

```java
# Insert here already colorized text!
ColorUtils.removeColors("§aRemove my colors!")
```

# Characters without color (List of characters)

```java
# Insert here already colorized text!
ColorUtils.charactersWithoutColors("§aCharacters without colors")

# Output:
# [C, h, a, r, a, c, t, e, r, s,  , w, i, t, h, o, u, t,  , c, o, l, o, r, s]
```

# Characters with color (List of characters)

```java
# Insert here already colorized text!
ColorUtils.charactersWithColors("§aCharacters without colors")

# Output:
# [§aC, §ah, §aa, §ar, §aa, §ac, §at, §ae, §ar, §as, §a , §aw, §ai, §at, §ah, §ao, §au, §at, §a , §ac, §ao, §al, §ao, §ar, §as]
```
