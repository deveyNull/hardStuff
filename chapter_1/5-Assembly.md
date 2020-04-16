# Assembly

[Check out our free course!](https://academy.hoppersroppers.org/mod/assign/view.php?id=1011)

Before we do anything else, let's read over about x86 assembly. 
<https://en.wikipedia.org/wiki/X86_assembly_language>

Specifically, look over the differences between Intel and AT&T syntax. In this course, and the vast majority of other online resources, you will be working with Intel syntax. 

The way to tell the difference at a glance is AT&T is littered with % symbols. The fundamental difference between the two is that Intel is (opcode) (destination) (source).

Most tools will have a way to switch between the two syntaxes. Using Objdump we open files using Intel syntax by using "-M intel" flags.

Alright, I understand that you don't actually know what is going on yet with Assembly, and that is fine. We are trying to get comfortable with it, not good at it. This is a fairly accessible resource to help you get a general guess at what is going on.  <https://en.wikibooks.org/wiki/X86_Assembly/Print_Version> There are also some example files on the Wikipedia page that might help out.

Work through this tutorial. Don't worry about understanding all of it, just work through and try to wrap your head around what is going on, not how any of it works.  You will have to install nasm with `sudo apt install nasm`.

<https://github.com/hoppersroppers/nightmare/blob/master/modules/03-beginner_re/csaw18_x86tour_pt1/stage1.asm>

Task: 

* Submit text discussing anything that you struggled with and didn't understand, and what you did to overcome that problem. If you still don't understand, tell us what specifically you did not understand.
[Visit the course page!](https://academy.hoppersroppers.org/mod/assign/view.php?id=1011)
