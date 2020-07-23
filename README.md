## SKILL TREE APP

### Version 1
* [ ] Client
    * [x] Install D3.js
    * [ ] Graph Framework
    * [ ] Data Framework
        * [ ] General idea of Data
        * [ ] Tests with sample data
* [ ] Server


### General Form of the Data
A single JSON containing the skill information and the nodes, borrowed from https://observablehq.com/@d3/force-directed-graph
```
{
    nodes:[
      {
         id:"nameofSkill"
         group:"categoryofSkill"
      },
      {..},{..}
    ]
    links:[
      {
        source:"skillOne"
        target:"skillTwo"
      },
      {..},{..}
    ]
}
```
