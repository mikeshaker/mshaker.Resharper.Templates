# MShaker.Resharper.Templates

Collection of Resharper Templates (Live Templates and File Templates) to help when writing (mainly C#) code.

## Installation

Get the Git repo by typing the following into Git Bash:

`git clone https://github.com/mikeshaker/mshaker.Resharper.Templates.git`

To import a .DotSettings templates file into Resharper:

- Open Visual Studio
- Select drop down menu: **Resharper** -> **Tools** -> **Templates Explorer**
- In the Templates Explorer select the **Live Templates** or **File Templates** tab depending on what kind of template you want to import
- Select the C# scope (on the left) 
- Click on the "Import" toolbox button and select the .DotSettings file

## Live Templates

C# Live Templates for testing include:

- NUnit
- MSTest
- xUnit
- Specflow

Other C# Live Templates include:

- Test Builder
- Simple Factory
- log4net
- Override
- ToString

Other templates include:

- Markdown

### Usage

To insert a live template simply start typing its shortcut in your C# file (or press `Ctrl+J` or `Ctrl+E, L` to bring up the inline menu).

#### CSharp\Testing\NUnit Shortcuts

```
nunitclass                  // create a nunit class
nunitcleanup                // create a nunit test cleanup method
nunitclasscleanup           // create a nunit class cleanup method
nunitclasssetup             // create a nunit class setup method
nunitclassinner             // create a nunit inner class
nunitsetup                  // create a nunit setup method
nunitteardown               // create a nunit tear down method
nunittestcase1arg           // create a nunit test case attribute with 1 input arg
nunittestcase2arg           // create a nunit test case attribute with 2 input args
nunittestcase3arg           // create a nunit test case attribute with 3 input args
nunittestwhen               // create a nunit test
nunittestwhenasync          // create an async nunit test
```

#### CSharp\Testing\MSTest Shortcuts

```
mstestclass                 // create a mstest class
mstestclasscleanup          // create a mstest class cleanup method
mstestclasssetup            // create a mstest class setup method
mstestcleanup               // create a mstest cleanup method
mstestsetup                 // create a mstest setup method
mstestwhen                  // create a mstest test
```

#### CSharp\Testing\xUnit Shortcuts

```
xunitclassinner             // create a xunit inner class
xunitctor                   // create a xunit constructor
xunitfact                   // create a xunit fact test
xunitfactasync              // create a xunit fact async test
xunitinlinedata             // create a xunit inline data attribute
xunittheory                 // create a xunit theory test
xunittheoryasync            // create a xunit theory async test
```

#### CSharp\Testing\SpecFlow Shortcuts

```
specflowclass               // create a specflow class
specflowscenariosetup       // create a specflow setup for scenario method
specflowscenariocleanup     // create a specflow cleanup for scenario method
specflowtestsetup           // create a specflow test setup method
specflowtestcleanup         // create a specflow test cleanup method
specflowstepbefore          // create a specflow step before method
specflowstepafter           // create a specflow step after method
```

---


#### CSharp\Test Builder Shortcuts

```
testbuilder                 // create a testbuilder class
testbuilderdb               // create a testbuilder database class
testbuilderindb             // create a testbuilder "InDatabase" property
testbuilderas               // create a testbuilder "As" method
testbuilderwith             // create a testbuilder "With" method
testbuilderwithname         // create a testbuilder "With<name>" method
testbuilderwithnamenoargs   // create a testbuilder "With<name>" method that has no args
```

#### CSharp\Simple Factory Shortcuts

```
factory                     // create a simple factory & interface with Create method
factoryfor                  // create a simple factory & interface with CreateFor method
```

#### CSharp\log4net Shortcuts

```
log4netconfigure            // prints a call to log4net XML configure method
log4netlogger               // prints the Logger declaration
```

#### CSharp\Override Shortcuts

```
overrideequals              // override the Equals method
overridegethashcode         // override the GetHashCode method 
```

#### Markdown Shortcuts

```
blockquote
code-block
code-inline
em-bold
em-italics
em-strike
hr
image-inline
image-ref
link-inline
link-ref
list-ol-li
list-ul-li
```

## File Templates

C# file templates include:

- TestBuilder Class
- Simple Factory Class
- NUnit Class
- Exception Class

Other file templates include:

- Markdown
- JSON
- XML
- Text

### Usage

To choose from the list of file templates press `Ctrl+Alt+Insert`.

To place a new file from a file template in a particular place in Solution Explorer:

- Select in Solution Explorer where you want the file to be placed
- Press `Alt+Insert`
- Select the file template from the inline menu

