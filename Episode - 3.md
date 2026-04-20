### Episode 3

# Counting like a machine

## inc & dec [plus one, minus one]

- `inc ax` — **add** 1 to box **ax** (increment)
- `dec ax` — **subtract** 1 from box **ax** (decrement)

**Example:**
- `mov ax, 5`
- `inc ax` — now **ax** = 6
- `dec ax` — now **ax** = 5 again

**Nothing difficult.**

## Flags [if-else for CPU]

- **CPU** has hidden boxes. They store **yes/no** answers.
- After `sub ax, bx`:
  - **ZF (Zero Flag)** = 1 if result is **zero**
  - **ZF** = 0 if result is **not zero**

## Compare like if-else:
- `cmp ax, bx` — compare **ax** with **bx**
- `je label` — **jump if equal** (if **ZF** = 1)
- `jne label` — **jump if not equal** (if **ZF** = 0)

**This is just if-else. You already know it.**

## My notebook (5 months of learning)

[Здесь будет ссылка на твой файл с заметками]

# Comming to Episode - 4!
