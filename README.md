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
In JSON format, object containing all the skills
```
{
    "nameOfSkill": {
        "hours": numberOfHours
        "dateStarted": startingDate
    }
}
```


Another dataset, preferably JSON containg relationships between skills. Something like...
```
{
    "parent": ["child1","child2"]
}
```
