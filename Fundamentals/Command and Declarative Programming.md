# COMMAND BASED
##
There are two approaches to making an FRC robot: **Iterative**, and **Command-Based**, of which we use the latter.
<br/>

# Iterative and Command Based
Iterative is like designing an ordered list of instructions for the robot to follow.
Command based is like creating a seperate list of complex dance moves, then telling the robot the cirumstances in which to perform those dance moves.

##
# A quick table, summing up the uses
<table>
<thead>
  <tr>
    <th>Issue</th>
    <th>iterative</th>
    <th>Command-Based + Declarative</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Quick prototyping</td>
    <td>Good; makes it easy to prototype simple code</td>
    <td>Not needed; thinking about code structure for simple tests and whatnot isn't needed,</td>
  </tr>
  <tr>
    <td>dependence</td>
    <td>nightmarish; like soldering a lamp to a socket</td>
    <td>Non-existent (if you're smart) due to much more modular design</td>
  </tr>
  <tr>
    <td>Reading and comprehension</td>
    <td>Fine for short snippets of code, <br>but complex systems and developers will suffer greatly from the inherent <br>lack of clarity</td>
    <td>Easier to separate each function call and class into individual parts, <br>and debugging can be made much easier (if you're smart)</td>
  </tr>
  <tr>
    <td>Issuing Robot Orders</td>
    <td>Calling robot methods directly; easy to understand for a whole 5 seconds,<br>dependencies will FESTER</td>
    <td>Robot properties and actions are neatly fit into subsystems and commands, <br>allowing for greater control and mental ease</td>
  </tr>
  <tr>
    <td>reaction of pretentious team 1XX member</td>
    <td>dude what is this youre disgusting</td>
    <td>this is so good marry me</td>
  </tr>
</tbody>
</table>

###

If you yet hunger for perfection beyond Declarative, check out the SOLID principles, one of the most popular set of guidelines for clean code out there. I would recommend watching Tim Corey's videos on the priciples. They're boring as *redacted*, but they are presented carefully enough to actually teach. Another caveat is that he uses C#, which won't matter too much, as the principles are universal once you understand them, and C# and Java are fairly similar in basic syntax.
