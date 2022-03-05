<!-- Output copied to clipboard! -->

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.682 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Fri Mar 04 2022 14:53:16 GMT-0800 (PST)
* Source doc: SENG 438 Assignment 1 Report
* Tables are currently converted to HTML tables.
----->


**SENG 438 Assignment 3 Report**	

**Group: (18)**


<table>
  <tr>
   <td>
    Sr.
   </td>
   <td>
    Name
   </td>
   <td>
    UCID
   </td>
  </tr>
  <tr>
   <td>
    1.
   </td>
   <td>
    Ali Siddiqi
   </td>
   <td>
    30092156
   </td>
  </tr>
  <tr>
   <td>
    2.
   </td>
   <td>
    Jay Gurjar
   </td>
   <td>
    30096042
   </td>
  </tr>
  <tr>
   <td>
    3.
   </td>
   <td>
    Kai Wang
   </td>
   <td>
    30002810
   </td>
  </tr>
  <tr>
   <td>
    4.
   </td>
   <td>
    Mohamed Numan
   </td>
   <td>
    30086940
   </td>
  </tr>
</table>


**<span style="text-decoration:underline;">SENG 438 GROUP</span>**

**Introduction**

This lab is used to familiarize students with generic code coverage methods. EclEmma was used as the code coverage tool which most of us had installed from Assignment 2. We decided to use the same approach as we did in Assignment 2. We decided that half of us would be on the Range and the other half on Data. Utilities. Most of our previous code had over 50% coverage and we added test cases to Range and Data Utilities to get the desired percentage. Each team later checked on each other to ensure the test cases were satisfactory and we also asked each other questions throughout the process. We learned that dividing group work into teams and checking on each other works really well for us and allows us to complete the assignments easily and quickly.  

**A detailed description of the testing strategy for the new unit test.**

The unit tests were developed based on the strategy we learned for white box testing. Test cases were developed based on the source code provided. EclEmma was initially used to get an initial glance at code coverage and then additional test cases were added for Branch Coverage and Statement Coverage. Line Coverage was already at over 90%. The code was then reviewed by the other team to make sure we didn't have any bugs. 

**A high-level description of five selected test cases you have designed using coverage information, and how they have increased code coverage**

**For range:**

For the combineShouldBeEqualTor1 () we increase our statement coverage by testing the different functions in the range such as .combine(), .getUpperBound() to increase our coverage. We tested combining different ranges and testing with their upper bounds as well.

For the equalsTest() we increased our statement branch coverage since the if(test.equals(“hello”)) local = true

Else local = false 

Allows for the first if condition to be false and the else to which increased branch coverage.

For the combiningIgnoringNan5() method we increased branch coverage through the if and else statements:

if(r3== null) assertTrue(true);

Else assertTrue(false);

  

**Have 2 tests for the data utilities**

**(Add stuff Kai and Numan)**

**Detailed report of coverage achieved of each class and method.**

The screenshots can be found [here](/ScreenShots).

**Pros and Cons of coverage tools used and Metrics reported**

EclEmma was used with Eclipse IDE as code coverage tool. 

**Pros:**



* The tool could be installed from Eclipse, therefore eliminating any 3rd party requirements. 
* A vast variety of coverages metrics is included for ease. 
* Color coding illustrates if a method has been partially or fully tested.
* Metrics included for branches tested or missed which was very useful to increase code coverage. 

**Cons:**



* There is no information on which particular branch was missed, only a specific number stating which branches were covered. This made debugging complicated. 

**A comparison of advantages and disadvantages of requirements-based test generation and coverage-based test generation.**

**Advantages of requirements-based test generation:**



* Promotes a more creative approach to testing methods. 
* The simplicity of test creation is based on requirement boundaries.

**Disadvantages of requirements-based test generation:**



* Lack of confirmation in regards to what extent the code needs to be tested/covered.

**Advantages of coverage-based test generation:**



* Extensive testing and more targeted unit test

**Disadvantages of coverage-based test generation:**



* Requires in-depth knowledge and understanding of the source code. 
* Requires a lot of time and resource commitment to achieve full coverage.

**Teamwork/effort division:**

We decided that half of us would be on the Range and the other half on Data. Utilities. Each pair of teams completed the code coverage for each section. We then wrote added test cases to get the desired coverage. Each team later checked on each other to ensure the test cases were satisfactory and we also asked each other questions throughout the process. 

**Difficulties Encountered**

Developing unit tests to get high code coverage. 

**Lessons Learned**

We learned how to use EclEmma and create units tests that maximize coverage.


**Comments and Feedback**

In the lab, we got the chance to learn more about different methods of code coverage test cases and how it's important to have good test coverage especially. All in all, an interesting lab to do. 