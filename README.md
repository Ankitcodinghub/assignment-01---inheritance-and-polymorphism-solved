# assignment-01---inheritance-and-polymorphism-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 01 – Inheritance and Polymorphism Solved](https://www.ankitcodinghub.com/product/assignment-01-inheritance-and-polymorphism-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;9197&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment 01 – Inheritance and Polymorphism Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
You may work in <strong>pairs </strong>(that is, as a <strong>group of two</strong>) with a <strong>partner </strong>on this assignment if you <strong>wish </strong>or you may work <strong>alone</strong>. If you work with a partner, only submit <strong>one </strong>lab project with <strong>both </strong>of your <strong>names </strong>in the <strong>source code file </strong>to Blackboard (BB) for grading; you will each earn the <strong>same </strong>number of points. What to <strong>hand in</strong>, and by <strong>when, </strong>is discussed below. <strong>Assignment Objectives</strong>

After completing this assignment the student should be able to,

<ul>
<li>Write an abstract base class in Java according to Interface specifications given in UML.</li>
<li>Implement base class Interfaces in java according to specifications given in UML.</li>
</ul>
<strong>Assignment Requirements</strong>

For this assignment you are given a Java source code file (CSE205_Assignment01.java) with a main method and supporting methods. You must write the following Java files to complete the program:

BankAccount.java&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;CheckingAccount.java

SavingsAccount.java&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;CreditcardAccount.java

The specifications for these files are given below (including the UML diagram on the following page). Special requirements:

<u>All Bank Accounts</u>

<ol>
<li>1. All bank accounts have a balance that is stored as an amount of penn</li>
<li>2. All money amounts are expressed in penn</li>
<li>3. All debit amounts will be subtracted from the balance, and all credit amounts will be added to the balan</li>
<li>4. All bank accounts have a non-negative interest rate (0.02 would be a 2% interest rate).</li>
<li>5. When applying interest, interest amount is calculated by multiplying the balance by the interest rat</li>
<li>6. When applying interest, interest amount is <strong>added </strong>to the balan</li>
<li>7. Interest will not be applied to any account with a balance of zero.</li>
<li>8. Debit methods will return false if the transaction cannot be made because of insufficient balance or insufficient credit limi Otherwise they will return true.</li>
</ol>
<u>Savings accounts</u>

<ol>
<li>1. A savings account cannot have a negative balanc</li>
<li>The debit method will return false if an attempt to overdraw the account is made.</li>
<li>2. The getAccoutInfoAsString method will return a string formatted like this:</li>
</ol>
Account type : Savings

Account #&nbsp;&nbsp; &nbsp;: 101101

Balance&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;: 12345

Interest rate : 0.01

<u>Checking accounts</u>

<ol>
<li>1. Any CheckingAccount debit that ends with a negative balance will incur an overdraftFee (i.e. the overdraftFee amount will be subtracted from the balance)</li>
<li>2. The getAccoutInfoAsString method will return a string formatted like this:</li>
</ol>
Account type : Checking

Account #&nbsp;&nbsp; &nbsp;: 202202

Balance&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;: 200000

Interest rate : 0.02

Overdraft fee : 2000

<u>Creditcard accounts</u>

<ol>
<li>1. The balance of a Creditcard account cannot overrun its credit limit</li>
<li>The debit method will return false if an attempt to overdraw the account is made.</li>
<li>2. Interest will not be applied to a Creditcard account with a positive balan</li>
<li>3. The getAccoutInfoAsString method will return a string formatted like this:</li>
</ol>
Account type : Creditcard

Account #&nbsp;&nbsp; &nbsp;: 303303

Balance&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;: -27550

Interest rate : 0.03

Credit limit : 1000000

&nbsp;

<strong>UML Class Diagram</strong>

&nbsp;

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/02/993.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">
