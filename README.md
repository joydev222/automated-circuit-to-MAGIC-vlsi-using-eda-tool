# automated circuit to magic vlsi layout using open source eda tools.
<h6>
<p>
***This is project from virtual internship program offered by E&ICT IIT, Guwahati***
</p>
    </h6>
<br>
<p>
    <h4>Overview: </h4><br>
    ***
        <p>
        Circuit Design and Layout is one of the most important steps in the flow steps in VLSI. These are designed using  the manual processes. This could also be a time-consuming process. However, this can be resolved by using Open-Source EDA Tools by designing in some specific language. Circuit Simulation is carried out by some open-source EDA Tools and like MAGIC, e-Sim, etc. and layout can design in any tool like MAGIC, Microwind, etc. </p>
</p>
<br>
<h3>Sticks Layout & 𝝀-RULE: </h3><br>
<p>    In the designer draws a freehand sketch of a layout, using colored lines to represent the various process layers such as diffusion, metal and polysilicon. Where poly-silicon crosses diffusion, transistors are created and where metal wires join diffusion or polysilicon, contacts are formed. The advantage of this symbolic approach is that the designer does not have to worry about design rules, because the compactor ensures that the final layout is physically correct. All paths in all the layouts will be dimensions of 𝝀 units and subsequently 𝝀 can be allocated an appropriate value compatible with the feature size of the fabrication process. So, this would be easy-to-understand work for the designer.</p>
<br>
<h2>Implementation of Idea</h2><br>
    <p>Implementation is a simple approach, where we have a circuit for basic input. We have the e-Sim EDA tool for Automated MAGIC VLSI Circuit where the input is a circuit and we will use Python-Turtle [2] graphics as backend which will process the input circuit and returns back the layout according to the set of circuit. Thus, creating an efficient & time-saving tool for the future. The process cycle involves simple steps that reads the circuit and processes according to the stick diagram and 𝝀-Rule using Python-Turtle graphics as a backend engine to design the layout. Thus, producing a layout design as an output.

This engine is known as ***Automated Circuit to MAGIC VLSI Engine***.
</p>
<br>
<h2>Tools used for Implenting this Idea</h2><br>
<p>
    1. ngSpice layout editior
    2. Python 3.6 or up
    3. Turtle Graphics
</p>
<br>
