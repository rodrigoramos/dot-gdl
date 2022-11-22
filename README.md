# Example for DOT (Graph Description Language)

This repo contains an example how to create a [dot][1] diagram and "render it" using [Graphiz][2].

## The Example
The file `example.dot` is written using [DOT][1] language and we suggest that you use [Graphviz][2] to render the diagram itself.

### How to render
1. Download and install [Graphviz][2] at <https://graphviz.org/download/>;
0. At your terminal, input the following command:
    ```bash
     dot example.dot -K neato -T png -o output/example_output.png
    ```
0. Open the file `example_output.png` using your preferred image viewer;


## Next Steps

### Layout Engines
Try other types of layout engines (from "neato" to "nop"). All layout engines supported are listed in (Graphiz Docs)[https://graphviz.org/docs/layouts/].

### Use the Graphiz Visual Editor 
You can test some attributes e others configurations using the (Graphiz Visual Editor)[http://magjac.com/graphviz-visual-editor/].

### Create diagrams automatically 
You can also create your diagrams using your build services preferred like Azure DevOps, GitHub Actions and more...


## References

[1]: <https://en.wikipedia.org/wiki/DOT_(graph_description_language)> "DOT Language"
[2]: <https://graphviz.org/> "Graphviz"
