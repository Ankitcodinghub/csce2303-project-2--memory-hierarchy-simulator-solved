# csce2303-project-2--memory-hierarchy-simulator-solved
**TO GET THIS SOLUTION VISIT:** [CSCE2303 Project 2- Memory Hierarchy Simulator Solved](https://www.ankitcodinghub.com/product/csce2303-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118645&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCE2303 Project 2- Memory Hierarchy Simulator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Project Overview: The goal of this project is to implement a simple simulator for the memory caching system. This document details the requirements of the simulator.

Implementation language: Any general-purpose programming language. The resulting application can either be a console application or a graphical user interface (GUI) application (desktop, web-based, or mobile app) as a bonus feature.

Team Size: 2 or 3 students

The memory hierarchy: The basic requirements for the project assume a simplified read-only one-level caching system that uses direct mapping. The underlying memory address space is assumed to be a 32-bit byte-addressable memory (4 GB). Accessing the memory is assumed to take 100 clock cycles.

Simulator inputs:

1. Cache Information: The total cache size S, the cache line size L, and the number of cycles needed to access the cache (e.g., an integer between 1 and 10 clock cycles).

2. Access Sequence: A sequence of memory addresses that are accessed by a certain program. Addresses should be given in bytes. This sequence should be provided through a text file.

Simulation and simulation outputs: The simulator should trace the cache behavior given the input sequence of memory accesses by keeping track of the cache contents after each access (by updating the valid bits and tags associated with each cache line. The actual cache content is irrelevant). The cache is assumed to be initially empty. The simulator should also keep track of the number of accesses, the number of hits, and the number of misses. After each memory access and until the sequence ends, the program should output the following:

• Valid bits and tags of all entries

• Total number of accesses

• The hit and miss ratios

• The Average Memory Access Time (AMAT) of the memory hierarchy (in cycles)

Bonus features:

1. Building the application as a GUI application (either desktop, web-based, mobile app).

2. Supporting set and full associativity. In this case, in addition to the cache information listed above, the user will need to specify the associativity level.

3. Supporting multi-level cache hierarchies. In this case, the user of the simulator should specify the number of cache levels to simulate. For each cache level, the user will also need to specify: The total cache size S, the cache line size L, and the number of cycles needed to access the cache.

4. Supporting separate caches for instructions and data. In this case, each of the memory addresses in the provided sequence must be labelled as either an instruction or data access.

5. Supporting a read-write cache instead of just a read only cache. In this case, the user will need to specify the writing policy used (both in case of hit and in case of miss). Also, each of the memory addresses in the provided sequence must be labelled as either a read or write access.

General Guidelines

• Only one member of each group should submit on Blackboard. The submission should consist of a single compressed folder (zip or rar) which must include the following:

o A journal folder that contains the journal file of each team member. o A source code folder that contains the code you wrote using your chosen programming language. o A test folder that contains all input files (sequence files) used for testing.

o A PDF report that containing the following

 Students’ names and IDs

 A brief description of your implementation including any bonus features included.

 Any design decisions and/or assumptions you made.

 Any known bugs or issues in your simulator.

 A user guide showing how to compile and run your simulator including a full simulation example step-by-step with screenshots.

 A list of sequences you simulated. You should at least provide two 20-access sequences.

 Optionally, you can include a section about your experience working on this project. This section will NOT affect your grade in any way.

Grading Criteria

• Bonuses: Each bonus feature will count for 5% with a maximum of 2 bonuses worth 10%. Please do not be tempted to implement more than 2 bonus features, as this will cost you too much time.

• Deductions: o -5% for not following the required submission directory structure.

o -100% for plagiarized submissions.
