# cs2204-homework-4-namedtuple-chemistry-solved
**TO GET THIS SOLUTION VISIT:** [CS2204 Homework 4-Namedtuple Chemistry Solved](https://www.ankitcodinghub.com/product/cs2204-homework-chemistry-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116686&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2204 Homework 4-Namedtuple Chemistry Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Objectives

Learn to use namedtuple

Learn to process data from a text file

Work with a list of (named)tuples

Implement string processing algorithms

Background

This assignment is about chemical elements,

compounds, and their modeling with computer software. You are given a database of the elements

( elements.txt ), which is a text file where each line describes one chemical element with four key properties using the following format:

&lt;number&gt; &lt;symbol&gt; &lt;name&gt; &lt;weight&gt;

where &lt;number&gt; is the atomic number (number of protons in the nucleus), &lt;symbol&gt; is the chemical symbol (one capital character, followed by zero, one or two lower case characters), &lt;name&gt; is the English name of the element (capitalized), and &lt;weight&gt; is the standard atomic weight

(https://en.wikipedia.org/wiki/Standard_atomic_weight) of the element. The four fields are separated by one or multiple space characters. It is a good idea to open this file in Spyder to better understand the format.

You are going to read this database and store the information in Python objects to answer some simple and more complex questions about elements and compounds.

Tasks

You need to finish the chemistry.py source file. Note: you can use the simple tests provided at the end of the file (by uncommenting those lines). Feel free to change / add / delete any testing code. The outputs of this testing code are not going to be graded. The validator program will use your code directly.

1. Create a new data type , called Element , using the collections.namedtuple (meta)class. Each instance of this data type should have four fields in this order (6 pts):

A. number : an integer value, the atomic number

B. symbol : a string value, the chemical symbol

C. name : a string value, the name of the element

D. weight : a float value, the standard atomic weight

2. Finish the load_elements function. The existing code shows how to open a text file and read it line by line. Your task is to break up the line to four parts, convert some parts to the right data type (see above), create an Element instance with the parts, and add them to the global elements list. (12 pts)

3. Implement the element_by_number function. You can use the global elements list (created by load_elements function). Check the documentation string (and the example testing code) for the expected behavior. (8 pts)

4. Implement the element_by_symbol function. You can use the global elements list (created by load_elements function). Check the documentation string (and the example testing code) for the

expected behavior. (8 pts)

5. Implement the element_by_name function. You can use the global elements list (created by load_elements function). Check the documentation string (and the example testing code) for the

expected behavior. (8 pts)

6. Implement the compound_elements function. You can use the global elements list (created by load_elements function). This function should return a list of unique Element objects for each

element present in the compound. The compound formula is a string containing a sequence of element symbols, followed by an optional number (number of atoms of a given element in the compound). If there is no number, there is one atom of the given element in the compound (25 pts).

E.g. “H2O” has two Hydrogen and one Oxygen atoms, therefore you should return a list of two elements (Hydrogen and Oxygen).

7. Implement the compound_weight function. This function should return a float, which is the total weight of the molecule. You need to sum the atomic weights (considering the number of atoms of the given element) in the compound. The molecular formula is in the same format as described for the previous task. (25 pts)

Hints

The last two tasks ( compound_elements and compound_weight ) are a bit more challenging. You need to process strings character by character to find elements and an optional sequence of numbers behind these. You can use the following string methods to decide if a character is an upper case, lower case, or numeric

In [ ]: ch1 = “A”

ch2 = “a” ch3 = “1”

print(f'”ch1″:’, ch1.isupper(), ch1.islower(), ch1.isnumeric()) print(f'”ch2″:’, ch2.isupper(), ch2.islower(), ch2.isnumeric()) print(f'”ch3″:’, ch3.isupper(), ch3.islower(), ch3.isnumeric())

“ch1”: True False False

“ch2”: False True False

“ch3”: False False True

Also, if you have a string of numeric character(s) you can convert this object to an integer, by the int() type/function:

Out[3]: (‘123’, 123)

Grading

Penalties

Points will be deducted if you fail to set __author__ variable (-10 pts) and for each PEP 8 style errors (-1 pt for each) in your program.

Submission

Please, upload the final version of the following file(s) (and only those files) to Brightspace:

chemistry.py
