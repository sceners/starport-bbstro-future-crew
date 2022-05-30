# Starport BBS by The Future Crew

#### Written for MS-DOS in 1993

[Original package](https://defacto2.net/f/b11aa7e)

![image](https://user-images.githubusercontent.com/513842/171067754-120eac42-4465-4632-9567-04e4b379f81d.png)

---

```
-- Starport Intro II V1.0 -- Source -- Copyright (C) 1993 Future Crew --

File:		Description;
SP2.COM 	the second starport intro
SP2.ASM 	the assembler source for it
MAKE.BAT	batch file to compile the demo

Read the beginning of SP3.ASM for more details about the intro.
```


```asm
;--------------------------------------------------------------------
;                  StarPort Intro II V1.0
;--------------------------------------------------------------------
;              Copyright (C) 1993 Future Crew
;--------------------------------------------------------------------
;                        code: Psi
;                       music: Skaven
;--------------------------------------------------------------------
;    This code is released to the public domain. You can do
;    whatever you like with this code, but remember, that if
;    you are just planning on making another small intro by
;    changing a few lines of code, be prepared to enter the
;    worldwide lamers' club. However, if you are looking at
;    this code in hope of learning something new, go right 
;    ahead. That's exactly why this source was released. 
;    (BTW: I don't claim there's anything new to find here,
;    but it's always worth looking, right?) 
;--------------------------------------------------------------------
;    The code is optimized mainly for size but also a little
;    for speed. The goal was to get this little bbs intro to
;    under 2K, and 1993 bytes sounded like a good size. Well,
;    it wasn't easy, and there are surely places left one could 
;    squeeze a few extra bytes off...
;      Making a small intro is not hard. Making a small intro
;    with a nice feel is very hard, and you have to sacrifice
;    ideas to fit the intro to the limits you have set. I had
;    a lot of plans (a background piccy for example), but well,
;    the size limit came first.
;      I hope you enjoy my choice of size/feature ratio in this
;    intro! In case you are interested, this was a three evening
;    project (the last one spent testing).
;--------------------------------------------------------------------
;    You can compile this with TASM, but the resulting COM-file
;    will be a lot larger than the released version. This is
;    because all the zero data is included to the result. The
;    released version was first compiled to a COM file, and then
;    a separate postprocessing program was ran which removed all
;    the zero data from the end of the file. If you are just 
;    experimenting, recompiling is as easy as MAKE.BAT. If you
;    want to make this small again, you have to do some work as
;    well, and make your own postprocessor.
;--------------------------------------------------------------------
```
