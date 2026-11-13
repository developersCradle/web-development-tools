# Section 02: Basic Debugging Features. ✅

 Introduction to Java Debugging Using Eclipse.

# What I Learned. ✅

- Debugging is a methodical process of finding and fixing the bugs in software.

<br>

- Breakpoint is pause in code.

<br>

- **Step Over (F6)**, Line get executed and control is given in next line


<div align="center">
    <img 
    src="stepOver.JPG" 
    alt="alt text" 
    width="500"
    />
</div>


- **Step Into (F5)**
    - Steps into function/method
- **Step Return (F7)**
    - Function/method will be executed and control is returned to caller

<div align="center">
    <img 
    src="stepReturn.JPG" 
    alt="alt text" 
    width="500"
    />
</div>


<hr>

<div align="center">
    <img 
    src="EclipseDebuggingTricks.JPG" 
    alt="alt text" 
    width="300"
    />
</div>


### **Step into selection**

<div align="center">
    <img 
    src="StepIntoSelection.JPG" 
    alt="alt text" 
    width="500"
    />
</div>


- If you want to go into code inside some chained methods
    - Example `int firstPersonAge = DataUtil.getPersonData().get(0).getAge();`. We would want to go inside `getAge()` whiteout putting breakpoint manually

1. We first focus on method where want to go → Right click and select **Step Into Selection(CTRL+F5)**

- We will find end in `getAge()`



<div align="center">
    <img 
    src="breakAfterStepInto.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

- We can ignore other breakpoints and run into specific line using

<div align="center">
    <img 
    src="runIntoLine.JPG" 
    alt="alt text" 
    width="500"
    />
</div>

- Skip all breakpoints. **Easy to leave on**!


<div align="center">
    <img 
    src="skipAllBreakPoint.JPG" 
    alt="alt text" 
    width="700"
    />
</div>

- We can evaluate expressions from `Highlight Expression` then click `Inspect`

<div align="center">
    <img 
    src="InspectExpressions.JPG" 
    alt="alt text" 
    width="400"
    />
</div>

- We can watch expression getting folded out
    - This can be also done in ahead in executed time

<div align="center">
    <img 
    src="InspectExpressionsResults.JPG" 
    alt="alt text" 
    width="300"
    />
</div>

<br>

- Execute can evaluate input ahead of time, just like inspect expression


<div align="center">
    <img 
    src="Execute.JPG" 
    alt="alt text" 
    width="600"
    />
</div>

<br>

<div align="center">
    <img 
    src="expressions.JPG" 
    alt="alt text" 
    width="400"
    />
</div>

- Expressions are also good way to evaluate values at execution time.
