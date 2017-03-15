# iRail-docs

iRail-docs provides documentation for the iRail api.
This includes documentation on the endpoints, parameters, responses and examples.

We use the open-source api blueprint standard for these docs.
See https://apiblueprint.org/ for more information.


## Installation and compiling

### Requirements
Before proceeding, the following software should be present on your system:

- NodeJs
- Npm

### Installation

To install aglio, run

    npm install -g aglio

### Rendering the documentation

To render the blueprints, you need to specify the input and destination. Theme parameters can be passed as well. 
The following command is used to render to 3 columns in a modern theme.

    aglio -i src/irail.apib -o render/index.html --theme-template triple --theme-variables streak

On unix based systems, the same can be achieved by running 
    
    ./render.sh

