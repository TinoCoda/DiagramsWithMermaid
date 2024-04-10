# Using Mermaid to Generate Cool Diagrams from Text

You can directly generate your diagrams inside the markdown file provided that you have a mermaid plugin installed in your platform or IDE.
Here an example of a block diagram that is also listed in the medium article related to this repository.

```Mermaid

flowchart LR
    subgraph CPU["Central Processing Unit (CPU)"]
        direction TB
        ArithmeticUnit["Arithmetic & Logic Unit"]
        ControlUnit["Control Unit"]
        MemoryUnit["Memory Unit"]
        
        ArithmeticUnit-->ControlUnit-->ArithmeticUnit
        MemoryUnit-->ControlUnit-->MemoryUnit
    end
    InputUnit["Input Unit"]-->CPU 
    CPU-->OutputUnit["Output Unit"]

```

The diagrams that can be plotted vary from the simple block diagrams up to more advances diagrams like UML classes or sequence diagrams. I just want to list some diagrams found on the official website of mermaid. www.mermaid.js.org