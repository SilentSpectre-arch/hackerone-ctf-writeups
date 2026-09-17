# Trivial — CTF Write-up

**Category:** Web
**Difficulty:** Trivial
**Points:** 1

## Solution

The first thing I did was inspect the page source using `Ctrl + U`.

While reviewing the source code, I noticed a hidden URL pointing to:

```text
background.png
```

I appended `background.png` to the original URL and accessed it directly:

```text
http://target.com/background.png
```

The page returned the flag.

## Flag

```text
FLAG{...}
```

> **Note:** Replace `FLAG{...}` with the actual flag if you want to include it in the write-up.
