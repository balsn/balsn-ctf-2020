# Balsn CTF 2020

The top N domestic teams will be invited to another on-site competition on December 12th and 13th in Taipei, Taiwan.

- Date: 11/14 10:00 a.m. (UTC+8) ~ 11/16 10:00 a.m. (UTC+8)
- Format: Online Jeopardy
- [CTFtime link](https://ctftime.org/event/1122)
- Prize (the prize will be transferred in BTC or ETH.)
  - 1st place: $30,000 TWD
  - 2nd place: $23,000 TWD
  - 3rd place: $15,000 TWD
  - Balsn CTF 2020 Taiwan Stars (top 3 domestic teams, sponsored by HackerSir):
    - 1st place: $15,000 TWD
    - 2nd place: $10,000 TWD
    - 3rd place: $5,000 TWD

Results:
- 1st: Super ⚔️ Blue
- 2nd: The Flat Network Society
- 3rd: 10sec
- Balsn CTF 2020 Taiwan Stars (top 3 domestic teams):
  - 1st: 10sec
  - 2nd: NCtfU
  - 3rd: BambooFox

## Challenges

- [Balsn CTF 2020](#balsn-ctf-2020)                                                                                                                                         - [Challenges](#challenges)
  - [Misc](#misc)
    - [Show your Patience and Intelligence I](#show-your-patience-and-intelligence-i)
    - [Show your Patience and Intelligence II](#show-your-patience-and-intelligence-ii)
    - [IdleGame](#idlegame)
    - [Election](#election)
    - [Transformer: The Guardian Knight](#transformer-the-guardian-knight)
    - [The Last Bitcoin](#the-last-bitcoin)
  - [Crypto](#crypto)
    - [aeshash](#aeshash)
    - [IEAIE](#ieaie)
    - [Happy Farm](#happy-farm)
  - [Reverse](#reverse)
    - [babyrev](#babyrev)
    - [The Danger of Google's Omnipotence](#the-danger-of-googles-omnipotence)
  - [Web](#web)
    - [Windows XP Media Player](#windows-xp-media-player)
    - [The Woven Web](#the-woven-web)
    - [tpc](#tpc)
    - [L5D](#l5d)
  - [Pwn](#pwn)
    - [Machbook Air](#machbook-air)
    - [Machbook Pro](#machbook-pro)
    - [Diary](#diary)
    - [STACK](#stack)
    - [House of Cats](#house-of-cats)



## Misc

### Show your Patience and Intelligence I

* Solved: 8
* Author: nawmrofed
* Link: https://hackmd.io/@KSmbxBXYS--LGCt0iZmypw/r19D6WoiD

### Show your Patience and Intelligence II

* Solved: 24
* Author: nawmrofed
* Link: https://hackmd.io/@KSmbxBXYS--LGCt0iZmypw/r19D6WoiD

### IdleGame

* Solved: 4
* Author: shw
* Link: https://github.com/x9453/my-ctf-challenges#balsn-ctf-2020

### Election

* Solved: 5
* Author: shw
* Link: https://github.com/x9453/my-ctf-challenges#balsn-ctf-2020

### Transformer: The Guardian Knight

* Solved: 10
* Author: sasdf
* Link: 

### The Last Bitcoin

* Solved: 50
* Author: kevin47
* Writeup: `echo -en '\xff\n' | nc [ip] [port]`
The condition in run.sh will be passed if the process exit(1), which normally means that the verify_hash() returned True
But it turns out that the process not terminating normally will also exit(1)
Inputting `\xff` will crash python's input() because it can't be decoded to str as utf-8
If you execute run.sh locally, you can also simply press ctrl+c to get flag
* You can use `nc the-last-bitcoin.balsnctf.com 7123 -N` and Press ctrl+D

## Crypto

### aeshash

* Solved: 0
* Author: sasdf
* Link: 

### IEAIE

* Solved: 0
* Author: kevin47
* Link: HW

### Happy Farm

* Solved: 10
* Author: fweasd
* Link: 

## Reverse

### babyrev

* Solved: 33
* Author: sces60107
* Link: 

### The Danger of Google's Omnipotence

* Solved: 2
* Author: Frank Lin
* Link: https://www.notion.so/Balsn-CTF-2020-Writeup-The-Danger-of-Google-s-Omnipotence-2183588ae68548c3bf7648c24f756a3c

## Web

### Windows XP Media Player

* Solved: 5
* Author: bookgin
* Link: https://github.com/BookGin/my-ctf-challenges#balsn-ctf-2020

### The Woven Web

* Solved: 6
* Author: bookgin
* Link: https://github.com/BookGin/my-ctf-challenges#balsn-ctf-2020

### tpc

* Solved: 33
* Author: ysc
* Link: https://gist.github.com/YSc21/e5471285145cc5d34fe53c7d67a3d8f3

### L5D

* Solved: 17
* Author: kaibro
* Link: https://github.com/w181496/My-CTF-Challenges/tree/master/Balsn-CTF-2020#l5d

## Pwn

### Machbook Air

* Solved: 4
* Author: how2hack
* Link: https://github.com/how2hack/my-ctf-challenges/tree/master/2020/balsnctf-2020/machbookair

### Machbook Pro

* Solved: 1
* Author: how2hack
* Link: https://github.com/how2hack/my-ctf-challenges/tree/master/2020/balsnctf-2020/machbookpro

### Diary

* Solved: 18
* Author: jwang
* Link: https://github.com/jwang-a/CTF/tree/master/MyChallenges/Pwn/Diary

### STACK

* Solved: 0
* Author: jwang
* Link: HW
* Hint: https://github.com/jwang-a/CTF/tree/master/MyChallenges/Pwn/STACK

### House of Cats

* Solved: 0
* Author: jwang
* Link: HW
* Hint: https://github.com/jwang-a/CTF/tree/master/MyChallenges/Pwn/House_of_Cats
